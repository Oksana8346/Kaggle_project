
![](./images/data_cleaning.png)
# <center> Анализ отзывов о бронировании отелей </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Установка проекта](#Установка-проекта)
4. [Использование проекта](#Использование)
5. [Автор](#Автор)
6. [Итоги](#Итоги)

## Описание проекта

> Настоящий проект демонстрирует исполнение возможной  задачи дата-саентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из таких путей решения проблемы является построение модели предсказывающей рейтинг отеля.

**Данный проект** направлен на развитие практических навыков связанных с преобразованием, отбором созданием признаков, подготовкой данных для создания модели, созданием и обучением модели, оценкой качества модели.


## Описание данных
В этом проекте используются данные с соревнования [Отзывы о бронировании Прогнозирование рейтинга отеля на Booking](https://www.kaggle.com/competitions/sf-booking/overview)


Исходный набор данных представляет из себя три файла, два из которых содержат табличные данные отзывов о бронировании отелей и состоят из 17 признаков.



## Установка проекта

```
git clone https://github.com/Oksana8346/Kaggle_project.git
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке eda-project-3.ipynb.

## Автор

* [Оксана Ли]

## Итоги

В ходе работы над проектом часть признаков была преобразована, на основе некоторых были созданы новые, произведен отбор признаков для построения модели. Построена модель, предсказывающая рейтинги отелей с показателем MAPE: 0.9263985987824199.