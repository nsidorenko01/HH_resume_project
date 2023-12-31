# Проект. Анализ резюме из HeadHunter

## Оглавление

[1. Описание проекта](.README.md#Описание-проекта)  
[2. Описание кейса](.README.md#Описание-кейса)  
[3. Структура проекта](.README.md#Структура-проекта)  
[4. Информация о данных](.README.md#Информация-о-данных)  
[5. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[6. Результаты проекта](.README.md#Результаты-проекта)  

### Описание проекта

С помощью инструментов Python и встроенных в него библиотек в данном проекте реализован анализ данных по резюме соискателей с сайта HeadHunter.

### Описание кейса

Часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме. Это является помехой для рекомендательной системы HeadHunter, которая подбирает соискателям список наиболее подходящих вакансий, а работодателям — список наиболее подходящих специалистов. Поэтому, необходимо спрогнозировать желаемую заработную плату на основе определенных признаков, анализ которых реализуется в данном проекте.

### Структура проекта
1. [data](data) - папка с исходными данными для анализа.
2. [graphics_html](graphics_html) - папка с графиками в Plotly формата html.
3. [Project_HH_analysis.ipynb](Project_HH_analysis.ipynb) - jupyter-notebook с анализом данных.
4. [Google drive с графиками в html](https://drive.google.com/drive/folders/1ZR8ANVG9C0u9iwLOjEuDjvV9o986o39O?usp=drive_link)
5. [Google drive с датасетом по признакам соискателей](https://drive.google.com/file/d/1y4KybwvCg8WkW60--PYci-FIaSssWB7v/view?usp=sharing)

### Информация о данных

В ходе анализа были использованы обезличенные данные о людях в поиске работы с платформы HeadHunter. Выборка содержит информацию о соискателях, которая необходима для прогнозирования желаемой заработной платы. 

Размер исходной выборки - 44744 строки, 12 столбцов.

Также для полного анализа желаемой заработной платы были использованы данные о курсе валют за определенный промежуток времени, поскольку соискатели указывают желаемую заработную плату не только в рублях.

### Этапы работы над проектом

1. Предварительный анализ данных на объем, пропущенные значения и дубликаты.
2. Обработка и парсинг признаков, некорректно представленных в исходных данных.
3. Визуальный анализ взаимосвязей признаков соискателей.
4. Обработка датасета и работа с пропущенными значениями, дубликатами и выбросами.

### Результаты проекта

В результате проекта были выявлены значимые признаки, которые могут оказывать влияние при построении модели машинного обучения, предсказывающей желаемую заработную плату.

:arrow_up:[ К оглавлению](.README.md#Оглавление)

Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️