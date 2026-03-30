---
title: Windows 10/11 && Microsoft Office 365 - Установка и активация
description: Файлы и инструкции для скачивания, установки и активации Windows 10/11 и Microsoft Office 365
date: 2025-12-12 20:00:00+0300
image: cover.jpg
categories:
    - Полезности
---

# Windows 10/11

## Файлы

Скачать **Windows 10 ISO**: [скачать](https://www.comss.ru/download/page.php?id=2572)

Скачать **Windows 11 ISO**: [скачать](https://www.comss.ru/download/page.php?id=9234)

## Установка

Установить образ на флешку можно при помощи программы **Rufus**: [скачать](https://github.com/pbatard/rufus/releases/download/v4.13/rufus-4.13p.exe) | [сайт](https://rufus.ie/ru/)

## Активация Windows

1. Запускаем **PowerShell** (**Терминал** в Windows 11) от имени Администратора

2. Вставляем команду и нажимаем <kbd>Enter</kbd>:
```
irm https://get.activated.win | iex
```

3. Выбираем `HWID`



# Microsoft Office 365

## Файлы

Скачать **Microsoft Office 365**: [скачать](https://officecdn.microsoft.com/db/492350f6-3a01-4f97-b9c0-c7c6ddf67d60/media/ru-ru/O365ProPlusRetail.img)

Скачать архив для кастомной установки: [скачать](https://github.com/abbodi1406/WHD/raw/master/scripts/YAOCTRI_v11.2.zip)

## Установка

1. Скачать `O365ProPlusRetail.img` по ссылке выше, для кастомной (настройки) установки скачиваем заодно и архив `YAOCTRI_v11.2.zip` выше

    1.1. Если устраивает установка по умолчанию (без выбора, что ставить и куда), то нажимаем дважды по `O365ProPlusRetail.img` и запускаем `setup.exe`

2. Для кастомной установки - нажимаем дважды по `O365ProPlusRetail.img` или <kbd>ПКМ</kbd> -> <kbd>Подключить</kbd>

3. Распаковываем архив `YAOCTRI_v11.2.zip` и запускаем `YAOCTRIR_Configurator.cmd` от имени Администратора и настраиваем установку, в зависимости от ваших требований

## Активация **Microsoft Office 365**

Активировать **Microsoft Office 365** можно также во время установки через `YAOCTRIR_Configurator.cmd`, выбрав соответствующий пункт

Если не активировали во время установки или выполняли установку по умолчанию, то инструкция ниже

1. Запускаем **PowerShell** (**Терминал** в Windows 11) от имени Администратора

2. Вставляем команду и нажимаем <kbd>Enter</kbd>:
```
irm https://get.activated.win | iex
```

3. Выбираем `OHook`

