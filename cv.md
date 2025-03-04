# **Shumeiko Gleb**
# **CV**

* Personal information  
* Code example  
* Contact information

## Personal Information
### About me
Student of the Belarusian-Russian University of Engineering and Economics Faculty.  
Group: PIR-231  
Goals and priorities: Wishing to complete higher education and learn new things in the IT field to realize my strengths and acquire a decent job.  
Skills: Beginner programming skills in C#, lacking job experience.  
English language level: up to B2.

## Code Example
```
static void Main(string[] args)
{
    int choice;
    bool exit = false;
    while (!exit)
    {
        Console.Clear();
        Console.WriteLine("Выберите игру: \n1) Крестики-нолики \n2) Угадай число \n3) Выйти из программы");
        ChoiceInput(out choice);
        switch (choice)
        {
            case 1:
                Console.WriteLine("Игра \"Крестики-нолики\"");
                Console.WriteLine("Задача: закрашивая поле крестиками/ноликами, заполнить ряд из 3 клеток");
                PressToContinue();
                TicTacToeGame();
                break;
            case 2:
                Console.WriteLine("Игра \"Угадай число\"");
                Console.WriteLine("Задача: угадать число заданное компьютером");
                PressToContinue();
                DigitsGame();
                break;
            case 3:
                exit = true;
                break;
            default:
                Console.WriteLine("Некорректный ввод, попробуйте снова\n");
                PressToContinue();
                break;
        }
    }
}
```
## Contacts
Phone Telegram VK Gmail
