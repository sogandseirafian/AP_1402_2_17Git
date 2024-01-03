# AP_1402_2_17Git
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp13
{
    internal class Program
    {
        static void Main(string[] args)
        { 
            //soal dar jozve.
            int x = Convert.ToInt32(Console.ReadLine());
            int y = Convert.ToInt32(Console.ReadLine());
            Double Result = Math.Sqrt(Math.Pow(Math.Abs(x-y),Math.Abs(y))) ;
            Console.WriteLine(Result);
            Console.ReadKey();  //mesle return dar C++ mimome.


        }
    }
}
