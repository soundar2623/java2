# java2
}
public class B extends ex2{
public void input()
{
	int i=0;
	for(i=0;i<3;i++)
	{
	System.out.println("customer "+(i+1)+":");
	System.out.println("person name:\n");
	String name=s.next();
	System.out.println("person address:\n");
	String name1=s.next();
	System.out.println("person age:\n");
	int age=s.nextInt();
	System.out.println("person number:\n");
	int number=s.nextInt();
	}
}
	public void details(String name,String name1,int age,int number)
	{
	System.out .println("person details:\n");
	System.out.println(name);
	System.out.println(name1);
	System.out.println(age);
	System.out.println(number);
	System.out.println(id)
	
	if(id1<1){
	

	}
	}
	
		
	
	
package excercise2;
import java.util.*;
class a{
	Scanner sc = new Scanner(System.in);
	int id;
	String name,telphno,add;
	void person1() {
		System.out.println("enter id:");
		id = sc.nextInt();
		sc.nextLine();
		System.out.println("enter telephone no.:");
		telphno = sc.nextLine();
		System.out.println("enter address:");
		add = " ";
		add = sc.nextLine();
		}
	void show() {
		System.out.println("Id:" +id);
		System.out.println("Telephone no.:" +telphno);
		System.out.println("Address:" +add);
	}
}

public class ex21 {
	public static void main(String args[]) {
		Scanner c=new Scanner(System.in);
		a p1 = new a();
		System.out.println("Enter your choice:");
		int ch = c.nextInt();
		String name;
		switch(ch) {
		case 1:
			name="John";
			System.out.println("enter name:\n"+name);
			p1.person1();
			System.out.println("Name:" +name);
			p1.show();
			break;
		case 2:
		    name="Ally";
			System.out.println("enter name:\n"+name);
			p1.person1();
			System.out.println("Name:" +name);
			p1.show();
			break;
		case 3:
			name="roy";
			System.out.println("enter name:\n"+name);
			p1.person1();
			System.out.println("Name:" +name);
			p1.show();
			break;
		default:
			System.out.println("invalid choice");
				
		}
		c.close();
	}
}		

