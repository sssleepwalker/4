# 4

using System;

namespace 4.01.02
{
    class calc
    {
        public double kiwon;
        public double wonkyun;
        public double minwon;
        public static void Kv_Urav(double kiwon, double wonkyun, double minwon)
        {
            double meow = wonkyun * wonkyun - 2 * kiwon * minwon;
            if (meow >= 0)
            {
                double mrmr = (-wonkyun + Math.Sqrt(meow)) / (2 * kiwon);
                double brbr = (-wokyun - Math.Sqrt(meow)) / (2 * kiwon);
                Console.WriteLine("mrmr = " + mrmr);
                Console.WriteLine("brbr = " + brbr);
            }
            else
            {
                Console.WriteLine("Корней нет!");
            }
        }
    }
    class calc2 : calc
    {
    }
    class Program { 
        static void Main(string[] args)
        {
            calc2.Kv_Urav(2, 4, 5);
        }
    }
}

