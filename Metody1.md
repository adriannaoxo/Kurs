import java.util.Scanner;

public class Metody{

  public static void main(String[] args) {
  
    System.out.print("Podaj temperaturę ");
    Scanner scan = new Scanner(System.in);
    double tempreture = scan.nextDouble();
    
    tempCheck(tempreture);
  }
  
  private static void tempCheck (double tempreture){
    if(tempreture>0){
      System.out.println(tempreture + " to temperatura dodatnia");
    }
    else{
      System.out.println(tempreture + " to temperatura ujemna");
    }
  }
}
