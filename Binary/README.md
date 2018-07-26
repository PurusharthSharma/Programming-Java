import java.util.Scanner;
public class bina {
	
	public static void main(String args[]){
		int num,i,qu,re,binary;
		
		Scanner sys = new Scanner (System.in);
		
		System.out.print("Enter Any Number to be Converted into its Equivalent Binary :");
		num = sys.nextInt();
		
		System.out.print("Equivalent binary to the input Number is : ");
		
		while(num!=0){
			for(i=0;i<num;i++){
				qu = num%2;
				re = num/2;
				binary = qu;
					System.out.print(binary);
				num = re;
				
			}
		}
	}

}
