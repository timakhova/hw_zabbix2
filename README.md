## Домашнее задание к занятию «Система мониторинга Zabbix. Часть 2» Тимахова Наталья
# Задание 1

![1-1](https://github.com/timakhova/hw_zabbix2/blob/main/1-1.png)
![1-2](https://github.com/timakhova/hw_zabbix2/blob/main/1-2.png)

# Задание 2 и 3

![2-3](https://github.com/timakhova/hw_zabbix2/blob/main/2%D0%B83-1.png)
![2-3-2](https://github.com/timakhova/hw_zabbix2/blob/main/2%D0%B83-2.png)

# Задание 4
![4-1](https://github.com/timakhova/hw_zabbix2/blob/main/4-1.png)

# Задание 6

Написала след-ий скрипт:

#!/bin/bash

if [ "$1" -eq 1 ]; then
    echo "Timakhova Natalia Mikhailovna"
elif [ "$1" -eq 2 ]; then
    date
else
    echo "Неверный параметр"
fi

В конец файла /etc/zabbix/zabbix_agentd.conf добавила UserParameter=custom.script[*],/usr/local/bin/zabbix_custom_script.sh $1

![6-1](https://github.com/timakhova/hw_zabbix2/blob/main/6-2.png)
![6-2](https://github.com/timakhova/hw_zabbix2/blob/main/6-3.png)
![6-3](https://github.com/timakhova/hw_zabbix2/blob/main/6-4.png)


