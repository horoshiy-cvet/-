Хороший Цветочный — сайт
========================

Структура:
  index.html    — главная страница
  catalog.html  — каталог букетов с корзиной и формой заказа
  style.css     — общие стили (подключается из catalog.html)
  img/          — фото букетов (bouquet1.jpg … bouquet9.jpg)

Настройка Telegram:
  1. Откройте catalog.html в блокноте
  2. Найдите строки (ближе к концу файла):
     var TELEGRAM_TOKEN = 'ВСТАВЬТЕ_ТОКЕН_СЮДА';
     var TELEGRAM_CHAT_ID = 'ВСТАВЬТЕ_CHAT_ID_СЮДА';
  3. Замените на свои значения:
     var TELEGRAM_TOKEN = '123456:ABC-DEF...';  (от @BotFather)
     var TELEGRAM_CHAT_ID = '123456789';          (от @userinfobot)
  4. Найдите своего бота в Telegram и нажмите /start
  5. Сделайте тестовый заказ — он придёт в Telegram

Загрузка на GitHub:
  1. Загрузите все файлы и папку img в репозиторий
  2. Settings → Pages → Branch: main → Save
  3. Сайт будет доступен по адресу логин.github.io/название-репозитория
