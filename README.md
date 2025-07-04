# Assignment-
Assi
import java.util.Scanner;

public class ArrayExample {
    public static void main(String[] args) {
        int[] arr = new int[10]; // Declare array of size 10
        Scanner sc = new Scanner(System.in);

        // Populate the array with user input
        System.out.println("Enter 10 integers:");
        for(int i = 0; i < 10; i++) {
            arr[i] = sc.nextInt();
        }

        // Print all values
        System.out.println("The array values are:");
        for(int i = 0; i < 10; i++) {
            System.out.print(arr[i] + " ");
        }
        System.out.println();
    }
}
#include <iostream>
using namespace std;

int main() {
    int arr[10]; // Declare array of size 10

    // Populate the array with user input
    cout << "Enter 10 integers:" << endl;
    for(int i = 0; i < 10; i++) {
        cin >> arr[i];
    }

    // Print all values
    cout << "The array values are:" << endl;
    for(int i = 0; i < 10; i++) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}
