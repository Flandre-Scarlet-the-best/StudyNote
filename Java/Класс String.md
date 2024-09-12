Любая символьная строка (в том числе и строковый литерал) по умолчанию является объектом класса **String**. 
Например:
```Java
System.out.println("I love Java");
```
символьная строка *"I love Java"* является объектом класса **String**.

Объекты класса String являются **неизменяемыми** после их создания.

**String** -  ссылочный тип. Описание *String st;* создает в стековой памяти переменную для хранения ссылки на объект-строку. А сам объект (который будет размещен в динамической памяти) еще не создан. Рассмотрим различные способы создания объекта-строки.

- [[Создание строк]]
- [[Сравнение строк]]

Методы:
- [[concat()|concat]]
- [[equals()|equals]] | [[equalsIgnoreCase()|equalsIgnoreCase]]
- [[compareTo()|compareTo]] | [[compareToIgnoreCase()|compareToIgnoreCase]]
- [[contentEquals()|contentEquals]]
- [[substring()|substring]]
- [[length()|length]]
- [[indexOf()|indexOf]] | [[lastIndexOf()|lastIndexOf]]
- [[toUpperCase() , toLowerCase()|toUpperCase | toLowerCase]]
- [[replace()|replace]]
- [[trim()|trim]]
- [[charAt()|charAt]]
- [[isEmpty()|isEmpty]]
- [[getChars()|getChars]]
- [[split()|split]]
- [[intern()|intern]]
- [[String.valueOf|valueOf]]
- [[String.format|format]] 