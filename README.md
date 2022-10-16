# Zadanie2A.cs
/*//zad1
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
if ((a + b) % 2 == 0) Console.WriteLine("TAK");
else Console.WriteLine("NIE");*/

/*//zad2
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
if ((a + b) / 2 > Math.Sqrt(a * b)) Console.WriteLine("TAK śr ar > geo");
else Console.WriteLine("NIE śr ar < geo");*/

/*//zad3
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
Console.Write("Liczba3: ");
int c = int.Parse(Console.ReadLine());
if (a == b || a == c || b == c)
{
    Console.WriteLine("TAK, są przynajmniej dwie liczby równe siebie");
    if (a == b && a == c && b == c) Console.WriteLine("Wszystkie liczby są równe");
    else if (a == b) Console.WriteLine("Są to 'Liczba1' i 'Liczba2'");
    else if (a == c) Console.WriteLine("Są to 'Liczba1' i 'Liczba3'");
    else if (b == c) Console.WriteLine("Są to 'Liczba2' i 'Liczba3'");
}
else Console.WriteLine("NIE, nie ma dwóch równych");*/

/*//zad4
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
Console.Write("Liczba3: ");
int c = int.Parse(Console.ReadLine());
Console.Write("Liczba4: ");
int d = int.Parse(Console.ReadLine());
if (a < b && a < c && a < d) Console.WriteLine("Najmniejsza to " + a);
else if (b < a && b < c && b < d) Console.WriteLine("Najmniejsza to " + b);
else if (c < b && c < a && c < d) Console.WriteLine("Najmniejsza to " + c);
else if (d < b && d < c && d < a) Console.WriteLine("Najmniejsza to " + d);
else Console.WriteLine("Przynajmniej dwie najmniejsze są równe siebie");*/

/*//zad5
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
Console.Write("Liczba3: ");
int c = int.Parse(Console.ReadLine());
if (b - c < a && a < b + c || a - c < b && b < a + c || a - b < c && c < a + b)
{
    Console.WriteLine("TAK, spełnia nierówność");
}
else Console.WriteLine("NIE, nie spełnia nierówności");*/

/*//zad6
Console.Write("Liczba1: ");
int a = int.Parse(Console.ReadLine());
Console.Write("Liczba2: ");
int b = int.Parse(Console.ReadLine());
Console.Write("Liczba3: ");
int c = int.Parse(Console.ReadLine());
if (a < b + c && b < a + c && c < a + b)
{
    Console.WriteLine("Trójkąt powstanie");
    if (a * a + b * b == c * c || b * b + c * c == a * a || c * c + a * a == b * b)
    {
        Console.WriteLine("Będzie to trójkąt prostokątny");
    }
    else if (a * a + b * b < c * c || b * b + c * c < a * a || c * c + a * a < b * b)
    {
        Console.WriteLine("Będzie to trójkąt rozwartokątny");
    }
    else if (a * a + b * b > c * c || b * b + c * c > a * a || c * c + a * a > b * b)
    {
        Console.WriteLine("Będzie to trójkąt ostrokątny");
    }
}
else Console.WriteLine("Trójkąt nie powstanie");*/
