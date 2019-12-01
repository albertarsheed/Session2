# Session2
import java.io.*;
import java.util.*;

public class KthParticipant {

	public static void main(String[] args) throws IOException {
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int k=sc.nextInt();
		int a[]=new int[n];
		for(int i=0;i<n;i++) {
			a[i]=sc.nextInt();
		}
		  int temp=a[k-1];int t=0;
		  for(int i=0;i<n;i++) {
				if(a[i]>=temp &&a[i]>0) {
					t++;
				}
			}
		  System.out.println(t);
    }
}
