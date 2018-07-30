# Method_overloading1
class Test7
{
   void disp(int a,int b)
  {
  int x=a;
  int y=b;
  int z=x+y;
System.out.println("Sum is :"+z);
}
   void disp(int a,float b)
{
  int x=a;
  float y=b;
  float z=x*y;
System.out.println("Multiplication is:"+z);
}
public static void main(String args[])
{
  Test7 obj=new Test7();
  obj.disp(45,55);
  obj.disp(5,4.5f);
}
}
     
