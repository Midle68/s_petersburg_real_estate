# Проект "Исследование объявлений о продаже квартир"

## Описание проекта:

Предоставлен набор данных от Яндекс Практикума - архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. 
Необходимо установить параметры, влияющую на цену. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

## План работы:

1. [Импорт библиотек и данных](#import)
2. [Предобработка данных](#preprocessing)
    - ['cityCenters_km'](#cityCenters_km)
    - ['ceiling_height'](#ceiling_height)
    - ['living_area'](#living_area)
    - ['is_apartment'](#is_apartment)
    - ['kitchen_area'](#kitchen_area)
    - ['floors_total'](#floors_total)
    - ['balcony'](#balcony)
    - ['locality_name'](#locality_name)
    - ['days_exposition'](#days_exposition)
    - ['first_day_exposition'](#first_day_exposition)
    - ['parks_around3000'](#parks_around3000)
    - ['ponds_around3000'](#ponds_around3000)
    - ['last_price'](#last_price)
    - ['rooms'](#rooms)
3. [Feature Engineering](#feature_engineering)
4. [Исследовательский анализ данных](#eda)
5. [Исследования](#research)
    - [Исследование 1](#research_one)
    - [Исследование 2](#research_two)
    - [Исследование 3](#research_three)
6. [Общий вывод](#conclusion)

## Решенные задачи:

1) Осуществлена предобработка данных;
2) Проведен исследовательский анализ данных;
3) Проведено исследование;
4) Обобщены выводы.

## Используемые библиотеки:

`matplotlib`, `pandas`
