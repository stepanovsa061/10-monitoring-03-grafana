# Домашнее задание к занятию 14 «Средство визуализации Grafana»

# Обязательные задания
# Задание 1

1) Используя директорию help внутри этого домашнего задания, запустите связку prometheus-grafana.
2) Зайдите в веб-интерфейс grafana, используя авторизационные данные, указанные в манифесте docker-compose.
3) Подключите поднятый вами prometheus, как источник данных.
4) Решение домашнего задания — скриншот веб-интерфейса grafana со списком подключенных Datasource.

# Ответ 1

![alt text](https://github.com/stepanovsa061/10-monitoring-03-grafana/blob/main/1.1%20docker.PNG)

![alt text](https://github.com/stepanovsa061/10-monitoring-03-grafana/blob/main/1.2%20grafana.PNG)

![alt text](https://github.com/stepanovsa061/10-monitoring-03-grafana/blob/main/1.3%20promet.PNG)


# Задание 2

Создайте Dashboard и в ней создайте Panels:

- утилизация CPU для nodeexporter (в процентах, 100-idle);
- CPULA 1/5/15;
- количество свободной оперативной памяти;
- количество места на файловой системе.

# Ответ 2

![alt text](https://github.com/stepanovsa061/)

![alt text](https://github.com/stepanovsa061/)

![alt text](https://github.com/stepanovsa061/)

![alt text](https://github.com/stepanovsa061/)


# Задание 3

Создайте для каждой Dashboard подходящее правило alert — можно обратиться к первой лекции в блоке «Мониторинг».

# Ответ 3

![alt text](https://github.com/stepanovsa061/)


# Задание 4

Сохраните ваш Dashboard.Для этого перейдите в настройки Dashboard, выберите в боковом меню «JSON MODEL». Далее скопируйте отображаемое json-содержимое в отдельный файл и сохраните его.

# Ответ 4

![alt text](https://github.com/stepanovsa061/)

