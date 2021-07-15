import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    System.out.println("Welcome to the check value");
    System.out.println("Enter the first number");
    Scanner num1=new Scanner(System.in);
    int numm1=num1.nextInt();
    System.out.println("Enter the second number");
    Scanner num2=new Scanner(System.in);
    int numm2=num2.nextInt();
    if(numm1<numm2){
      System.out.println("First number is greater than second number");
      }
      else if(numm1==numm2){
        System.out.println("Both the number or equal");
      }
else{
  System.out.println("Second number is greater than first number");
}
    }
  }
