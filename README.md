# ⚰ Некрограм

> [!NOTE]
> Я ещё только **начал** разработку Некрограма, так-что ожидайте, что проект может тупо сдохнуть, потому-что я так хочу.

Некрограм — самый худший (возможно) форк Nekogram и Telegram, который даёт вам полезные функции и пока-что не следит за вами.

- Вебсайт: *скора*
- Телеграм-канал: *завтра*
- Баги: https://github.com/StupidKlad/Necrogram/issues

## Установка

Пока билдов нет, надо компилировать :(

## Докуменитация API и протоколов

Документация Telegram API: https://core.telegram.org/api

Документация протокола MTProto: https://core.telegram.org/mtproto

## Гайд на компиляцию и форк Некрограма

1. Скачай код ( `git clone https://github.com/StupidKlad/Necrogram.git` или тупо zip-файлик с Gitgub).
1. Заполни storeFile, storePassword, keyAlias, keyPassword в local.properties чтобы получить твой release.keystore
1. Иди в https://console.firebase.google.com/, создай два приложения Android с ID tw.nekomimi.nekogram и tw.nekomimi.nekogram.beta, включи общение через Firebase (firebase messaging) и скачай `google-services.json`, который должен быит скопирован в папку `TMessagesProj`.
1. Открой всё это в Android Studio (именно открой, <ins>**НЕ** ипортируй</ins>).
1. Заполни циферки и буковки в `TMessagesProj/src/main/java/tw/nekomimi/nekogram/Extra.java` – там есть ссылка с каждыми переменнами, показывая где и какую фигню они могут тебе показывать.
1. Поздровляем! Можно теперь компилировать и перенести твой замечательный проект на телефоны.

## Локализация

Пока-что Некрограм не поддерживает ваши западные языки, лишь поддержиаются украинский, русский и английский, так-что вся часть текста из Некрограма будет без перевода на других языках. Позже будет поддержка Crowdin, но сейчас мне лень. :trollface:
