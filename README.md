# simple5
import java.util.Scanner;
public class simple5 {
    public static void main(String args[])
    {
        int i,j,n=6;
        for(i=0;i<n;i++)
        {
            for(j=2*(n-i);j>=0;j--)
            {
                System.out.print(" ");
                
            }
            for(j=0;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }            
            }
