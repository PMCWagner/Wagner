## БОТ БАЙТЕР | BITE BOT

<picture>
  <img width=50% height=50% alt="" src="https://i.imgur.com/kGGLSwb.jpeg">
</picture>
<br>
Подпишись на наш телеграм https://t.me/holey_moon
<br>

### УСТАНОВКА
Устанавливаем модуль pyrogram
```
pip install pyrogram
```
### НАСТРОЙКА

Настройка параметров в cfg.py:

api_id и api_hash - данные от приложения телеграм. Их можно найти в интернете или создать самому приложение

chance - шанс ответа. Если стоит 0 будет отвечать на каждое сообщение, если 2 - через каждое и т.д.

my_id - айди аккаунта телеграм, на котором будет работать бот

ignoreusers - игнор пользователей по их айди. Айди вписывать через запятую внутри квадратных скобок

chats - игнор чатов. Айди чатов также нужно записывать через запятую внутри скобок

reactions - список реакций, который бот рандомно выбирает и ставит

reply_only - 1 - постоянно отвечать на сообщения 2 - отвечать по желанию 0 - не отвечать

answer_only_on_replies - ответ только на реплаи

send_pm = False - не отвечать в личные сообщения True - отвечать

chat_leave = False - не выходить с чатов и ставить реакции True - выходить с чатов


### ИСПОЛЬЗОВАНИЕ
Перед запуском нужно заполнить данными фразами файл words.txt
Каждая фраза должна начинаться с новой строки

### ЗАПУСК
```
python bot.py
```
После запуска вам остается только смотреть и наслаждаться смешными ответами пользователей
