# not_Hesaplama
Patika.dev not hesaplama

package giris;

import java.util.Scanner;

public class Baslangic {
            public static void main(String[]args){
                short matematik, fizik, kimya, turkce, tarih, muzik;

                Scanner puan = new Scanner(System.in);

                System.out.print("Matematik notu:");
                matematik = puan.nextShort();

                System.out.print("Fizik notu:");
                fizik = puan.nextShort();

                System.out.print("Kimya notu:");
                kimya = puan.nextShort();

                System.out.print("Türkçe notu:");
                turkce = puan.nextShort();

                System.out.print("Tarih notu:");
                tarih = puan.nextShort();

                System.out.print("Müzik notu:");
                muzik = puan.nextShort();


                int toplam = (matematik + fizik + kimya + turkce + tarih + muzik);
                float sonuc = toplam / 6f;

                System.out.println("ortalaması:" + sonuc );
                String kosul = (sonuc >= 60) ? "başarılı." : "başarısız.";
                System.out.print(kosul);
            }
}

