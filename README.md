# Проект 1. Анализ резюме на hh.ru

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Анализ резюме на hh.ru

:arrow_up:[к оглавлению](_)


### Какой кейс решаем?    
Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю. Для расчётов будет браться информация из анкет. 


### Краткая информация о данных
Имеем дата файл заключённый в формате CSV. Изначальный дата сет представляет собой таблицу размерностью (44744, 23)
  
:arrow_up:[к оглавлению](.README.md#Оглавление)


### Этапы работы над проектом  
1. Проведём исследование структуры данных получили следующее:
   - часть записей имеют пропуски
   - некоторые столбцы необходимо разбить на более простые признаки
2. Преобразуем данные согласно этапу 1.
3. Проанализируем зависимости в данных в согласно требованиям к проекту: 
   - распределение признаков:
        - "Возраст",
        - "Опыт работы(месяц)",
        - "ЗП (руб)",
        - "ЗП (руб)" в разрезе признака "Город";
   - взаимосвязь между медианой желаемой заработной платы и мобильностью кандидатов;
   - величину медианой желаемой заработной платы в разрезе возраста и образования;
   - изучим как опыт работы зависит от возраста.  
   В рамках дополнительного исследования проведём: 
   - общий анализ опыта кандидатов
   - соотношение полов
   - влияние гендерного фактора на уровень желаемой заработной платы
4. Произведём очистку данных:
    - удалим: 
        - аномальные значения,
        - дубликаты;
    - заменим недостающий значения


:arrow_up:[к оглавлению](.README.md#Оглавление)


### Результаты:  
Дата сет подготовлен для передачи модели

:arrow_up:[к оглавлению](.README.md#Оглавление)


### Выводы:  
В общем и целом не было выявлено никаких особых тенденций

:arrow_up:[к оглавлению](.README.md#Оглавление)

