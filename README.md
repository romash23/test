# <center> Проект 1. Анализ резюме из HeadHunter

## Оглавление
[1. Описание проекта](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Результат)    
[6. Выводы](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/readme.md#Выводы) 


### Описание проекта

 
:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)


### Какой кейс решаем

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но чтобы построить модель, нужно сначала произвести некотоую работу с данными. Наша задача в этой проекте состоит как раз в том, чтобы эти данные преобразовать, исследовать и очистить.

***Условия соревнования:***
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

***Метрика качества***     
Результаты оцениваются по среднему количеству попыток при 1000 повторений. Дополнительное условие: необходимо, чтобы любое целое число от 0 до 100 "угадывалось" компьютером менее чем за 20 попыток

**Что практикуем**     
Учимся писать хороший код на python

:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)


### Краткая информация о данных
Данные для вычисления программа получает "случайным" образом, поскольку функция random() в Python используется для генерации псевдослучайных чисел. Функция random.seed() в Python используется для инициализации случайных чисел. По умолчанию генератор случайных чисел использует текущее системное время. Если вы дважды используете одно и то же начальное значение, вы получите один и тот же результат, что означает случайное число дважды.
Это упрощает оптимизацию кодов, когда для тестирования используются случайные числа. Вывод кода иногда зависит от ввода. Поэтому использование случайных чисел для тестирования алгоритмов может быть проблематичным.

:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)


### Этапы работы над проектом
В данном проекте мы будем опираться на два простейших подхода к решению этой задачи, которые были даны оставлены автором модуля. А именно:
- [Подход 1: Случайное угадывание](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/game_v1.py)
- [Подход 2: Угадывание с коррекцией](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/game_v2.py)

Для решения постановленной задачи была написана функция ***game_core_v3***
- [Решение поставленной задачи](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/game_v3.py)

:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)


### Результат
Для этого была написана функция ***max_attempt_score***, которая считает максимальное число попыток при угадывании программой целого числа от 0 до 100.
Также мы использовали функцию ***score_game***, написанную автором модуля. Она считает за какое количство попыток в среднем за 1000 подходов наш алгоритм угадывает число

[Для того, чтобы увидеть результат работы, нажмите сюда](https://github.com/romash23/roman_maryukov_DTS/blob/main/project_0/game.ipynb)

:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)


### Выводы
В данном модуле мы научились пользоваться платформой GitHub, познакомились со средой VS Code, а также применили знания, полученные ранее на практике

:arrow_up:[ К оглавлению](https://github.com/romash23/roman_maryukov_DTS/tree/main/project_0#Оглавление)