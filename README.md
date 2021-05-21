interface A
{
	default void display();
}
class C implements A
{
	void display()
	{
		System.out.println("Im from A as well as B");
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 C c = new C();
			 c.display();
		
	}
}

