# Лабораторная №2 (Численное решение нелинейных уравнений)
Лабораторная 2 по Вычислительной математике ИТМО.  
**Метод половинного деления, Ньютона, простой итерации**.  
Цель лабораторной работы: реализовать методы: “Половинного деления, Ньютона, Простые итерации” и протестировать программу для решения нелинейного уравнения.

Функция по варианту: `−1,8 * x^3 − 2,94 * x^2 + 10,37 * x + 5,38`

## Программная реализация  
1. Все численные методы должны быть реализованы в виде отдельных подпрограмм или классов.
2. Пользователь выбирает уравнение, корень/корни которого требуется вычислить (3-5 функций, в том числе и трансцендентные), из тех, которые предлагает программа.
3. Предусмотреть ввод исходных данных (границы интервала/начальное приближение к корню и погрешность вычисления) из файла или с клавиатуры по выбору конечного пользователя.
4. Выполнить верификацию исходных данных. Для метода половинного деления анализировать наличие корня на введенном интервале. Для метода Ньютона – выбор начального приближения (а или b). Для метода простой итерации – достаточное условие сходимости метода. Программа должна реагировать на некорректные введенные данные.
5. Предусмотреть вывод результатов (найденный корень уравнения, значение функции в корне, число итераций) в файл или на экран по выбору конечного пользователя.
6. Организовать вывод графика функции, график должен полностью отображать весь исследуемый интервал (с запасом).