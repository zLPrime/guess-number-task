# Проект 0. Угадай число

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Угадать загаданное компьютером число за минимальное число попыток.

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Нужно написать программу, которая угадывает число за минимальное число попыток

**Условия соревнования:**  
- Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под «угадать», подразумевается «написать программу, которая угадывает число».
- Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.

**Метрика качества**     
Результаты оцениваются по среднему количеству попыток при 1000 повторений

**Что практикуем**     
Учимся писать хороший код на python


### Краткая информация о данных
В этом проекте данные не используются

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
- скачивание [заготовки проекта](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@guess-number-task.zip)
- написание функции `binary_predict`
- проверка и сравнение результатов

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Функция `binary_predict` справляется с задачей в среднем за 4 попытки; предложенная в заготвоке функция `random_predict` угадывает число в среднем за 100 попыток.

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
Алгортм бинарного поиска значительно эффективней случайного подбора

:arrow_up:[к оглавлению](.README.md#Оглавление)