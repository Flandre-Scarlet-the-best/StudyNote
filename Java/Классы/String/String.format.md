```Java
static String format(String format, Object… args)
```
Создание форматированной строки. Спецификаторы форматирования аналогичны методу [[Вывод на консоль|printf()]].

Пример:
```Java
double x = 3.1415;
String out = String.format("x = %6.3f", x); System.out.println(out);
```
На консоль будет выведено:
**x =  3,142**
