namespace ConsoleApp2
{
    internal class Program
    {
        static void Main(string[] args)
        {
            /* هذا التطبيق يقوم بحساب الجرعات المطلوبه لأخذ حقنه المنجارو بأحجامها الموجوده في الاسواق
وهو صدقةعلي روح كلا من جدي وجدتي 
ادعو الله لهم ان يرحمهم ويدخلهم فسيح جناته 
وان يرحم اموات المسلمين جميعا 
*/
            Console.Write("Hello Ser , Enter Your Name : ");
            string name = Console.ReadLine();
            Console.WriteLine(" ");
            Console.WriteLine("________________________________");
            Console.WriteLine(" ");
            Console.WriteLine("Hello , " + name);
            Console.WriteLine(" ");
            Console.WriteLine("________________________________");
            Console.WriteLine(" ");
            Console.Write("Welcome, please enter what is your injection (5Mg , 7.5Mg , 10Mg , 12.5Mg , 15Mg) : ");
            double injectionT = double.Parse(Console.ReadLine());

            Console.WriteLine(" ");
            Console.WriteLine("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            Console.WriteLine(" ");
            if (injectionT == 5)
            {
                Console.Write("Please enter ( what dose you need to take ? 2.5 Mg / 5 Mg ) : ");
                double dose = double.Parse(Console.ReadLine());
                if (dose == 2.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose + "Mg , You must pull (30) steps ");
                }
                else if (dose == 5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose + "Mg , You must pull (60) steps ");
                }
                else
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine("Your Dose Is UnKnown !!");
                }
            }
            else if (injectionT == 7.5)
            {
                Console.Write("Please enter ( what dose you need to take ? 2.5 Mg / 5 Mg / 7.5 Mg ) : ");
                double dose2 = double.Parse(Console.ReadLine());
                if (dose2 == 2.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose2 + "Mg , You must pull (20) steps ");
                }
                else if (dose2 == 5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose2 + "Mg , You must pull (40) steps ");
                }
                else if (dose2 == 7.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose2 + "Mg , You must pull (60) steps ");
                }
                else
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine("Your Dose Is UnKnown !!");
                }
            }
            else if (injectionT == 10)
            {
                Console.Write("Please enter ( what dose you need to take ? 2.5 Mg / 5 Mg / 7.5 Mg / 10 Mg ) : ");
                double dose3 = double.Parse(Console.ReadLine());
                if (dose3 == 2.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose3 + "Mg , You must pull (15) steps ");
                }
                else if (dose3 == 5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose3 + "Mg , You must pull (30) steps ");
                }
                else if (dose3 == 7.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose3 + "Mg , You must pull (45) steps ");
                }
                else if (dose3 == 10)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose3 + "Mg , You must pull (60) steps ");
                }
                else
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine("Your Dose Is UnKnown !!");
                }
            }
            else if (injectionT == 12.5)
            {
                Console.Write("Please enter ( what dose you need to take ? 2.5 Mg / 5 Mg / 7.5 Mg / 10 Mg / 12.5 Mg ) : ");
                double dose4 = double.Parse(Console.ReadLine());
                if (dose4 == 2.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose4 + "Mg , You must pull (12) steps ");
                }
                else if (dose4 == 5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose4 + "Mg , You must pull (24) steps ");
                }
                else if (dose4 == 7.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose4 + "Mg , You must pull (36) steps ");
                }
                else if (dose4 == 10)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose4 + "Mg , You must pull (45) steps ");
                }
                else if (dose4 == 12.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose4 + "Mg , You must pull (60) steps ");
                }
                else
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine("Your Dose Is UnKnown !!");
                }
            }
            else if (injectionT == 15)
            {
                Console.Write("Please enter ( what dose you need to take ? 2.5 Mg / 5 Mg / 7.5 Mg / 10 Mg / 12.5 Mg / 15 Mg ) : ");
                double dose5 = double.Parse(Console.ReadLine());
                if (dose5 == 2.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (10) steps ");
                }
                else if (dose5 == 5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (20) steps ");
                }
                else if (dose5 == 7.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (30) steps ");
                }
                else if (dose5 == 10)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (40) steps ");
                }
                else if (dose5 == 12.5)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (50) steps ");
                }
                else if (dose5 == 15)
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine(" To Take This Dose " + dose5 + "Mg , You must pull (60) steps ");
                }
                else
                {
                    Console.WriteLine("");
                    Console.WriteLine("=======================================================");
                    Console.WriteLine("");
                    Console.WriteLine("Your Dose Is UnKnown !!");
                }
            }
            else
            {
                Console.WriteLine("");
                Console.WriteLine("=======================================================");
                Console.WriteLine("");
                Console.WriteLine("________________________________");
                Console.WriteLine("The Injection Type Unknown !!");
                Console.WriteLine("________________________________");
            }

            Console.WriteLine("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
            Console.WriteLine(" ");
            Console.WriteLine(" This application is intended to help all sick people calculate the required dose in a Mounjaro injection ");
            Console.WriteLine(" ");
            Console.WriteLine("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        }
    }
}
