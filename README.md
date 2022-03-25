# :white_check_mark: ft_printf (project 2020)  
## Описание  
Этот проект выполнен в соответствии с требованиями школы программирования 21 (42 школа).
Основной задачей в этом проекте является реализация отдельных компонентов оригинальной функции printf.
Список преобразований, которые я реализовал в коде:
| Спецификатор | Описание | Пример |
|:---------:|:-----------:|:-------:|
| %с | Вывод любого символа из таблицы ASCII | '$' |
| %s | Выведите массив символов с нулл символом в конце ('\0') | "Hello World!" |
| %p | Вывод адреса указателя | 0xfff000bd8 |
| %d and %i | Вывод целого числа в десятичной системе счисления | 1488 |
| %u | Вывод целого числа без знака в десятичной системе счисления | 3000000000 |
| %x | Выведите целое число без знака в шестнадцатеричной системе счисления | 15e20a |
| %X | Выведите целое число без знака в шестнадцатеричной системе счисления | 15E20A |
| %% | Вывод знака "%" | % |  

Список используемых флагов:  
| Flag | Description |
|:----:|:-----------:|
| - | Left-align text with the specified width |
| (number). | The minimum number of characters to output as a width. If the number has fewer characters, it inserts spaces (or zeros) |
| .(number) | For integer specifiers (d, i, o, u, x, X), precision determines the minimum number of characters to output. If the value is shorter, zeros are output before the number. The value is not truncated, even if it is longer. An accuracy of 0 means that nothing is output for the value 0. |
| *. | The width is not specified in the format string, it is passed separately as an argument that must precede the output number |
| .* | Precision is not specified in the format string, but is passed separately as an argument that must precede the output number |  

## Проект протестирован тестером "PFT"  
Ссылка на тестер: [click](https://github.com/gavinfielder/pft)  

## Запуск
Основные команды:
```
make (make all) - compilation libftprintf.a
make clean - clearing *.o files  
make fclean - clearing *. o files and libraries  
```
  
**Author:** *[Andrey Belenov](https://github.com/luchikAR)* 
