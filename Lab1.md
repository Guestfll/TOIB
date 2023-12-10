### 1. Создаем 2 виртуальные машины на базе ОС Debian 12

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231118163754.png)

### 2. Обеспечиваем между ними сетевой обмен

В настройках сети виртуальных машин выбираем Bridged Adapter. 

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231118164323.png)

### 3. Устанавливаем keycloak на Host машине, произодим первоначальную настройку:

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231118171149.png)

Создаем real-me

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231209173017.png)

Создаем пользователей

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231209191039.png)

Подключаем клиент Nextcloud

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231209191003.png)

### 4. Разворачиваем тестовое приложение на User машине и подключаем его к keycloak

[Инструкция по установке](https://itproblog.ru/%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-nextcloud/)

Авторизация через Keycloak для Nextcloud:

![](https://github.com/Guestfll/TOIB/blob/main/Pasted%20image%2020231209194416.png)

