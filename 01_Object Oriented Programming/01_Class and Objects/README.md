```java
// Principle of Object-Oriented Programming
/* 
    class v/s object for circle
*/   

class Circle{
    public double redius;
    public double area()
    {
        return Math.PI * redius*redius;
    }
    public double perimeter()
    {
        return 2*Math.PI*redius;
    }
    public double circumfrence()
    {
        return perimeter();
    }
}
public class Main
{
	public static void main(String[] args) {
		Circle c1=new Circle();
		c1.redius=7;
		System.out.println(c1.area());
		System.out.println(c1.circumfrence());
		System.out.println(c1.perimeter());
	}
}

```
 
