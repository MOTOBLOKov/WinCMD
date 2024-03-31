//Code Example
//Пример кода

using WinCMD;

namespace Space
{
    class Program
    {
        public static async Task Main()
        {
            Terminal terminal = new Terminal();
            terminal.ConsoleOutPut += Cacneliii;
            terminal.InputComand("ping 8.8.8.8");

            await Task.Delay(6000);
        }
        public static void Cacneliii(string str)
        {
            Console.WriteLine(str);
        }
    }
}