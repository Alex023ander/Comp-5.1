# Comp-5.1
Creates a program that reads if a year is a leap year or not.
import java.util.Scanner;
public class Comp51 {

    
    public static void main(String[] args) {
       int year;
      System.out.println("Enter an Year:  ");
      Scanner sc = new Scanner(System.in);
      year = sc.nextInt();

      if (((year % 4 == 0) && (year % 100!= 0)) || (year%400 == 0))
         System.out.println(year + " is a leap year");
      else
         System.out.println(year + " is not a leap year");
   }
}
