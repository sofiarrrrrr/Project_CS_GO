# Project_CS_GO
## Участники проекта: 
1) Григорий Карташев 

2) Софья Арефьева 

3) Ксения Бастер 

## Окончательно готовый проект лежит в "Проект КС ГО (Finally).ipynb"

## Описание проекта: 
Мы решили проанализировать лондонский рынок аренды велосипедов. Взяли данные по аренде с кегля https://www.kaggle.com/datasets/kalacheva/london-bike-share-usage-dataset, данные о погоде взяли с https://rp5.ru/Архив_погоды_в_Лондоне,_Сент-Джеймском_парке. Поставили цель: выявить взаимосвязь влияния погоды на аренду велосипедов. В том числе проанализировали время взятие велосипеда, день недели и продолжительность поездки. 
## Облако с исходными данными 
https://cloud.mail.ru/public/8EeH/7aUc4y9rW

## Как использавали машинку:
1. В самом начале мы выделили некоторые признаки для прогнозирования длительности поездки в секундах. Так как даже после оптимизации не удалось достигнуть нормального Р^2 (он был 0.01), решено сделать логистическую регрессию для прогнозирования, был ли дождь в определенную поездку по параметрам поездки
2. Перепробовали разные модели тюнинга гиперпараметров у логистической регрессии

## Наши гипотезы: 
1) В выходные люди берут велосипеды реже чем в буднии
2) Влияет ли дождь на среднюю длительность поездки?
3) Влияет ли температура на длительность поездки?




