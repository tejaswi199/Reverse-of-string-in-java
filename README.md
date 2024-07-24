# Reverse-of-string-in-java
public class Main{
    public static void main(String[] args){
       String s="Hello, World!.";
       System.out.println("String:"+s);
       int last=s.length()-1;
       String rev="";
       for(int i=0;i< s.length();i++){
           rev=rev+s.charAt(last);
           last--;
       }
       System.out.println("Reversed string:"+rev);
       
  }
}
