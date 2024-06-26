# Анализ данных для интернет-магазина компьютерных игр «Стримчик»

__Данные__: games.csv

__Описание данных__: 
- `Name` — название игры
- `Platform` — платформа
- `Year_of_Release` — год выпуска
- `Genre` — жанр игры
- `NA_sales` — продажи в Северной Америке (миллионы проданных копий)
- `EU_sales` — продажи в Европе (миллионы проданных копий)
- `JP_sales` — продажи в Японии (миллионы проданных копий)
- `Other_sales` — продажи в других странах (миллионы проданных копий)
- `Critic_Score` — оценка критиков (максимум 100)
- `User_Score` — оценка пользователей (максимум 10)
- `Rating` — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

__Цель:__ выявить определяющие успешность игры закономерности


__План работ:__
1. Открыть файл с данными и изучить общую информацию:
    - Путь к файлу: /datasets/games.csv.
2. Подготовить данные:
    - заменить названия столбцов (привести к нижнему регистру);
    - преобразовать данные в нужные типы;
    - обработать пропуски при необходимости;
    - выявить причины, которые могли привести к пропускам;
    - обработать значение tbd
    - посчитать суммарные продажи во всех регионах и записать их в отдельный столбец.
3. Провести исследовательский анализ данных:
    - посмотреть сколько игр выпускалось в разные годы.    
    - посмотреть, как менялись продажи по платформам. выбрать платформы с наибольшими суммарными продажами и построить распределение по годам.
    - выявить какие платформы лидируют по продажам, растут или падают. Выберать несколько потенциально прибыльных платформ.
    - построить график «ящик с усами» по глобальным продажам игр в разбивке по платформам.
    - посмотреть, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Построить диаграмму рассеяния и посчитать корреляцию между отзывами и продажами.
    - соотнести выводы с продажами игр на других платформах.
    - посмотреть на общее распределение игр по жанрам. 
4. Составить портрет пользователя каждого региона
    - определить для пользователя каждого региона (NA, EU, JP):
        - самые популярные платформы (топ-5).
        - самые популярные жанры (топ-5).
        - влияет ли рейтинг ESRB на продажи в отдельном регионе.
5. Проверить гипотезы
    - средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
    - средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.
6. Написать общий вывод

https://github.com/tverikinlv/games_analysis/blob/main/games_analysis.ipynb
