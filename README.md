# **Сборная проектная работа студентки Яндекс.Практикум отделения аналитики**
[Яндекс.Практикум] (https://practicum.yandex.ru/)

## Описание проекта:
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). 
Перед вами данные до 2016 года.  
Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.    
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков». 
    
***Цель исследования*** - Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.   

***Исходные данные*** - данные о продажах компьютерных игр до 2016 года.  

***Ход исследования:***   
 Сколько игр выпускалось в разные годы?  
 Как менялись продажи по платформам?  
 Какие платформы лидируют по продажам, растут или падают?   
 Как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков?    
  
Определить для пользователя каждого региона (NA, EU, JP):  
 - Самые популярные платформы (топ-5).
 - Самые популярные жанры (топ-5).
Влияет ли рейтинг ESRB на продажи в отдельном регионе?  

Проверить гипотезы:  
 - Средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
 - Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.


### Описание данных:
Name — название игры  
Platform — платформа  
Year_of_Release — год выпуска  
Genre — жанр игры  
NA_sales — продажи в Северной Америке (миллионы проданных копий)  
EU_sales — продажи в Европе (миллионы проданных копий)  
JP_sales — продажи в Японии (миллионы проданных копий)  
Other_sales — продажи в других странах (миллионы проданных копий)  
Critic_Score — оценка критиков (максимум 100)  
User_Score — оценка пользователей (максимум 10)  
Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board).   
Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.  


## Инструменты:
Pyton  
Pandas  
Matplotlib  
Seaborn  
Numpy  
Jupyter Notebook  

## Итоги исследования
Были проведены исследования по всем поставленным задачам и сделаны выводы по каждому. 
С результатами вы можете ознакомиться в файле.

## Ссылка на репозиторий: 
