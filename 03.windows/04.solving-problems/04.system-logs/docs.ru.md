---
title: 'Как получить файлы журнала Windows?'
taxonomy:
    category:
        - docs
visible: true
---

Для анализа и диагностики сложных проблем, связанных с работой AdGuard, службе поддержки могут понадобиться файлы журнала Windows. Журналы Windows содержат записи о системных событиях и ошибках за последнее время. Ниже представлена инструкция для получения и отправки этих файлов.

1. Откройте программу Просмотр событий (Event Viewer).

В Windows 10 нажмите на значок "Поиск" в панели задач, введите  в поисковой строке **eventvwr** и запустите первую найденную программу (щелкнув на ней мышью или нажав Enter).

![](eventvwr.png)

Если вы используете Windows 8 или 8.1, то проделайте следующие действия.

Перейдите в меню Поиск:

![](https://i.imgur.com/qJ10VR6.png)

Введите в поисковой строке eventvwr и запустите первую найденную программу (щелкнув на ней мышью или нажав Enter).

![](https://i.imgur.com/0KulZwA.png)

Если вы используете Windows 7 или Vista, нажмите на Пуск, введите в строке поиска eventvwr, и нажмите Enter.

![](https://i.imgur.com/jwOldkd.png)

2. Сохраните журналы приложений и системы в отдельные файлы

Окно программы Просмотр событий выглядит как показано ниже на картинке.

![](win_log_ru.png?cropResize=700,500)

Для сохранения необходимых нам файлов проделайте следующее.

2.1. Откройте журнал "Приложение" ("Просмотр событий (Локальный)" -> "Журналы Windows" -> "Приложение")

2.2. Щёлкните правой кнопкой мыши по пункту списка "Приложение" и в выпадающем меню выберите "Сохранить все события как ..."

2.3. Выберите место сохранения, введите название, нажмите "Сохранить". Выберите "Отображать сведения для следующих языков:". Напротив пункта "Русский" должен быть установлен флажок. Нажмите "Ок".

2.4. Откройте журнал "Система" ("Просмотр событий (Локальный)" -> "Журналы Windows" -> "Система").

2.5. Щёлкните правой кнопкой мыши по пункту меню "Система" и в выпадающем меню выберите "Сохранить все события как ..."

2.6. Выберите место сохранения, введите название, нажмите "Сохранить". Выберите "Отображать сведения для следующих языков:".  Напротив пункта "Русский" должен быть установлен флажок. Нажмите "Ок".

Полученные два файла пришлите, пожалуйста, службе [технической поддержки](mailto:support@adguard.com).