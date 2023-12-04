# Седмица 8 - Базови алгоритми върху масиви

Bubble Sort:
=
**Описание**

Bubble Sort е прост алгоритъм за сортиране, който многократно обхожда списъка, сравнява съседни елементи и ги разменя, ако те не са в правилния ред. Този процес се повтаря до тогава, докато не се обходи целия масив без да се направи нито една размяна, което показва, че списъкът е сортиран.

**Процедура**

- Стартирайте от началото на масива.
- Сравнете текущия елемент със следващия.
- Ако текущият елемент е по-голям от следващия, разменете ги.
- Преминете към следващата двойка елементи и продължете стъпки 2 и 3, докато не достигнете края на масива.
- След всеки преглед на масива, най-големият елемент "плува" на повърхността или се премества в края на масива (оттук идва името "мехурчета").
- Повторете процеса за всички елементи, като намалявате броя на итерациите, тъй като най-големите елементи са вече на правилното си място и не е нужно да се обхождат.

**Сложност**

В най-лошия и средния случай O(n^2), където n е броят на елементите в масива. В най-добрия случай (когато масивът е вече сортиран) е O(n).

**Използване**

Bubble Sort е полезен за образователни цели и за разбиране на концепцията на сортирането.
Обикновено не е практичен за реални приложения поради своята неефективност, особено при големи масиви.


Selection Sort:
=

Описание: Алгоритъмът обхожда масива и на всяка итерация селектира най-малкия (или най-големия) елемент от несортираната част и го разменя с първия елемент от несортираната част.
Сложност: Винаги O(n^2), където n е броят на елементите.
Използване: Подходящ за малки списъци; неефективен за големи обеми данни.

Insertion Sort:
=

Описание: Взима елемент от несортираната част и го вмъква на правилното му място в сортираната.
Сложност: O(n^2) в най-лошия и средния случай, но близо до O(n) ако данните са предварително частично подредени.
Използване: Ефективен за малки набори от данни или когато данните са почти сортирани.

Quick Sort:
=

Описание: Алгоритъм от типа "разделяй и владей", който избира "опорен" елемент и разделя масива на две части: елементи по-малки от опорния и такива по-големи от него, след което рекурсивно сортира двете подмасиви.
Сложност: Средно и най-добро време O(n log n), но в най-лошия случай O(n^2).
Използване: Много ефективен за големи набори от данни.