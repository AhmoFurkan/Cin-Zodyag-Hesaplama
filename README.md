# Cin-Zodyag-Hesaplama
Java ile kullanıcıdan doğum tarihini alıp Çin Zodyağı değerini hesaplayan program yazınız.
import java.util.Scanner;

     public class Main {

     public static void main(String[] args) {

        int dateOfBirth;
        Scanner inp = new Scanner(System.in);
        System.out.print("Doğum Yılınızı Giriniz : ");
        dateOfBirth = inp.nextInt();


        if (dateOfBirth % 12 == 0) {
            System.out.println("Çin Zodyağı Burcunuz : Maymun");
        } else if (dateOfBirth % 12 == 1) {
            System.out.println("Çin Zodyağı Burcunuz : Horoz");
        } else if (dateOfBirth % 12 == 2) {
            System.out.println("Çin Zodyağı Burcunuz : Köpek");
        } else if (dateOfBirth % 12 == 3) {
            System.out.println("Çin Zodyağı Burcunuz : Domuz");
        } else if (dateOfBirth % 12 == 4) {
            System.out.println("Çin Zodyağı Burcunuz : Fare");
        } else if (dateOfBirth % 12 == 5) {
            System.out.println("Çin Zodyağı Burcunuz : Öküz");
        } else if (dateOfBirth % 12 == 6) {
            System.out.println("Çin Zodyağı Burcunuz : Kaplan");
        } else if (dateOfBirth % 12 == 7) {
            System.out.println("Çin Zodyağı Burcunuz : Tavşan");
        } else if (dateOfBirth % 12 == 8) {
            System.out.println("Çin Zodyağı Burcunuz : Ejderha");
        } else if (dateOfBirth % 12 == 9) {
            System.out.println("Çin Zodyağı Burcunuz : Yılan");
        } else if (dateOfBirth % 12 == 10) {
            System.out.println("Çin Zodyağı Burcunuz : At");
        } else if (dateOfBirth % 12 == 11) {
            System.out.println("Çin Zodyağı Burcunuz : Koyun");
        }
      }
     }
     
     
     
  
  
  
  ![image](https://user-images.githubusercontent.com/107626332/179390293-a72a7857-000f-420f-a9cc-48a8ce112895.png)


