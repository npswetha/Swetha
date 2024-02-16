//print same difference pairs
class Main {
    public static void main(String[] args) {
        int[] a = new int[]{1, 2, 3, 4, 5};
        int c;
        int t;
        for (int i = 0; i < 5; i++) {
            for (int j = i+1 ; j <5; j++) {
                if((a[i] - a[j])==(a[j]-a[i]));
                 
                
                 {
                    System.out.println(a[i] + " " + a[j]); 
                }
            }
        }
    }
}


//find coolest number
import java.util.*;

class Main {
    public static void main(String[] args) {
        int[] a = new int[5];
        Scanner b = new Scanner(System.in);
        
        // Taking input
        System.out.println("Enter 5 integers:");
        for (int i = 0; i < 5; i++) {
            a[i] = b.nextInt();
        }
        
        // Finding cool numbers
        System.out.println("Cool numbers:");
        for (int i = 0; i < n; i++) {
            if (a[i] + a[i+1] == a[i+2] + a[i+3]) {
                System.out.println(a[i] + " and " + a[i+1]);
            }
        }
    }
}
   //subset of Array
   import java.io.*;
 
class GFG {
 
    
    static int nCr(int n, int k)
    {
        int C[][] = new int[n + 1][k + 1];
        int i, j;
 

        for (i = 0; i <= n; i++) {
            for (j = 0; j <= Math.min(i, k); j++) {
                // Base Cases
                if (j == 0 || j == i)
                    
                else
                    C[i][j] = C[i - 1][j - 1] + C[i - 1][j];
            }
        }
        return C[n];
     int Subsets(int arr[], int N)
    {
        int sum = 0;
        for (int i = 0; i < N; i++)
            sum += arr[i];
 
        for (int n = 1; n <= N; n++)
 
            
            result += (double)(sum * (nCr(N - 1, n - 1))) / n;
 
        return result;
    }
 

    public static void main(String[] args)
    {
        int arr[] = { 2, 3, 5, 7 };
        int N = arr.length;
        System.out.println(Subsets(arr, N));
    }
}
