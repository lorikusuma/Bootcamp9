# Bootcamp9
Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 1
public class Biodata{

   public static void main(String args[]){
      char[] nameString = {"Name : Lori Kusuma Dewi"};  
      System.out.println( nameString );
   }
   public static void main(String args[]){
      char[] addressString = {"Address : Blitar, Jawa Timur"};  
      System.out.println( addressString );
   }
   public static void main(String args[]){
      char[] hobbiesArray = { 'photography', ',', 'traveling', 'readinig', '.'};
      String hobbiesString = new String(hobbiesArray);  
      System.out.println( hobbiesString );
   }

   public static void main(String[]args){
        boolean a, b;
        a = No;
        b = Yes;
        if(a){
            System.out.println("boolean bernilai No");
        }if(b){
            System.out.println("boolean bernilai Yes");
        }
        System.out.println("is_married");
   }
   public static void main(String args[]){
      char[] universityString = {"University : Universitas Jember"};  
      System.out.println( universityString );
   }
   public static void main(String args[]){
      char[] skillArray = { 'MATLAB', ',', 'Photoshop', 'EChem', '.'};
      String skillString = new String(hobbiesArray);  
      System.out.println( skillString );
   }
}

Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 2
function validasi(form){
if(form.pass.value.length == 0) {
	alert("Masukkan password Anda");
	return false;
	}
	if(form.pass.value.length < 8){
		alert("password harus 8 karakter");
		return false;
	}
	for (var i = 0; i < form.pass.value.length; i ++){
		var ch = form.pass.value.charAt(i);
		if((ch < "A" || ch > "Z") && (ch < "a" || ch > "z") && (ch < "0" || ch > "9")){
			alert("password memuat karakter - karakter ilegal");
			return false;
		}
	}
	alert("password OK!");
	return true;
}

Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 3

public void paint(image) {
for (int x = 0; x < this.widthInTiles; x++) {
    for (int y = 0; y < this.heightInTiles; y++) {
	    final BufferedImage img = this.state.tiles[x][y];
	    if (img != null) {
		image.drawImage(img, x * this.tileWidth, y * this.tileHeight, null);
		System.out.print("*");
	    }
	System.out.print("=");
	}
    }
}
   }
          
Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 4

#include <stdio.h>
#include <stdlib.h>
int main()
{
int hargaTotal=15500;
int bayar;
int kembalian;
int limaratus, seribu, duaribu, limaribu, sepuluhribu, duapuluhribu, limapuluhribu;
int sisakembalian, sisakembalian2, sisakembalian3, sisakembalian4, sisakembalian5, sisakembalian6, sisakembalian7;

printf("Masukan NIlai Pembayaran\t:"); scanf("%d", &bayar);
system("CLS");
//Total Kembalian
kembalian=bayar-hargaTotal;

//jumlah pecahan 50000
sisakembalian=(kembalian%50000);
limapuluhribu=(kembalian-sisakembalian)/50000;
//jumlah pecahan 20000
sisakembalian2=(sisakembalian%20000);
duapuluhribu=(kembalian-sisakembalian2)/20000;
//jumlah pecahan 10000
sisakembalian3=(sisakembalian2%10000);
sepuluhribu=(kembalian-sisakembalian3)/50000;
//jumlah pecahan 5000
sisakembalian4=(sisakembalian3%5000);
limaribu=(kembalian-sisakembalian)4/5000;
//jumlah pecahan 2000
sisakembalian5=(sisakembalian4%2000);
duaribu=(kembalian-sisakembalian5)/2000;
//jumlah pecahan 1000
sisakembalian6=(sisakembalian5%1000);
seribu=(kembalian-sisakembalian6)/1000;
//jumlah pecahan 500
sisakembalian7=(sisakembalian6%500);
limaratus=(kembalian-sisakembalian6)/500;

//tampilan hasil input
printf("\n Total Harga \t: %d\n\n",hargaTotal);
printf("\n Nilai Bayar \t: %d\n\n",bayar);
printf("\n Kembalian \t: %d\n\n",kembalian);
printf("------------------------------\n");
printf("\n Jumlah Pecahan 50000\t: %d\n\n",limapuluhribu);
printf("\n Jumlah Pecahan 20000\t: %d\n\n",duapuluhribu);
printf("\n Jumlah Pecahan 10000\t: %d\n\n",sepupuluhribu);
printf("\n Jumlah Pecahan 5000\t: %d\n\n",limaribu);
printf("\n Jumlah Pecahan 2000\t: %d\n\n",duaribu);
printf("\n Jumlah Pecahan 1000\t: %d\n\n",seribu);
printf("\n Jumlah Pecahan 500\t: %d\n\n",limaratus);

printf("\n");
System("pause");
}

Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 5

class perulangan  
{  
    static int count_Handshake(int n) 
    { 
        return (n * (n - 1)) / 2; 
    } 
      
      
    public static void main (String[] args) 
    { 
        int n = 15; 
        System.out.println( count_Handshake(n)); 
    } 
} 

Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 6

//A. Categories 1, Product 1,2 Categories 2, Product 3,4 Categories 3 Product 5

//B. query SQL
SQL> id, category_name, products
INSERT INTO nama_tabel('id', 'category_name', 'product' ) 
VALUES('id', 'category_name', 'prodducts');

Bootcamp Arkademy Batch 9 Kloter 3  TIPE SOAL : E no 7
<td> <?php echo $data; ?> </td>

SQL> id, category_name, products
INSERT INTO nama_tabel('id', 'category_name', 'product' ) 
VALUES('id', 'category_name', 'prodducts');
