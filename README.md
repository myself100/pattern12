# pattern12

import java.util.Scanner;
public class Pattern11 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				if(i%2==0) {
					System.out.print(i);
				}
				else {
					System.out.print((char)(i+64));
				}
			}
			System.out.println();
		}
	}

}

output::                           ////when n is 5
5
A
22
CCC
4444
EEEEE
