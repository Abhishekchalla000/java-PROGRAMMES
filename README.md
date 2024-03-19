package Abhi;
public class Student 
{
      int id;
      String name;
      int phno;
      public Student(int id, String name, int phno) {
    	  this.id=id;
    	  this.name=name;
    	  this.phno=phno;
      }

public void info() {
	System.out.println("Student ID:" + id);
	System.out.println("Student name:" + name);
	System.out.println("Student phno:" + phno);
	System.out.println();
	
}
public static void main(String[]args) {
	Student Student1=new Student(101,"Abhi",123456789);
	Student Student2=new Student(102,"palak",987654321);
	
	Student1.info();
	Student2.info();
}
}
