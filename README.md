import java.util.*;
class assignment24
{
public static void main(String args[])
{
System.out.println("Enter 3 numbers");
Scanner obj=new Scanner(System.in);
int a=obj.nextInt();
int b=obj.nextInt();
int c=obj.nextInt();
int d=a>b?(a>c?a:c):(b>c?b:c);
System.out.println("The highest among the 3 numbers you have entered is "+d);

}
}
