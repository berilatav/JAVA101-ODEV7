Manav Kasa Programı

Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.
Meyveler ve KG Fiyatları

Armut : 2,14 TL
Elma : 3,67 TL
Domates : 1,11 TL
Muz: 0,95 TL
Patlıcan : 5,00 TL

import java.util.Scanner;
public class Odev7 {

    public static void main(String[] args) {

        double armut = 2.14;
        double alinanArmut;
        double elma = 3.67;
        double alinanElma;
        double domates = 1.11;
        double alinanDomates;
        double muz = 0.95;
        double alinanMuz;
        double patlican = 5;
        double alinanPatlican;


        Scanner input = new Scanner (System.in);
        System.out.println("Armut kaç kilo ? ");
        alinanArmut = input.nextDouble();

        System.out.println("Elma kaç kilo ? ");
        alinanElma = input.nextDouble();

        System.out.println("Domates kaç kilo ? ");
        alinanDomates = input.nextDouble();

        System.out.println("Muz kaç kilo ? ");
        alinanMuz = input.nextDouble();

        System.out.println("Patlıcan kaç kilo ? ");
        alinanPatlican = input.nextDouble();

        double tutar = ((alinanArmut * armut ) + (alinanElma * elma) + (alinanDomates * domates) + (alinanMuz * muz) + (alinanPatlican + patlican));
        System.out.println("Toplam Ödenecek tutar " + tutar);

    }

}

   
