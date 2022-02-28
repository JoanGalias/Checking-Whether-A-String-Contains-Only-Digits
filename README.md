#Checking-Whether-A-String-Contains-Only-Digits.            

package program;

public class Digits {

  public static void main(String[] args) {

String str = "ABCD 1234";
     boolean result = str.matches("[0-9]+");
     System.out.println("Original String : " + str);
     System.out.println("Does string contain only Digits? : " + result);
    }

   
  }
