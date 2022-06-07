# Linux
## Лабораторная работа №8

## Вопросы:
#### Какая команда позволяет установить задания планировщика?
```at```

#### Что сделает Команда atrm 7?
```удалит задачу 7 ```

#### Какая команда позволяет установить планировщику crontab задания из файла jobs?
``` crontab jobs ```
#### Когда будет готово задание 19 */2 13 * 5 job.sh ?
``` Каждый месяц, если пятница выпадает на 13 число, каждые 2 часа в 19 минут ```
#### Напишите cron строку установленной на выполнение скрипта job.sh с января по май, в 01:00 по воскресеньям
``` crontab 0 1 * 1-5 0 job.sh ```
#### Просмотреть список всех смонтированных разделов можно командой?
``` mount ```

## Практика:
продемонстрировать работу at по запуску задачи записи в файл произвольной строки
![!](https://github.com/AntyufeevA/lab8/blob/main/1.jpg)

продемонстрировать работу cron по запуску задачи записи в файл произвольной строки
![!](https://github.com/AntyufeevA/lab8/blob/main/2.jpg)
