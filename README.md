# Безопасность веб-приложений. Лабораторка №2

## Вариант 1. Расписания

Сделать аналог раздела https://ssau.ru/rasp?groupId=531030143

Какие нужны возможности:
- справочники групп, табличные данные по расписаниям добывать с настоящего сайта на серверной стороне приложения
- в клиентскую часть подгружать эти сведения динамически по JSON-API
- обеспечить возможность смотреть расписания в разрезе группы или препода
- обеспечить возможность выбора учебной недели (по умолчанию выбирается автоматически)

## Запуск:
1. Скачать архив
<img width="464" alt="image" src="https://github.com/v0dnyy/websec-2/assets/92549113/1a04ed9e-386c-4718-afcd-481f7f4ae4d0">

2. Распаковать архив и перейти по пути: "websec-2-main\"

3. Открыть папку с помощью pycharm

4. Установить необходимые пакеты в терминале:
    pip install re
   
    pip install requests
   
    pip install bs4
   
    pip install datetime
   
    pip install json
   
    pip install flask


6. Открываем server_side.py в проекте и запускаем(в консоле отобразиться хост)
   <img width="720" alt="image" src="https://github.com/v0dnyy/websec-2/assets/92549113/e1c34afa-0781-406e-a11a-9f9cc277a790">

7. Переходим на http://127.0.0.1:5000/




