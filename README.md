impor java.util.Scanner;
public class Cmr{
        public static void main(String[] args){
               Scanner sc=new scanner(System.in);
               System.out.println("enter a character")
               int a=sc.next().charAt(0);
               System.out.println(a);
        }
}
half revese array
import java.util.Scanner;
public class Main{
    public static void main(String[] args) {
        Scanner scanner=new Scanner(System.in);
        System.out.print("Enter the size of the array: ");
        int size=scanner.nextInt();
        int[] array=new int[size];
        System.out.println("Enter the elements of the array:");
        for(int i = 0;i < size;i++){
            array[i]=scanner.nextInt();
        }
        int temp;
        for (int i=0,j=(size/2)-1;i<size/4;i++,j--) {
            temp=array[i];
            array[i]=array[size-1-i];
            array[size-1-i]=temp;
        }
        for (int i=0;i<size;i++) System.out.print(array[i]+" ");
    }
}
HASHING;how many times a number is repeating.
													
