# JAVA-PROJECT
//Write a java prog for employee using OOPs Concepts
abstract class Employee  //ABSTRACT CLASS
{
abstract void details();
}
class Account extends Employee  //INHERITANCE
{
double id;
long jd;
long mn;
float bal;
String name,eid,bname;
private int acno;  //DATA ENCAPSULATION
private int pin;
void details()
{
acno=11;
name="James Gosling";
bal=69.23f;
pin=1234;
bname="SBI";
id=0768d;
mn=9397402744l;
eid="james@gmail.com";

System.out.println("-----------------");
System.out.println("Employee Details");
System.out.println("-----------------");
System.out.println("Account Number="+acno);
System.out.println("Account Holder Name="+name);
System.out.println("Account Balance="+bal);
System.out.println("Password="+pin);
System.out.println("Branch Name="+bname);
System.out.println("Identity Number="+id);
System.out.println("Mobile Number="+mn);
System.out.println("Email id="+eid);
}
}
class EmployeeDemo
{
public static void main(String [] args) 
{
Employee ee=new Account(); //POLYMORPHISM
   ee.details();
}
}
