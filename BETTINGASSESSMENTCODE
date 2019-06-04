using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace BETTINGASSESSMENT
{
    public abstract class basebasket
    {
        public string Name { get; set; }
        public string size { get; set; }

        public abstract void display1();

    }
    class tshirt : basebasket
    {
        public override void display1()
        {

            Console.WriteLine("---Tshirt class---");
            Console.WriteLine($"Type of Shirt: {Name}");
            Console.WriteLine($"Shirt Size:  {size}");
            int s = 10, m = 20, l = 30;
            if (size == "m" && Name == "tshirt")
            {
                int a = m;
                Console.WriteLine("Total price for medium shirt: R" + a + "\n");
                return;

            }
            else
            if (size == "s" && Name == "tshirt")
            {
                int b = s;
                Console.WriteLine("Total price for small shirt: R" + b + "\n");
                return;
            }
            else
                if (size == "l" && Name == "tshirt")
            {
                int c = l;

                Console.WriteLine("Total price for large shirt: R" + c + "\n");
                return;
            }
        }

    }
    class golfers : tshirt
    {
        public override void display1()
        {
            int s = 10 * 2, m = 20 * 2, l = 30 * 2;
            Console.WriteLine("---Golfer class---");
            Console.WriteLine($"Type of shirt: {Name}");
            Console.WriteLine($"Size of shirt: {size}");
            if (size == "m" && Name == "golfer")
            {

                int a = m;
                Console.WriteLine("Total price for  medium golfer shirt: R" + a + "\n");
            }
            else
            if (size == "s" && Name == "golfer")
            {
                int b = s;
                Console.WriteLine("Total price for small golfer shirt: R" + b + "\n");

            }
            else
                if (size == "l" && Name == "golfer")
            {
                int c = l;

                Console.WriteLine("Total price for large golfer shirt: R" + c + "\n");

            }

        }
    }

    class Jeans : golfers
    {
        public override void display1()
        {
            int s = 10, m = 20, l = 30;
            Console.WriteLine("---Jeans class---");
            Console.WriteLine($"Type of Pants: {Name}");
            Console.WriteLine($"Type of size: {size}");
            if (size == "m" && Name == "jeans")
            {

                int a = m;
                Console.WriteLine("Total price for medium jeans: R" + a);
            }
            else
            if (size == "s" && Name == "jeans")
            {
                int b = s;
                Console.WriteLine("Total price for small jeans: R" + b + "\n");

            }
            else
                if (size == "l" && Name == "jeans")
            {
                int c = l;

                Console.WriteLine("Total price for large jeans: R" + c + "\n");

            }

        }
    }

    class formalpants : Jeans
    {
        public override void display1()
        {
            int s = 10 + 30, m = 20 + 30, l = 30 + 30;
            Console.WriteLine("---Formal Pants class---");
            Console.WriteLine($"Type of Pant: {Name}");
            Console.WriteLine($"Size: {size}");
            if (size == "m" && Name == "formal pants")
            {

                int a = m;
                Console.WriteLine("Total price for medium formal pants: " + a + "\n");

            }
            else
            if (size == "s" && Name == "formal pants")
            {
                int b = s;
                Console.WriteLine("Total price for small formal pants: R" + b + "\n");

            }
            else
                if (size == "l" && Name == "formal pants")
            {
                int c = l;

                Console.WriteLine("Total price for large formal pants: R" + c + "\n");

            }

        }
    }
    class Basket : formalpants
    {
        public override void display1()
        {
            //    var tshirt = new tshirt();
            //    int s = 10, m = 20, l = 30;
            //    if (size == "m" && Name == "tshirt")
            //    {
            //        int a = m;
            //        Console.WriteLine("Total price for medium shirt: R" + a + "\n");
            //        return;

            //    }
            //    else
            //    if (size == "s" && Name == "tshirt")
            //    {
            //        int b = s;
            //        Console.WriteLine("Total price for small shirt: R" + b + "\n");
            //        return;
            //    }
            //    else
            //        if (size == "l" && Name == "tshirt")
            //    {
            //        int c = l;

            //        Console.WriteLine("Total price for large shirt: R" + c + "\n");
            //        return;
            //    }

            //}

            //static void cal()
            //           {
            //           var tshirt = new tshirt();
            //           tshirt.display1();
            //           }

        }
        class Program
        {
            static void Main(string[] args)
            {
                var baskset = new Basket();
                var tshirt = new tshirt();
                var golfers = new golfers();
                var jeans = new Jeans();
                var formalpants = new formalpants();

                tshirt.Name = "tshirt";
                tshirt.size = "l";
                tshirt.display1();

                golfers.Name = "golfer";
                golfers.size = "s";
                golfers.display1();

                jeans.Name = "jeans";
                jeans.size = "s";
                jeans.display1();

                formalpants.Name = "formal pants";
                formalpants.size = "l";
                formalpants.display1();


                // baskset.display1();

                //   Console.WriteLine($"Your total price is:{baskset.display1()}");

                Console.ReadLine();
            }
        }
    }
}

