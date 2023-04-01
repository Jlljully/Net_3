# Домашнее задание к занятию «Компьютерные сети. Лекция 3»

1. Подключитесь к публичному маршрутизатору в интернет. Найдите маршрут к вашему публичному IP.

 ```
telnet route-views.routeviews.org
Username: rviews
show ip route x.x.x.x/32
show bgp x.x.x.x/32
```

### Ответ

2. Создайте dummy-интерфейс в Ubuntu. Добавьте несколько статических маршрутов. Проверьте таблицу маршрутизации.

### Ответ

3. Проверьте открытые TCP-порты в Ubuntu. Какие протоколы и приложения используют эти порты? Приведите несколько примеров.

### Ответ

4. Проверьте используемые UDP-сокеты в Ubuntu. Какие протоколы и приложения используют эти порты?

### Ответ

5. Используя diagrams.net, создайте L3-диаграмму вашей домашней сети или любой другой сети, с которой вы работали. 

### Ответ


 ---
 
## Задание со звёздочкой* 

Это самостоятельное задание, его выполнение необязательно.

6. Установите Nginx, настройте в режиме балансировщика TCP или UDP.

### Ответ

7. Установите bird2, настройте динамический протокол маршрутизации RIP.

### Ответ

8. Установите Netbox, создайте несколько IP-префиксов, и, используя curl, проверьте работу API.

### Ответ

