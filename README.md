# hh-ru-auto-resume-raising
### Описание
Программа для автоматического подъема резюме на [HeadHunter](https://hh.ru/) 
каждые 4 часа. Альтернатива платной услуге 
[Продвижение.LITE](https://hh.ru/applicant/services/payment?from=landing&package=lite) 
от HeadHunter.  

### Инструкция
Переименовать и заполнить все данные
```
mv .env_pub .env
```
Установить зависимости
```
python3 -m pip install -r requirements.txt
```
Запустить
```
python3 bot.py
```
### Функционал
1) Авторизоваться
   1) Создать токены авторизации
   2) Обновить токены авторизации
2) Обновить список резюме
   1) Получить данные с hh.ru
3) Список резюме
   1) Локальный список
4) Добавить или обновить
   1) Добавить резюме в распсиание
   2) Обновить текущее резюме в расписании
5) Удалить
   1) Удалить резюме из расписания
6) Профиль
   1) Данные из .env (номер телефона, пароль, прокси, состояние уведомлений, часовой пояс)
7) Расписание
   1) Список резюме и время последнего и следующего поднятия
8) Вкл/выкл уведомления
   1) Меняет состояние уведомлений
