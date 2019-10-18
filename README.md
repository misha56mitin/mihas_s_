using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp11
{
    class Program
    {
        static void Main(string[] args)
        {
            for (double x = 1, xKon = 25, h = 0.5; x <= xKon; x += h)
                double y = Math.Tan(2 * x + 1);
            Console.WriteLine("x={0:0.#}\ty={1:0.###}", x, 
                y);

        }
    }
}
