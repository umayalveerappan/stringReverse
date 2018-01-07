public static void main(String args[])
{
 String original="";
 String reverse="";
 System.out.println("enter a string");
 Scanner sc=new Scanner(System.in);
 sc.nextline();
 int length=original.length();
 for(int i=len-1;i>=0;i--)
   {
     reverse=reverse+original.charAt(i);
   }
 System.out.println("original string:"+original);
 System.out.println("reverse string:"+reverse);
}
