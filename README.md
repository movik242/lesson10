# lesson10

Домашнее задание:
Написать свою реализацию ps ax используя анализ /proc

*Результат ДЗ - рабочий скрипт который можно запустить

При выполнении ДЗ использован Vagrant boxes файл системы Centos Stream 8 сборка 20230501.0

Для реализации аналога ps ax подготовлен скрипт файл ps.sh:

      PID, PPID, State - вытаскиваем из /proc/*/status
      Command забираем из /proc/*/cmdline
      Цикл пробегает по процессам и собирает информацию
      Вывод информации

![image](https://github.com/movik242/lesson10/assets/143793993/1e5a82cc-aae4-4f28-a73d-51aa0cc0e86b)
![image](https://github.com/movik242/lesson10/assets/143793993/a95a974c-975b-4054-a8c5-2469f9016bce)



