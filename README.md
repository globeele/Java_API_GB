# Java: знакомство и как пользоваться базовым API (семинары)
## Урок 1. Знакомство с языком программирования Java
№1. **N-ое треугольное число**

Вычислить n-ое треугольного число(сумма чисел от 1 до n).
Внутри класса Answer напишите метод countNTriangle, который принимает число n и возвращает его n-ое треугольное число.

№2. **Вывести простые числа**

Напишите функцию printPrimeNums, которая выведет на экран все простые числа в промежутке от 1 до 1000, каждое на новой строке.
Напишите свой код в методе printPrimeNums класса Answer.

№3. **Реализуйте простой калькулятор**

Напишите класс Calculator, который будет выполнять математические операции (+, -, *, /) над двумя числами и возвращать результат. В классе должен быть метод calculate, который принимает оператор и значения аргументов и возвращает результат вычислений.
При неверно переданном операторе, программа должна вывести сообщение об ошибке "Некорректный оператор: 'оператор'".

№4*. **Восстановите выражение**

В файле задано уравнение вида q + w = e (q, w, e >= 0). Некоторые цифры могут быть заменены знаком вопроса, например 2? + ?5 = 69.
Восстановите выражение до верного равенства.
Предложите хотя бы одно решение или сообщите, что его нет.
Напишите класс Equation, содержащий метод getSolution, который будет считывать уравнение из файла и восстановит его до верного равенства.
Выведите сначала строку формата "Given the equation: {выражение из файла}".
А затем верните строку формата "Result: {цельное выражение}".
Если выражение не имеет решений - верните строку "No solution".