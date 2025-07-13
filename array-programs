import java.util.*;

public class ArrayOperations {
    public static void main(String[] args) {
        int[] arr = {10, 50, 30, 20, 40};

        System.out.println("Original array:");
        printArray(arr);

        Arrays.sort(arr);
        System.out.println("Sorted array:");
        printArray(arr);

        System.out.println("Max: " + findMax(arr));
        System.out.println("Min: " + findMin(arr));

        System.out.println("Reversed array:");
        reverseArray(arr);
        printArray(arr);
    }

    static void printArray(int[] arr) {
        for (int n : arr)
            System.out.print(n + " ");
        System.out.println();
    }

    static int findMax(int[] arr) {
        int max = arr[0];
        for (int n : arr)
            if (n > max) max = n;
        return max;
    }

    static int findMin(int[] arr) {
        int min = arr[0];
        for (int n : arr)
            if (n < min) min = n;
        return min;
    }

    static void reverseArray(int[] arr) {
        int start = 0, end = arr.length - 1;
        while (start < end) {
            int temp = arr[start];
            arr[start] = arr[end];
            arr[end] = temp;
            start++;
            end--;
        }
    }
}
