# Sum-of-digits-of-given-num
package javabasics;

public class Sum {

	public static void main(String[] args) {
		int n=235;
		int r,sum=0;
		while(n>0)
		{
			r=n%10;
			n=n/10;
			sum=sum+r;
		}
	//	System.out.println("2+3+5="+sum);
		
			
		int R=sum%10;
		sum=sum/10;
		int ans=sum+R;
		System.out.println( ans);
	}}


