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

## Local Links
[[CSharp]]


## Global Links
[[00 Programming]]
[[00 Learning]]
[[00 Conspects]]