using System;

namespace section2
{
    class Program
    {
        static void Main(string[] args)
        {
            person p1 = new person();
            person p2 = new person();
            person spouse1 = new person();
            person spouse2 = new person();

            System.Console.Write("First Name P1?");
            p1.Firstname = System.Console.ReadLine();

            System.Console.Write("Last Name?");
            p1.lastname = System.Console.ReadLine();

            System.Console.Write(" Age?");
            p1.Age = int.Parse(System.Console.ReadLine());

            person.sumofallages = person.sumofallages + p1.Age;

            System.Console.Write("First Name spouse1?");
            spouse1.Firstname = System.Console.ReadLine();

            System.Console.Write(" Age?");
            spouse1.Age = int.Parse(System.Console.ReadLine());

            person.sumofallages = person.sumofallages + spouse1.Age;

            System.Console.Write("First Name P2?");
            p2.Firstname = System.Console.ReadLine();

            System.Console.Write("Last Name?");
            p2.lastname = System.Console.ReadLine();

            System.Console.Write(" Age?");
            p2.Age = int.Parse(System.Console.ReadLine());

            person.sumofallages = person.sumofallages + p2.Age;

            System.Console.Write("First Name spouse1?");
            spouse2.Firstname = System.Console.ReadLine();

            System.Console.Write(" Age?");
            spouse2.Age = int.Parse(System.Console.ReadLine());

            person.sumofallages = person.sumofallages + spouse2.Age;

            spouse1.lastname = p1.lastname;

            spouse2.lastname = p2.lastname;

            p1.Printnameandage();
            p2.Printnameandage();
            spouse1.Printnameandage();
            spouse2.Printnameandage();

            System.Console.Write("Average age: " + person.sumofallages / 4); 



        }
    }
}
