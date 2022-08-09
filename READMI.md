// Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.
Console.Write("Введите число a: ");
string input_a = Console.ReadLine();
int a = Convert.ToInt32(input_a );    
Console.Write("Введите число b: ");
string input_b = Console.ReadLine();
int b = Convert.ToInt32(input_b);      
if  (a > b)
{
Console.WriteLine( " max=  " +a);
}
else
{
  Console.WriteLine( " max=  " +b); 
}