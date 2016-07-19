# VowelOrConsonant
import java.util.Scanner;

public class VowelOrConsonant {
	public static void main(String []arg)
	{
		Scanner get=new Scanner(System.in);
		char input=get.next().charAt(0);
		if(input=='a' || input=='e' || input=='i' || input=='o'|| input=='u' ||input=='A' || input=='E'|| input=='I'|| input=='O'|| input=='U'){
			System.out.println("the character is vowel");
		}
		else
		{
			System.out.println("the character is consonant");
		}
	}

}
