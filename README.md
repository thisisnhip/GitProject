# GitProject
using System;
namespace tamgiac
{
    class Chuvi
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Nhap 3 canh tam giac:");
            double a = Convert.ToDouble(Console.ReadLine());
            double b = Convert.ToDouble(Console.ReadLine());
            double c = Convert.ToDouble(Console.ReadLine());
            double Chuvi = a+b+c;
            Console.WriteLine("Chu vi tam giac:" + Chuvi);
        }
    }
}
