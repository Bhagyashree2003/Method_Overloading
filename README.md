# Method_Overloading
java Method Overloading

class methodoverloading

{

	static void fool()
  
	{
  
		System.out.println("Good morning.bro!");
    
	}
  
	static void fool(int a)
  
	{
  
		System.out.println("Good morning "+a+ " bro!");
    
	}
  
	static void fool(int a,int b)
  
	{
  
		System.out.println("Good morning "+a+ " bro!");
    
		System.out.println("Good morning "+b+ " bro!");
    
	}
  
	static void change(int a)
  
	{	
  
		a=98;
    
	}
  
	static void change2(int []arr)
  
	{	
  
		arr[0] = 98;
    
	}
  
	static void jokes()
  
	{
  
		System.out.println("i'm joking:\n "+"miss");
    
	}
	
  
	public static void main(String args[])
  
	{

		System.out.println("\n Methodover loading");
    
		fool();
    
		fool(2500);
    
		fool(410,450);
    
	}
  
}
