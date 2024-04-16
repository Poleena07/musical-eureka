# Мой Теллеграмм бот со стихами

Для запуска бота необходимо в файл config.py добавить свой токен от бота. затем выполнить команту:

```
py now.py
```
или
```
python now.py
```
# Бот
* Написан на языке програмирования **_Python_**
* Используется библеотека **_telebot_**
* Используется декоратор **_Сallback_query_handlers_**
* Используется два вида кнопок: **URL-кнопка** и **Switch-кнопки**
* Работа с файлами

# Язык програмирования
Язык прогромирования - **Python**. Он крайне популярен и распространён, изучается в школах и уневерситетах. У этого языка много библеотек и очень удобен для изучения.
Так, что выбор остановился именно на нём.
# Telebot
Для написания Телеграмм - бота есть две библеотеки: _telebot_ и _aiogram_. Так как telebot по сравнению с aiogramе можно самстаятельно изучить,
ведь про  aiogram в интернете довольно мало информации. С учетом всего был установлен telebot, вбив встроенную консоль:
```
pip install pyTelegramBotAPI
```
# Сallback_query_handlers
**`Декоратор`** _Callback_query_handlers_ в Python используется для обработки _callback_data_, который передаётся при нажатии на определённую кнопку. Он создаёт анонимную функцию внутри декоратора, которая принимает callback и возвращает True, если callback пуст. Затем создаётся функция callback_message, которая принимает callback и обрабатывает переданное значение.

_**`Декортор`**_ в Python — это функция, которая принимает другую функцию в качестве аргумента, добавляет к ней некоторую дополнительную функциональность и возвращает функцию с изменённым поведением. Они используются для изменения работы существующих функций или классов, добавления новых возможностей и обеспечения безопасности.
# Кнопки
**`URL`-кнопка** — это специальная кнопка, которая используется для перехода пользователя по определённому веб-адресу. Она проста в использовании и позволяет пользователю быстро перейти на нужный сайт.
**`Switch`**-кнопка — это переключатель, который используется для выбора одного из нескольких вариантов действий. Она полезна, когда пользователю нужно выбрать один из нескольких вариантов, например, в меню или настройках.
# Файлы
Работа с файлами в Python включает открытие, чтение, запись и закрытие файлов. Для этого используются функции open(), read(), write() и close().
Для открытия файла используется функция open(), которая принимает два аргумента: имя файла и режим доступа к файлу (чтение, запись или добавление). Если режим доступа не указан, файл открывается в режиме чтения.

    После завершения работы с файлом его необходимо закрыть с помощью функции close(). Это освобождает системные ресурсы и гарантирует корректное завершение работы с файлом.
