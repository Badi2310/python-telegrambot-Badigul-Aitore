# Описание проекта:

### Телеграмм бот
Погода 

API взят из сервиса https://openweathermap.org/

## Архитектура:
В файле "assets/token.txt" хранится токен телеграмм бота

в main.py читается токен из "assets/token.txt" и далее используют его для обьяекта bot

1. функция start(message) следит за введением слова "/start"
2. функция get_weather(message) принимает имя города, и выдает информацию по нему