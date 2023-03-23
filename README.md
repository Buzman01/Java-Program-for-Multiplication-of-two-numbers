# Java-Program-for-Multiplication-of-two-numbers
import java.io.*;
import java.lang.*;
class Mul
{
    public static void main(String args[])throws IOException
    {
        int n1=0,n2;
        BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
        System.out.println("Enter first number ");
        n1=Integer.parseInt(br.readLine());
        System.out.println("Enter second number ");
        n2=Integer.parseInt(br.readLine());
        n1*=n2; // or n1=n1*n2
        System.out.println("Multiplication of two numbers is: "+n1);
    }
}
