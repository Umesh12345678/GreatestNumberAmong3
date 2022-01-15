
import java.util.Scanner;
public class GreatestNumberAmong3 {
    public static void main(String s[]){
    Scanner sc=new Scanner(System.in);
		int x = sc.nextInt();
		int y = sc.nextInt();
		int z = sc.nextInt();
		if(x>y && x>z)System.out.println(x+" "+"is greatest");
		if(y>x && y>z)System.out.println(y+" "+"is greatest");
		if(z>y && z>x)System.out.println(z+" "+"is greatest");
    }  
}
