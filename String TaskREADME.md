# Session2
import java.io.*;
import java.util.*;

public class QueryBased {

	public static void main(String[] args) throws IOException {
		BufferedReader sc=new BufferedReader(new InputStreamReader(System.in));
		 
		 
		  int t=Integer.parseInt(sc.readLine().trim());
		  while(t-->0) {
			  String s=sc.readLine();
			  if(s.length()<=10) {
				  System.out.println(s);
			  }
			  else {
				  System.out.print(s.charAt(0));
				  System.out.print(s.length()-2);
				  System.out.print(s.charAt(s.length()-1));
			  }
			  System.out.println();
		  }
    }
}
