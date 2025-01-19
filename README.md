# sum-of-array
import java.util.Scanner;


public class SumOfArray {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);


        // Input the size of the array
        System.out.print("Enter the number of elements in the array: ");
        int size = scanner.nextInt();


        // Create an array of the given size
        int[] array = new int[size];


        // Input array elements
        System.out.println("Enter the elements of the array:");
        for (int i = 0; i < size; i++) {
            System.out.print("Element " + (i + 1) + ": ");
            array[i] = scanner.nextInt();
        }


        // Calculate the sum of array elements
        int sum = 0;
        for (int i = 0; i < size; i++) {
            sum += array[i];
        }


        // Display the sum
        System.out.println("The sum of the array elements is: " + sum);


        // Close the scanner
        scanner.close();
    }
}


OUTPUT:


Enter the number of elements in the array: 5
Enter the elements of the array:
Element 1: 10
Element 2: 20
Element 3: 30
Element 4: 40
Element 5: 50
The sum of the array elements is: 150






