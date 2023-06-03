VK API Client
=============
Kлиент для работы с VK API. Позволяет получать информацию о пользователях, их друзьях и альбомах. Реализованы 3 команды: вывод информации о пользователе, вывод списка друзей пользователя и вывод списка альбомов пользователя по его идентификатору. К каждому запросы можно также указать количество для отображения.

Особенности
-----------

*   Использует асинхронные запросы к VK API для эффективной работы.
*   Простой в использовании и настройке.

Требования
----------

*   Python ~=3.8

Настройка
---------

1.  Получите токен доступа из [инструкции VK API](https://dev.vk.com/api/access-token/getting-started).
2.  Поместите полученный токен в файл `settings.json` в корневой директории проекта.

Использование
-------------
Вы можете запустить утилиту с флагом -h, чтобы увидеть, как передаются параметры:
`python main.py -h`

Примеры использования клиента:

![image](https://github.com/Ananastyyy/VK-Api/assets/91197697/48cfff7b-d28a-48ee-bb0e-9d93ec809e89)

Автор
-------------
Проект реализован студенткой группы КН-201 Новиковой Анастасией.
