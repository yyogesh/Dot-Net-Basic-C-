# Dot-Net-Basic-C-
Day 1

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace DataTypes
{
    class Program
    {
        static void Main(string[] args)
        {
            //1. 
            // Prompt the user for his name
            Console.WriteLine("Please enter your name");
            // Read the name from console
            string UserName = Console.ReadLine();
            // Concatenate name with hello word and print
            Console.WriteLine("Hello " + UserName);

           
            //Placeholder syntax to print name with hello word 
            //Console.WriteLine("Hello {0}", UserName);

            //***************************************************************
            //2. 

            bool b = true;
            //b = 123;

            //Error because b is boolean type data type it can not 
            //hold interger type of any other type. 

            // But in C and C++ 0 means false other then 0 means true 

            //***************************************************************
            //3 

            int i = 0;
            Console.Write("Min = {0}", int.MinValue);
            Console.Write("Max = {0}", int.MaxValue);
            Console.WriteLine("Size of int: {0}", sizeof(int)); // get size or memory 4 

            //***************************************************************
            //4

            double d = 123.12112;
            Console.Write(d); // It will show 123.12112 



            //***************************************************************
            //5
            string Name = "Yogesh Yadav";
            //string Name = "" Yogesh Yadav";  // double quotes has special meaning means start or string and end of string
            Console.Write(Name);
           //  Name = "\" Yogesh Yadav \""; // to write double quotes in string use back slash
            // Console.Write(Name);

            //***************************************************************
            //6
            Console.WriteLine(@"C:\Yogesh\DotNet\Training\Csharp"); 
            Console.Read();
          
        }
    }
}
