# Лабораторная работа №4: Создание системы авторизации в веб-приложении

Лабораторная работа №4, выполненная в рамках дисциплины «Введение в информационные технологии».

Ссылка на задание: [pdf](appendix/task.pdf)

Ссылка на отчет о проделанной работе: [docx](appendix/report.docx)

## Домашнее задание

* Дополнить таблицу users в базе данных до 10 пользователей
* Сделать обработку исключения на ввод пустого логина и пароля
* Сделать обработку исключения на отсутствие пользователя в базе данных
* Вывести на странице аккаунта помимо имени пользователя его логин и пароль

## Инструкция по запуску

С использованием пакетного менеджера `poetry`:

```bash
poetry shell && poetry install
cd authorization
flask run
```

Стандартными средствами `python` (рекомендуется прежде создать отдельное [виртуальное окружение](https://docs.python.org/3/library/venv.html)):

```bash
pip3 install -r requirements.txt
cd authorization
flask run
```
