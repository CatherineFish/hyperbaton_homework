# Ваше задание

## Перед началом

1. Зарегистрируйтесь на GitHub, если вы ещё не.
2. Прочтите инструкцию и взгляните на картинку, чтобы точно всё понять. Если будут вопросы — задавайте в тикетах или в чате.

В инструкции намеренно нет конкретных команд, которые вам надо будет выполнить, или скриншотов с кнопками в интерфейсе. Это сделано для того, чтобы вы научились гуглить и решать проблемы самостоятельно.

Ещё пара советов перед началом:
1. Вам необязательно лезть в командную строку, чтобы выполнить это задание можно выполнить. Но учтите, что когда будете гуглить, то в ответах обычно будут решения именно для командной строки. Но это не бесполезная информация для вас: вы можете попытаться повторить эти действия в интерфейсе, т.к. там обычно используются такие же названия для всех основных действий (checkout, commit, push, log, reset и т.п.).

   Учтите, не всё можно сделать в интерфейсе. Например, в GitHub Desktop нельзя сделать reset.

   А если через интерфейс не получается, то можно попробовать скопировать команду и вставить в терминал. Но советую перед этим  почитать про эту команду. Это можно сделать в [документации](https://git-scm.com/docs), либо можете добавить в конце команды **через пробел** `-h` для краткой справки или `--help` для более подробной.
2. Если у вас Windows, то при установке командной строки выбирайте git bash. Не выбирайте CMD в качестве командной строки, намучаетесь с ним.

## Инструкция

1. Склонируйте этот репозиторий.
2. В репозитории есть ветка `template`, но последний коммит в ней бесполезен — всю информацию по ошибке удалили. Вам нужен предыдущий коммит.

   Вам надо:
   1. Выяснить SHA этого коммита. SHA — это хеш коммита, т.е. его идентификатор.
   2. Завести свою ветку так, чтобы в ней была та же версия файлов, что и в этом коммите. В качестве имени ветки укажите свой логин на github.

   **Застряли?** Переключитесь на ветку `template`, там есть файл с парой подсказок.
3. Посл этого у вас появится папка `homework` с файлом `template.txt`.
   На первой строчке в нём будет написано `<commit_sha>` и текст Lorem Ipsum.

   Вам надо:
   1. Переименовать этот файл заменив имя файла `template.txt` на ваш логин, вот так: `<login>.txt`.
   2. В самом файле заменить `<commit_sha>` на хеш, коммита, который вы выяснили ранее.
   3. Внесённые изменения не забывайте сохранять — т.е. коммитить. Вы можете сделать один коммит или несколько, как вам угодно.
4. Отправьте свои изменения на сервере, т.е. сделайте push.
6. Сделайте пулл-реквест из своей ветки в ветку `homework`. НЕ `master`, а `homework`!

![здесь должна быть инструкция](instruction.jpg)