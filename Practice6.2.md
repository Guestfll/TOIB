### 0. Исходные данные

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119194642.png)

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119194559.png)

### 1. Проверка связи между маршрутизаторами

Определение IP-адреса порта S0/0/0 на маршрутизаторе RA

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119194813.png)

Отправка эхо-запроса на ip-адресс интерфейса S0/0/0 маршрутизатора RA

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119194912.png)

Отправка эхо-запроса с PC-B на PC-A

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119195329.png)

Заметим, что компьютеры не видят друг друга, т.к туннель GRE не настроен.

### 2. Настройка туннелей GRE

Настройка GRE на роутере RA

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119200605.png)

Настройка GRE на роутере RB

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119201242.png)

Настройка маршрута для частного IP-трафика
  1. Маршрутизатор RA:
![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119201534.png)
  2. Маршрутизатор RB:
![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119201551.png)

### 3. Проверка связи между маршрутизаторами

Эхо-запрос с ПК B на ПК A

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119201806.png)

Эхо-запрос с ПК A на ПК B

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119202105.png)

### 4. Результат работы

![](https://github.com/Guestfll/TOIB/blob/main/attachments/Pasted%20image%2020240119202141.png)

