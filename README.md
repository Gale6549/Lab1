import java.util.Scanner; 

public class Main {
  public static void main(String[] args) {
    Scanner s = new Scanner(System.in);  
    System.out.println("Enter Radius:");

    Integer Radius = s.nextInt();  
    Double Area=3.14*Radius*Radius;
    
    System.out.println("The radius is:"+Radius+ "The area is:"+ Area);  
  }
}
