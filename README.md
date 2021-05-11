// usingSwitch
import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        System.out.println("enter ur choice 1.>=90   2.80<=marks<90  3.70<=marks<80  4.60<=marks<70  5.50<=marks<60  6.40<=marks<50  :)");
        Scanner sc = new Scanner(System.in);
        int choice = sc.nextInt();
        switch(choice)
        {
            case(1) : 
                      System.out.println("your grade is 'O'  :) ");
                      break;
            case(2) : 
                      System.out.println("your grade is 'A+'  :) ");
                      break;
            case(3) : 
                      System.out.println("your grade is 'A'  :) ");
                      break;
            case(4) : 
                      System.out.println("your grade is 'B+'  :) ");
                      break;
            case(5) : 
                      System.out.println("your grade is 'B'  :) ");
                      break;
            case(6) :  
                      System.out.println("your grade is 'C'  :) ");
                      break;
                      
            default :
                        System.out.println("WRONG CHOICE....!");
        }
        
        
    }
}
