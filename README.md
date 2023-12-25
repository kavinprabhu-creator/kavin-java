# kavin-java
java program
class Mobile02 {
String brand; 
int price;

Mobile02(int price , String brand ){
this.price=price;
this.brand=brand;
}
public static void main(String[]args)
{
Mobile1 m1=new Mobile1(50000,"samsong");
System.out.println(m1.brand+"  "+m1.price);

Mobile1 m2=new Mobile1(125000,"iphone");
System.out.println(m2.brand+"  "+m2.price);
}
}
