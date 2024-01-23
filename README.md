# как использовать модуль maths
1. скачайте файл [maths.h](https://github.com/makarova1507ana/11-1/blob/tasks/maths.h)
2. подключите файл maths.h
### **Пример:**
![image](https://github.com/makarova1507ana/11-1/assets/103330304/d2ba8156-54e9-4f5b-a3f3-880f41525e31)
#include <maths.h>

# Сандарты кодирования
- Соблюдайте соглашения по именованию, например, camelCase для переменных и функций.
- Используйте комментарии для пояснения кода и описания функций.
- Избегайте использования глобальных переменных, если это необходимо, документируйте их использование.
- Используйте константы вместо магических чисел.
- Документируйте любые зависимости от сторонних библиотек или компонентов.

## подключение библиотек 
```
#include <windows.h>
#include <math.h>
#include <maths.h>
#include<iostream>
using namespace std;
```
 
## Функция для выполнения сложения двух чисел.
  
@param a Первое слагаемое.
@param b Второе слагаемое.
@return результат сложения.
 
 
```
double add(double a, double b)
{
	return (a + b);
}
 
```
## Функция для выполнения сложения двух чисел.
  *
  * @param a Первое слагаемое.
  * @param b Второе слагаемое.
  * @return разность.
 
 
```
double subtract(double a, double b)
{
	return (a - b);
}
```
# пример работы функций
```
int main()
{
	double a = 5;
	double b = 3;
 
	cout << add(a, b) << "\n" << subtract(a, b);
	cout << "какой-то математический пример с использованием данных функций"; 
	return 0; 
}
```
