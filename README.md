# Projekt-FizzBuzz
This is an app to show numbers from 1-100.

Console.WriteLine("Jag skriver ut alla tal från 1 till 100");


    for (int i = 1; i <= 100; i++)
{
    if (i % 3 == 0 && i % 5 == 0)
    {
        Console.WriteLine("FizzBuzz");
    }
    else if (i % 3 == 0)
    {
        Console.WriteLine("Fizz");
    }
    else if (i % 5 == 0)
    {
        Console.WriteLine("Buzz");
    }
    else
    {
        Console.WriteLine(i);
    }
}
    
    
    Console.WriteLine("Tryck på valfri tangent för att avsluta...");
