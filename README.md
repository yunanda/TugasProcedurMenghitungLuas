TugasProcedurMenghitungLuas
===========================

package id.blits.Tugas;


public class NewMainMenu {

 
    public static void main(String[] args) {
        // TODO code application logic here
        PersegiPanjang PP =  new  PersegiPanjang();
        PP.nama="Persegi Panjang";
        PP.Panjang=30;
        PP.Lebar=15;
        
        PP.tampilPersegiPanjang();
        
        Segitiga Segi = new Segitiga();
        Segi.nama="Menghitung Luas Segi Tiga";
        Segi.Alas=30;
        Segi.Tinggi=50;
        
        Segi.tampilSegiTiga();
        
        Lingkaran Ling = new  Lingkaran();
        Ling.nama="Menghitung Luas Lingkaran";
        Ling.Jari2=10;
        
        Ling.tampilLingkaran();

        

        
    }
    
}
