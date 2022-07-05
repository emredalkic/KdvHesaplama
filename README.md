# KullanicidanVeriAlmaimport java.util.Scanner;

public class KdvHesaplamaAracı {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int tutar;


        System.out.println("Lütfen Tutarı Giriniz  : ");
        tutar = input.nextInt();

        double kdv = tutar*0.18;
        double total = tutar+kdv;
        System.out.println("KDV TUTARINIZ  : "+kdv);
        System.out.println("TOPLAM TUTARINIZ  : "+total);


    }
}
