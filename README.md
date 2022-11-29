# Inheritance
## Aim:
To write a C# program to print some messages using hierarchical inheritance
## Algorithm:
### step 1:
Create a base class.
### step 2:
Create two child class.
### step 3:
Create a constructor in the base class and print a message.
### step 4:
create a function in child class to print a message.

## Program:
```c#
using System;
namespace abc
{
    class Tyre
    {
        public Tyre()
        {
            Console.Write("Tyre has been inserted ");
        }
    }
    class Scooter : Tyre
    {
        public void display()
        {
            Console.Write("For the scooter ");
        }
    }
    class Car : Tyre
    {
        public void display()
        {
            Console.Write("For the car ");
        }
    }
    public class yz
    {
        public static void Main(string[] args)
        {
            Scooter s1 = new Scooter();
            s1.display();
            Console.WriteLine();
            Car c1 = new Car();
            c1.display();
        }
    }
}
```
## Output:
![2022-06-09 (4)](https://user-images.githubusercontent.com/75235477/172840718-0375788c-7dc5-472a-9c2e-2fa65eebb9af.png)

## Result
Thus C# program to print some messages using hierarchical inheritance is written and executed sucessfully.
