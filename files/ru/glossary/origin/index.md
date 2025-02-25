---
title: Первичные данные
slug: Glossary/Origin
translation_of: Glossary/Origin
original_slug: Глоссарий/origin
---
Браузер отправляет серверу **первичные данные** - протокол, _хостинг, домен_, _порт соединения через_ {{Glossary("URL")}}. Два объекта одинаковые если протокол, хост, домен и порт одинаковые.

Некоторые данные могут не передаваться источником, для их получения необходимо использовать [CORS](/ru/docs/Glossary/CORS).

## Примеры первичных данных

| `http://example.com/app1/index.html` `http://example.com/app2/index.html` | данные протокола (`http`) и хостинга (`example.com`)          |
| ------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `http://Example.com:80` `http://example.com`                              | первичные данные для сервера- соединения HTTP, номер порта 80 |

## Пример других первичных данных

| `http://example.com/app1` `https://example.com/app2`                     | другие протоколы |
| ------------------------------------------------------------------------ | ---------------- |
| `http://example.com` `http://www.example.com` `http://myapp.example.com` | разные хостинги  |
| `http://example.com` `http://example.com:8080`                           | другой порт      |

## Больше информации

Смотрите [Same-origin policy](/ru/docs/Web/JavaScript/Same_origin_policy_for_JavaScript "/en-US/docs/Web/JavaScript/Same_origin_policy_for_JavaScript").
