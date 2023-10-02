Для запуска:
1) Заполнить config.ini. Telegram api_id и api_hash можно создать [тут](https://my.telegram.org/auth)
2) Запустить скрипт get_users_and_messages.py указав нужное кол-во сообщений в параметре total_count_limit. На выходе получатся 2 json файла: channel_users.json - информация о всех пользователях чата, channel_messages.json - последние total_count_limit сообщений в чате.
3) Запустить ячейки в ноутбуке find_products.ipynb. На выходе получится файл product_requests.json с информацией о продуктах, которыми интересовались пользователи.
