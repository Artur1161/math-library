# math-library
MyLibrary — простая математическая библиотека на C#

Небольшая библиотека классов для базовых математических операций, созданная в Visual Studio 2022 на C#.



MyLibrary — библиотека с математическими классами

ConsoleApp1 — консольное приложение для тестирования

реализовано:
сложение

вычитание

умножение

деление (с проверкой деления на ноль)

как юзать
using MyLibrary;

BasicMath math = new BasicMath();

Console.WriteLine(math.Add(5, 3));
Console.WriteLine(math.Multiply(4, 2));

подключение либы

В проекте:

Добавить → Ссылка на проект → MyLibrary
