    XXstatic void Main()
    {
        // Потребовать ввод от пользователя
        Console.Write("Введите ваше имя: ");
        
        // Считать введенное имя с консоли
        string userName = Console.ReadLine();
        
        // Вывести приветствие на консоль
        Console.WriteLine($"Hello {userName}!");

        // Ждать, пока пользователь нажмет клавишу перед выходом
        Console.ReadLine();
    }