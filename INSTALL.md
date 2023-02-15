# Инструкции по сборке программ и документации из командной строки
Для сборки программы использовать следующие команды:
```
gcc main.c -o main --std=c99
gcc child.c -lm -o child --std=c99
```
Для сборки тестов использовать команду:
```
gcc unit_tests.c -o unit_tests -lcunit -lm
```
Для сборки документации использовать команду:
```
doxygen
firefox doxygen/html/index.html
```