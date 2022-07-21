import java.util.Scanner;
public class ddwfwf {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    int sayi1,sayi2,islem;

    Scanner input = new Scanner(System.in);
    System.out.print("Birinci Sayıyı Giriniz: ");
    sayi1 = input.nextInt();
    System.out.print("İkinci Sayıyı Giriniz: ");
    sayi2 = input.nextInt();

    System.out.println("1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme");
    System.out.print("Lütfen İşlem Türünğ Seçiniz: ");
    islem = input.nextInt();

    switch (islem){
        case 1:
            System.out.print("İşlem Sonucu: "+(sayi1+sayi2));
            break;

        case 2:
            System.out.print("İşlem Sonucu: "+(sayi1-sayi2));
            break;

        case 3:
            System.out.print("İşlem Sonucu: "+ (sayi1*sayi2));
            break;

        case 4:
            System.out.print("İşlem Sonucu: "+(sayi1/sayi2));
            break;

        default:
            System.out.print("Lütfen Geçerli Bir Sayı Giriniz!!! ");
    }


    }

}
