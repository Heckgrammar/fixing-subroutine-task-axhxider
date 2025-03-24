using System;
					
public class Program
{
	public static void Main(string[] args)
	{
		for (int i = 7; i >= 0; i--)
		{
			Console.WriteLine(differentCurrencies(i));
		}
	}
	
	static string differentCurrencies(int x)
	{
	string[] currencies = {"baht" , "dollar" , "euro" , "koruna" , "lira" , "rand", "rupee" , "yen" };
		if (x >= 0 && x < currencies.Length)
		{	
			return currencies[x];	
		}
		else
		{
			return "invalid index";
		}
	}
	
	
}
