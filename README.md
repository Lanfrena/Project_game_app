## project_game_app
Проджект-менеджер дал задачу проанализировать данные по исследованию нескольких аспектов мобильного приложения для игр:
## 1
Retention – один из самых важных показателей в компании. Нужно написать функцию, которая будет считать retention игроков по дням от даты регистрации игрока, она должна работать как на полном датасете, так и на части (сэмпле) данных.
<br>
Данные для анализа:
- shared/problem1-reg_data.csv – данные о времени регистрации
- shared/problem1-auth_data.csv – данные о времени захода пользователей в игру

## 2
Имеются результаты A/B теста, в котором двум группам пользователей предлагались различные наборы акционных предложений. Известно, что ARPU в тестовой группе выше на 5%, чем в контрольной. При этом в контрольной группе 1928 игроков из 202103 оказались платящими, а в тестовой – 1805 из 202667.
<br>
- Какой набор предложений можно считать лучшим? 
- Какие метрики стоит проанализировать для принятия правильного решения и как?

## 3
В игре Plants & Gardens каждый месяц проводятся тематические события, ограниченные по времени. В них игроки могут получить уникальные предметы для сада и персонажей, дополнительные монеты или бонусы. Для получения награды требуется пройти ряд уровней за определенное время. 
- С помощью каких метрик можно оценить результаты последнего прошедшего события?

Предположим, в другом событии мы усложнили механику событий так, что при каждой неудачной попытке выполнения уровня игрок будет откатываться на несколько уровней назад. 
- Изменится ли набор метрик оценки результата? Если да, то как?
