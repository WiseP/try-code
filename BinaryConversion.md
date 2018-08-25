
package conversion;

import static java.lang.Integer.toBinaryString;
import java.util.Scanner;
import javax.swing.JOptionPane;

/**
 *
 * @author Peter
 */
public class Conversion {

  
    public static void main(String[] args) {
         double input;
  String outputb;
   int binaryform;
         
        
        
       System.out.print("Enter the number you want to convert to binary \n");

       
        Scanner read = new Scanner(System.in);
       
        
       input = read.nextDouble();
       
       
       outputb = toBinaryString((int) input);
       binaryform = Integer.parseInt(outputb);
       
       System.out.println("your answer is   \n" + binaryform);
       
                  
        }
       
        // TODO code application logic here
    }

  
    

