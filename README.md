# vucut-kitle-endeksi
//patika.dev vücut kitle endeksi hesaplama ödevi

import java.util.Scanner;
public class main {
    public static void main (String[]args) {
    double boy, kilo, vki;
    Scanner input = new Scanner(System.in);
    System.out.println("Lütfen boyunuzu Metre cinsinden giriniz:");
    boy = input.nextInt();
    Scanner inp = new Scanner (System.in);
    System.out.println("Lütfen kilonuzu Kilogram cinsinden giriniz:");
    kilo = inp.nextInt();
    vki = (kilo  / boy * boy);
    System.out.print("Vücut kitle indeksiniz:"+ vki);
    }
}
