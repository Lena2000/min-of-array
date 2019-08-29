package javaapplication16;

import java.util.Scanner;
import static jdk.nashorn.tools.ShellFunctions.input;

/**
 *
 * @author LENOVO
 */
public class JavaApplication16 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int []numbers=new int[10];
        System.out.println("Input elements of array:");
        for(int i=0; i<10; i++){
            numbers[i]=input.nextInt();
        }
        int min=numbers[0];
        for(int i=0; i<numbers.length; i++)
        {   if (min>numbers[i])
            min=numbers[i];
            }
        System.out.println("Minimal element - "+ min);

}
}
