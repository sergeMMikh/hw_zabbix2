# Домашнее задание к занятию "`"Система мониторинга Zabbix`" - `Михалёв Сергей`

### Цели задания
1. Научиться устанавливать Zabbix Server c веб-интерфейсом
2. Научиться устанавливать Zabbix Agent на хосты
3. Научиться устанавливать Zabbix Agent на компьютер и подключать его к серверу Zabbix

---

### Задание 1 

Установите Zabbix Server с веб-интерфейсом.

#### Процесс выполнения
Задание выполнено на Amazon AWS.
1.  Установлен PostgreSQL.
2. Составен набор команд для установки последней версии Zabbix с поддержкой PostgreSQL и Apache.
3. Выполнены все необходимые команды для установки Zabbix Server и Zabbix Web Server.

#### Результат 
1. [Cкриншот](https://drive.google.com/file/d/11JCOTpmhFssoPbbOXnbClTCtCAFgWGYD/view?usp=sharing) авторизации в админке.
2. [Tекст](https://drive.google.com/file/d/11LcE96Nyya__BpNaq1HgyWerRdz3wAfO/view?usp=sharing) использованных команд в GitHub.

---

### Задание 2 

Установите Zabbix Agent на два хоста.

#### Процесс выполнения
2. Установил Zabbix Agent на 2 вирт.машины, одна из них- Zabbix Server.
3. Добавил Zabbix Server в список разрешенных серверов внешнего Zabbix Agentа. У сервера 127.0.0.1 уже настроен по умолчению.
4. Добавил Zabbix Agentов в раздел Configuration > Hosts Zabbix Servera.
5. Проверил, что в разделе Latest Data начали появляться данные с добавленных агентов.

#### Требования к результаты 
1. [Скриншот](https://drive.google.com/file/d/11NazFX0ms3mR7BYkl377G3z9z6rl-6dm/view?usp=sharing) раздела Configuration > Hosts, где видно, что агенты подключены к серверу.
2. [Cкриншот](https://drive.google.com/file/d/11TQ3H_GSU7SPg0MCyqmH5lgCOHEZNdb0/view?usp=sharing) лога zabbix agent, где видно, что он работает с сервером
3. [Скриншот](https://drive.google.com/file/d/11TjbIcErNc1q_5wpZqNSy2ePMACFuH4t/view?usp=sharing) раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.
4. [Текст](https://drive.google.com/file/d/11Wn8KAKSgFf56rzJyh84BzYyVqhHCn2q/view?usp=sharing) использованных команд в GitHub

---
