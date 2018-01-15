using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            const double Pi = Math.PI;
            double radius = 14.3;

            double answerArea = Pi * radius * radius;
            double answerDiameter = radius * 2;
            double answerCircumference = 2 * Pi * radius;

            Console.WriteLine("Your radius was: " + radius);
            Console.WriteLine(" ");
            Console.WriteLine("The diameter of the circle is: " + answerDiameter);
            Console.WriteLine("The circumference of the circle is: " + answerCircumference);
            Console.WriteLine("The area of the circle is: " + answerArea);
            Console.WriteLine(" ");

        }
    }
}
