# square_peremeter-and-it-surface-area
square, perimeter and its surface are


Develop a program that has a class that represents a Square and has the following methods: enter value at its side,
print its perimeter and its surface. Use the next libraries: System; System.Collections.Generic; System.Linq;
System.Text;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace Square
{
class Square
{
double side, perimeter, surface_area;
public Square()
{
this.side = 0.0;
this.perimeter = 0.0;
this.surface_area = 0.0;
}
public void Enter_Value_at_its_Side()
{
Console.WriteLine("Enter the length of side in units: ");
this.side = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("\nThe Length of side of Square = {0} units", side);
}

7

public void Print_its_Perimeter()
{
this.perimeter = 4 * this.side;
Console.WriteLine("\nThe Perimeter of Square = {0} units", perimeter);
}
public void Print_its_Surface()
{
this.surface_area = this.side * this.side;
Console.WriteLine("\nThe Area of Square = {0} units.square", surface_area);
}
static void Main(string[] args)
{
Square s1 = new Square();
s1.Enter_Value_at_its_Side();
s1.Print_its_Perimeter();
s1.Print_its_Surface();
Console.WriteLine('\n');
}
}
}

Targets understanding of csharp classes and programming
