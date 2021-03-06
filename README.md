![rounded-in-photoretrica](https://user-images.githubusercontent.com/87089735/163038309-4610c9b0-f3d0-44eb-9034-40865a5c31ab.png)
# Установка

1. `pip install -r requirements.txt` библиотеки Python

2. Установка **ffmpeg** and **ffprobe**

    * [windows](https://drive.google.com/drive/folders/17a2wSKZajCx2_PzR6FqjGLTkyzgHvuVn?usp=sharing) скачать и переместить `ffmpeg.exe`, `ffprobe.exe` в **папку со скриптом**
    * linux `apt-get install ffmpeg`

3. Переменные
   * `OPEN_WEATHER_API_KEY` файл helpers.py (получить [api_key](https://openweathermap.org/))

   * `TELETHON_API_HASH` файл main.py (получить [api_hash](https://my.telegram.org/auth?to=apps))

   * `TELETHON_API_ID` файл main.py (получить можно так же как и api_hash)

   * `lat=49.98&lon=36.23` 50 строка в файле helpers.py, координаты города



# Функции

  * `scan [ответ на сообщение]` - сканировать сообщение
  * `scans [ответ на сообщение]` - молча сканировать сообщение
  * `gum [ответ на сообщение]` - вставить смайлики посреди сообщения
  * `cum [ответ на сообщение]` - кхалиси сообщение
  * `!w` - погода
  * `!s {запрос}` - поиск в Google
  * `!t` - имитация печатания в течение 5 минут
  * `ot` - случайная "отмазка"
  * `year` - информация о годе
  * `covg` - информация о ковидной диаграмме
  * `sat` - изображение со спутника
  * `tr [ответ на сообщение]` - перевод сообщения
  * `trl [ответ на сообщение]` - перевод сообщения на latin
  * `!m {20} {m/h/d}` - заглушить пользователя на {20} {m} минут
  * `🦔` - классный "мультик"
  * `loading` - анимация загрузки
  * `!f {текст}` - анимация текста
  * `!a {текст \ или [ответ на сообщение]}` - текст в голосовое сообщение
  * `!v {текст \ или [ответ на сообщение]}` - текст в видио сообщение
  * `!d {текст \ или [ответ на сообщение]}` - текст в голосовое сообщение с фильтром демон
  * `!inv {видео}` - видио в кружочек (для лучшего отправлять в соотношении сторон 1:1, меньше минуты)
  * `btc` - курс биткойн

## Полезная информация
* [Подробная инструкция установки на телефон (Android)](https://telegra.ph/Pomoshchnik-v-Telegram-08-17)
* [Оригинальнальный репозиторий](https://github.com/awitwicki/kodzu_thon)
* [awitwicki](https://github.com/awitwicki)
