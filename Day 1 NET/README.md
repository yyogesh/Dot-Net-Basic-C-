using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace CSharpOperator
{
    class Program
    {
        static void Main(string[] args)
        {
            int Number = 10;
            bool IsNumber10;

            if (Number == 10)
            {
                IsNumber10 = true;
            }
            else
            {
                IsNumber10 = false;
            }

            Console.WriteLine("i == 10 is {0}", IsNumber10);

            //*************************************************
            //2

            //bool IsNumber10 = Number == 10 ? true : false;
            //Console.WriteLine("i == 10 is {0}", IsNumber10);


            //*************************************************
            //3 Program without using NULL coalescing operator


            //int AvailableTickets;
            //int? TicketsOnSale = null;

            //if (TicketsOnSale == null)
            //{
            //    AvailableTickets = 0;
            //}
            //else
            //{
            //    AvailableTickets = (int)TicketsOnSale;
            //    //AvailableTickets = TicketsOnSale.Value;
            //}

            //Console.WriteLine("Available Tickets={0}", AvailableTickets);

            //*************************************************
            //4 Program without using NULL coalescing operator


            //int AvailableTickets;
            //int? TicketsOnSale = null;

            ////Using null coalesce operator ??
            //AvailableTickets = TicketsOnSale ?? 0;

            //Console.WriteLine("Available Tickets={0}", AvailableTickets);

            Console.Read();
        }
    }
}
