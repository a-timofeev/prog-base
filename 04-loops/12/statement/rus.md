# Быки и коровы (*)

Напишите компьютерную реализацию игры "Быки и коровы".

Правила:

+ Компьютер загадывает четырёхзначное число. Все цифры **должны быть различны**.
+ Игроку необходимо отгадать это число. Он может вводить свои числа в которых
  также все цифры должны быть различны.
+ На каждую попытку компьютер отвечает сколько цифр угадано. Если пользователь
  угадал цифру и её позицию, то такое совпадение называется "бык".
  Если пользователь угадал цифру, но не угадал позицию, то такое совпадение
  называется "корова". Программа после каждой попытки отвечает сколько
  "быков" и "коров".

## Пример

Загадано  Попытка  Ответ программы             Примечание
--------  -------  --------------------------- -----------
 0239      6875     быков: 0, коров: 0         ни одна цифра не угадана
 0239      5329     быков: 1, коров: 2         9 на месте, 2 и 3 на других местах
 0239      9320     быков: 0, коров: 4         цифры угаданы, но позиции не верные
 0239      0239     Вы отгадали за 4 попытки!



