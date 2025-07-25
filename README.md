# Print-the-weak-days
import java.util.Scanner;
class main
{
Public Static void main(String args[])
{
Scanner sc=new Scanner("System.in");
System.out.print("Enter the weak day number:");
int n=sc.nextInt();
Switch(n)
{
case1:
System.out.print("Monday");
break;
case2:
System.out.print("Tuesday");
break;
case3:
System.out.print("Wednessday");
break;
case4:
System.out.print("Thursday");
break;
case5:
System.out.print("Friday");
break;
case6:
System.out.print("Saturday");
break:
case7:
System.out.print("Sunday");
break;
default:
System.out.print("Invalid weakday number");
}
}
}
