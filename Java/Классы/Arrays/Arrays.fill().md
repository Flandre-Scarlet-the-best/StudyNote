#Метод #Массивы 

```Java
void fill(Object[] a, Object val)
```
Заполняет массив **a** одинаковыми значениями **val**.  Работает только с одномерными массивами.

Пример:
```Java
double[] b = new double[5];
Arrays.fill(b, 2.5);
System.out.println(Arrays.toString(b));
```
**[2.5, 2.5, 2.5, 2.5, 2.5]**

Если нужно заполнить только часть массива, то нужно указать пределы
```Java
Arrays.fill(b, 2, 4, 0.8); System.out.println(Arrays.toString(b));
```
2.5, 2.5, **0.8, 0.8**, 2.5

