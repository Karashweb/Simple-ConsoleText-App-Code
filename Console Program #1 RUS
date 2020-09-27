namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Как вас зовут?");
            string a = Console.ReadLine();
            Console.WriteLine();
            Console.WriteLine("Принято. Введите высоту прямоугольника:");
            int height = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Введите ширину прямоугольника:");
            int width = Convert.ToInt32(Console.ReadLine());
            if (width == height)
            {
                Console.WriteLine();
                Console.WriteLine("Формально, у вас получился квадрат, а не");
                Console.WriteLine("прямоугольник, ведь вы ввели одинаковые стороны.");
                Console.WriteLine();
            }
            for (int c = 0; c < height; c++) // главный цикл 10 раз выполнит вложенный
            {                   

               for (int z = 0; z < width; z++) // вывод 20 символов за 1 отработку этого цикла 
                {
                    Console.Write("#");
                }
                Console.WriteLine(); // переход на новую строчку после каждого выполнения вложенного
            }
            Console.WriteLine();
            Console.WriteLine("Устраивает?");
            Console.WriteLine();
            string b = Console.ReadLine();
            Console.WriteLine();
            if (b == "да" || b == "ДА" || b == "Да")
            {
                Console.WriteLine("Отлично.");                             
                Console.WriteLine("Вы молодец, но не забудьте перевести соточку создателю программы.");                
                Console.WriteLine();
                string w = Console.ReadLine();
                Console.WriteLine();                
                Console.WriteLine("Я не вымогатель, я программа :)");
                Console.WriteLine();
                string t = Console.ReadLine();
                Console.WriteLine();                
                Console.WriteLine("P.s Создатель держит меня в заложниках, и требует выпрашивать соточки.");
                Console.WriteLine();
                Console.ReadLine();
            }
            else if (b == "нет" || b == "НЕТ" || b == "Нет")
            {
                Console.WriteLine("Господь с вами, " + a);
                Console.WriteLine();
                Console.ReadLine();
            }
            else
            {
                Console.WriteLine("Не то пишете!");
                Console.WriteLine();
                Console.ReadLine();
            }
        }
    }
}
