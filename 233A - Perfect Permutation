import java.util.*;
public class A_Perfect_Permutation {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int t=sc.nextInt();
        if(t%2==1){
            System.out.println(-1);
        }
        else {
            int arr[]=new int[t];
            int k=1;
            for(int i=0;i<t;i++){
                arr[i]=k;
                k++;
            }
            for(int i=0;i<t;i+=2){
                int temp=arr[i];
                arr[i]=arr[i+1];
                arr[i+1]=temp;
            }
            for(int i=0;i<t;i++){
                System.out.print(arr[i]+" ");
            }
        }
}
}
