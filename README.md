# Li-o-de-String

using System;

namespace Cebolinha
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("escreva algo: ");
            string texto = Console.ReadLine();

            string novotexto = texto.Replace("l", "r"). Replace("L", "R");
            Console.WriteLine(novotexto);
        }
    }
}

using System;

namespace CriancaEducada
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Xinga-me: ");
            string texto = Console.ReadLine();

            string novotexto = texto.Replace("boba", "#@$%*!&").Replace("bobo", "#@$%*!&").Replace("pentelho", "3").Replace("pentelha", "3").Replace("chata", "#@$%*!&").Replace("chato", "#@$%*!&").Replace("feio", "#@$%*!&").Replace("feia", "#@$%*!&").Replace("boboca", "#@$%*!&").Replace("bocó", "#@$%*!&").Replace("tonto", "#@$%*!&").Replace("tonta", "#@$%*!&").Replace("palherma", "#@$%*!&").Replace("paspalho", "#@$%*!&").Replace("paspalha", "#@$%*!&").Replace("tantã", "#@$%*!&").Replace("panaca", "#@$%*!&").Replace("burro", "#@$%*!&").Replace("burra", "#@$%*!&").Replace("besta", "#@$%*!&");
            Console.WriteLine(novotexto);

        }
    }
}


using System;

namespace Gritador
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Se expresse: ");
            string texto = Console.ReadLine();
            Console.Write(texto. ToUpper());
            Console.ReadKey();
            
        }
    }
}


using System;

namespace Leet
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("escreva algo: ");
            string texto = Console.ReadLine();

            string novotexto = texto.Replace("A", "4").Replace("a", "4").Replace("E", "3").Replace("e", "3").Replace("o", "0").Replace("O", "0").Replace("L", "1").Replace("l", "1").Replace("i", "1").Replace("I", "1").Replace("T", "7").Replace("t", "7").Replace("S", "5").Replace("s", "5");
            Console.WriteLine(novotexto);

        }
    }
}


using System;

namespace memetonervoso
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("O que voce pensa de mim? ");
            string texto = Console.ReadLine();
            Console.WriteLine("- E sabe o que eu penso de você?");
            Console.WriteLine("Você é mui... NÃO, PERA.");
            Console.Write("Tô nervoso");
            Console.ReadKey();
        }
    }
}


using System;

namespace NomeCompleto
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Digite seu primeiro nome: ");
            String texto1 = Console.ReadLine();

            Console.Write("Digite seu sobrenome: ");
            string texto2 = Console.ReadLine();
            Console.Write("Nome Completo: ");
            Console.Write(texto1 + " " + texto2);
            Console.ReadKey();

            Console.Write("Nome de Catalogo: ");
            Console.Write(texto2.ToUpper() + " " + texto1);
            Console.ReadKey();

            
            
        }
    }
}

using System;

namespace OlaUsuario
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Digite seu nome: ");
            string textoDigitado = Console.ReadLine();
            Console.Write("Olá, ");
            Console.Write(textoDigitado);
            Console.ReadKey();
        }
    }
}
