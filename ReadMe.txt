 Описание обновления
 
 Установка всех файлов Appx и AppxBundle из папки \Files   | v. 0.2
 Магазин Windows не нужен.
 
 Добавлен подхват файлов XML лицензий для установки с лицензией при необходимости, 
 если файл лицензии имеет начало названия как у приложения Appx или AppxBundle до символа подчёркивания: _
   Например:
   Приложение: Microsoft.WindowsStore_12002.1001.113.0_neutral___8wekyb3d8bbwe.AppxBundle
     Лицензия: Microsoft.WindowsStore_8wekyb3d8bbwe.xml
 
 И пропуск зависимых пакетов другой разрядности VCLib.Appx, .NET.Native и др.


Установка

 Для установки:
 
 1. На сайте https://www.microsoft.com/store/ ищем приложение, которое нас интересует, копируем ссылку или productId.
    Пример: https://www.microsoft.com/ru-ru/p/intel-graphics-command-center/9plfnlnt3g5g
    Тут ID: 9plfnlnt3g5g
 2. Идём на сайт https://store.rg-adguard.net/ и там вставляем ссылку или productId 
 3. Из списка файлов скачиваем само приложение, и всё что с этим приложением идёт под свою архитектуру или обоих разрядностей.
    Обычно это само приложение Appx или AppxBundle, если их несколько версий лучше установить все версии, они будут по очереди установлены, 
    и вместе с ним файлы VCLib.Appx и .NET.Native.Framework.Appx и .NET.Native.Runtime.Appx и др. (иногда необходимо установить все предоставленные версии).
 4. Складываем все файлы в папку \Files
 5. Запускаем Install_Appx_AppxBundle_RU.bat
 6. Установленные приложения первый раз запускаем с подключенным интернетом.

 Файлы .eappx, .eappxbundle и .BlockMap не нужны, независимо от их версий!
