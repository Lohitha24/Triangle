 import java.util.Scanner;
//To check whether the triangle is equilateral, isosceles or scalene.
public class TriangleType
{
 public static void main(String[] args)
{
System.out.println("Hello World");
Scanner sc= new Scanner(System.in);
int side_a= sc.nextInt();
int side_b= sc.nextInt();
int side_c= sc.nextInt();
if(side_a==side_b && side_b==side_c) System.out.println("Equilateral Triangle" );
if(side_a==side_b || side_b==side_c || side_a==side_c) System.out.println("Isoceles Triangle");
if(side_a!=side_b && side_b !=side_c && side_a!=side_c) System.out.println("Scalene Triangle");
}
}
