# Программирование на С++
Вводный курс по C++ со вкраплениями нетривиальных вещей

План:
* Тема 0 - Введение
* Тема 1 - Работа с памятью
* Тема 2 - Классы и объекты. Инкапсуляция
* Тема 3 - Перегрузка операторов
* Тема 4 - Наследование
* Тема 5 - Полиморфизм. Абстрактные классы и интерфейсы
* Тема 6 - Агрегация/Композиция vs. Наследование vs. Дружественность
* Тема 7 - RTTI, dynamic_cast
* Тема 8 - Исключения
* Тема 9 - Шаблонные функции и классы. SFINAE
* Тема 10 - Библиотека STL
* Тема 11 - RAII. Умные указатели
* Тема 12 - Современные стандарты С++

&#43;

Демо-проект "Консольный блекджек" с дополнительными элементами:
- с++14 (auto, unique_ptr, shared_ptr, move, lambdas)
- автодокументация кода для doxygen
- юнит-тесты google test
- директивы препроцессора
- файлы makefile


В репозитории хранится несколько релизных версий:


[Версия 1](https://github.com/ar1st0crat/CppCourse/releases/tag/'demo_ver1')

Вариант "Студенческий середнячок": модульная объектно-ориентированная декомпозиция, пара интерфейсов, обработка исключений, кое-какие возможности С++ новых стандартов, добавлены простейшие юнит-тесты.

[Версия 2](https://github.com/ar1st0crat/CppCourse/releases/tag/'demo_ver2')

Предыдущий вариант, но с добавлением умных указателей. Обязательно ознакомиться со статьей Эрба Саттера: [GOTW #91](https://herbsutter.com/2013/06/05/gotw-91-solution-smart-pointer-parameters/) для понимания принципов ведения и передачи умных указателей в качестве параметров.

[Версия 3](https://github.com/ar1st0crat/CppCourse/tree/master/DemoProject)

Более-менее взрослый вариант: архитектура MVP, паттерны State и Strategy, проект достаточно тестируемый и расширяемый, добавлены интеграционные тесты, некоторые решения относительно кода были приняты после написания тестов (TDD).
