  //   # Temperature_Conversion
import java.util.Scanner;

public class TemperatureConversion {
    public static void main(String[] args) {
        Scanner input =new Scanner(System.in);
        float C =input.nextFloat();
        float F = C * 9/5 + 32;
        System.out.println(F);


    }
    
}
