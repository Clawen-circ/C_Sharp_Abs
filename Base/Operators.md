# Operators
Это выражения, они могут состоять из нескольких частей, при этом каждый оператор оканчивается точкой с запятой, например:
```csharp
var totalPrice = subtotal + salesTax;
```

## Оператор ветвления if ... else
Синтаксис:
```csharp
if (condition) {
	// блок кода, который выполнится если condition будет True
}
else {
	// блок кода, который выполнится если condition будет False
}
```
### elseif
Синтаксис:
```csharp
if (condition1)
{
  // блок кода, который выполнится если condition1 будет True
} 
else if (condition2) 
{
  // блок кода, который выполнится если condition1 будет False,
  // а condition2 - True
} 
else
{
  // блок кода, который выполнится если condition1 и condition2 будет False
}
```

## Тернарный оператор ?
Тернарный оператор (?) сокращает запись`if ... else` делая её короче, но усложняет понимание для начинающих.
Синтаксис:
```csharp
variable = (condition) ? expressionTrue : expressionFalse;
```

Пример:
```csharp
int time = 20;
string result = (time < 18) ? "Good day." : "Good evening.";
Console.WriteLine(result); // Good evening.
```

## Оператор ветвления switch
Используйте оператор `switch`, чтобы выбрать один из множества блоков кода для выполнения.
Синтаксис:
```csharp
switch(expression) 
{
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
    break;
}
```
Вот как это работает:
- Выражение переключения вычисляется один раз
- Значение выражения сравнивается со значениями каждого случая.
- Если есть совпадение, выполняется связанный блок кода.
### Ключевое слово break и default
Когда C # достигает ключевого слова `break`, он выходит из блока `switch`.
Это остановит выполнение большего количества кода и тестирования случаев внутри блока.
Ключевое слово `default` является необязательным и указывает некоторый код для запуска, если нет совпадения по регистру:
```csharp
int day = 4;
switch (day) 
{
  case 6:
    Console.WriteLine("Today is Saturday.");
    break;
  case 7:
    Console.WriteLine("Today is Sunday.");
    break;
  default:
    Console.WriteLine("Looking forward to the Weekend.");
    break;
}
// Outputs "Looking forward to the Weekend."
```
## Local Links
[[CSharp]]


## Global Links
[[00 Programming]]
[[00 Learning]]
[[00 Conspects]]