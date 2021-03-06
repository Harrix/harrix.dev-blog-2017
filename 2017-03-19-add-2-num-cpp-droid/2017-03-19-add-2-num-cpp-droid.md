---
categories: [it, programming]
tags: [C++, Android, Сложение двух чисел]
---

# Сложение двух чисел в CppDroid на C++

В статье рассказывается, как создать консольное приложения сложения двух чисел в CppDroid на Android.

## Программа

Программировать под C++ можно и в Android. CppDroid одна из таких приложений. Вот ссылка на приложение:

[Google Play](https://play.google.com/store/apps/details?id=name.antonsmirnov.android.cppdroid&hl=ru)

При открытии приложения будет произведена скачка и установка нужных файлов:

![Установка новых файлов](img/install.png)

После этого откроется главное окно приложения:

![Окно программы](img/cpp-droid.png)

## Болванка приложения

Введем в редакторе вот такой код:

```cpp
#include <iostream>
using namespace std;
int main(){

return 0;
}
```

![Код болванки](img/code_01.png)

Сохраните и скомпилируйте приложение:

![Компилирование проекта](img/run_01.jpg)

![Завершение компилирования](img/run_02.png)

После этого запустите приложение:

![Запуск приложения](img/run_03.jpg)

Откроется пустое окно. Если вы его видите, то всё хорошо:

![Запущенная болванка приложения](img/result_01.png)

## Написание кода

Внутри функции `main` напишем такой код:

```cpp
int a, b, c;
cout << "Input first number:"<< endl;
cin >> a;
cout << "Input second number:"<< endl;
cin >> b;
c = a + b;
cout << "Sum = " << c;
return 0;
```

Полный код будет такой:

```cpp
#include <iostream>
using namespace std;
int main(){
int a, b, c;
cout << "Input first number:"<< endl;
cin >> a;
cout << "Input second number:"<< endl;
cin >> b;
c = a + b;
cout << "Sum = " << c;
return 0;
}
```

![Код программы](img/code_02.png)

Аналогичным способом выше сохраним, скомпилируем и запустим программу:

![Компилирование программы](img/run_04.png)

![Запущенное приложение](img/result_02.png)

Введите числа и получите в результате:

![Результат выполнения программы](img/result_03.png)
