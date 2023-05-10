# 9-4-Git

Домашнее задание к занятию 9.4. «Система мониторинга Prometheus» - Григорьев Сергей

Задание 1
Установите Prometheus.

Процесс выполнения
Выполняя задание, сверяйтесь с процессом, отражённым в записи лекции.
Создайте пользователя prometheus
Скачайте prometheus и в соответствии с лекцией разместите файлы в целевые директории
Создайте сервис как показано на уроке
Проверьте что prometheus запускается, останавливается, перезапускается и отображает статус с помощью systemctl
Требования к результату
Прикрепите к файлу README.md скриншот systemctl status prometheus, где будет написано: prometheus.service — Prometheus Service Netology Lesson 9.4 — [Ваши ФИО]

![1-1](https://github.com/SG-netology/9-4-Git/blob/main/1-1.png)
![1-2](https://github.com/SG-netology/9-4-Git/blob/main/1-2.png)
![1-3](https://github.com/SG-netology/9-4-Git/blob/main/1-3.png)

Задание 2
Установите Node Exporter.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Скачайте node exporter приведённый в презентации и в соответствии с лекцией разместите файлы в целевые директории
Создайте сервис для как показано на уроке
Проверьте что node exporter запускается, останавливается, перезапускается и отображает статус с помощью systemctl
Требования к результату
Прикрепите к файлу README.md скриншот systemctl status node-exporter, где будет написано: node-exporter.service — Node Exporter Netology Lesson 9.4 — [Ваши ФИО]

![2-1](https://github.com/SG-netology/9-4-Git/blob/main/2-1.png)
![2-2](https://github.com/SG-netology/9-4-Git/blob/main/2-2.png)

Задание 3
Подключите Node Exporter к серверу Prometheus.

Процесс выполнения
Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.
Отредактируйте prometheus.yaml, добавив в массив таргетов установленный в задании 2 node exporter
Перезапустите prometheus
Проверьте что он запустился

![3-1](https://github.com/SG-netology/9-4-Git/blob/main/3-1.png)
![3-2](https://github.com/SG-netology/9-4-Git/blob/main/3-2.png)
