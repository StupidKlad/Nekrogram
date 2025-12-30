# ⚰ Некрограм

> [!NOTE]
> Я ещё только **начал** разработку Некрограма, так-что ожидайте, что проект может тупо сдохнуть, потому-что я так хочу.

Некрограм — самый худший (возможно) форк Nekogram и Telegram, который даёт вам полезные функции и пока-что не следит за вами.

- Вебсайт: *скора*
- Телеграм-канал: *завтра*

## Докуменитация API и протоколов

Документация Telegram API: https://core.telegram.org/api

Документация протокола MTProto: https://core.telegram.org/mtproto

## Гайд на компиляцию своими ручками для чайников

1. Download the Nekogram source code ( `git clone https://github.com/Nekogram/Nekogram.git` )
1. Fill out storeFile, storePassword, keyAlias, keyPassword in local.properties to access your release.keystore
1. Go to https://console.firebase.google.com/, create two android apps with application IDs tw.nekomimi.nekogram and tw.nekomimi.nekogram.beta, turn on firebase messaging and download `google-services.json`, which should be copied into `TMessagesProj` folder.
1. Open the project in the Studio (note that it should be opened, NOT imported).
1. Fill out values in `TMessagesProj/src/main/java/tw/nekomimi/nekogram/Extra.java` – there’s a link for each of the variables showing where and which data to obtain.
1. You are ready to compile Nekogram.

## Локализация

Пока-что Некрограм не поддерживает ваши западные языки, лишь поддержиаются украинский, русский и английский, так-что вся часть текста из Некрограма будет без перевода на других языках. Позже будет поддержка Crowdin, но сейчас мне лень. :trollface:
