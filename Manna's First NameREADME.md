# Session2
import java.util.Scanner;
import java.util.regex.Matcher;
import java.util.regex.Pattern;

public class dsjagfdksjgflds {
     public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();sc.nextLine();
		while(t-->0) {
			String s=sc.next();int s1=0,s2=0;
			Pattern p=Pattern.compile("SUVOJIT");
			Matcher m=p.matcher(s);
			while(m.find()) {
				s2++;
			}
			Pattern p1=Pattern.compile("SUVO");
			Matcher m1=p1.matcher(s);
			while(m1.find()) {
				s1++;
			}
			System.out.println("SUVO = "+(s1-s2)+", SUVOJIT = "+(s2));
		}
	}
}
