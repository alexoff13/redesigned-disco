
# Протокол HTTP. Основы работы с консолью разработчика в браузере

## Цель:

Получить практические навыки работы с HTTP протоколом. На практике отметить заголовки присущие Request и Response с помощью консоли разработчика в браузере в различных web-ресурсах.

## Постановка задачи

Написать эссе, отражающее особенности как минимум 10 уникальных HTTP-заголовков для Request и Response.

---
[manjaro.org](www.manjaro.org)
```yaml
Server: nginx
Date: Sun, 03 Oct 2021 05:42:26 GMT
Content-Type: text/html
Content-Length: 30222
Last-Modified: Sun, 03 Oct 2021 05:30:02 GMT
Connection: keep-alive
ETag: "61593fda-760e"
Expires: Thu, 31 Dec 2037 23:55:55 GMT
Cache-Control: max-age=315360000
Strict-Transport-Security: max-age=31536000
Accept-Ranges: bytes
```
- `Server` - содержит список названий и версий веб-сервера и его компонентов. В данном случае это `nginx`
- `Date` - содержит дату генерации отклика
- `Content-Type` - содержит формат и способ представления сущности
- `Content-Length` - Размер содержимого сущности в октетах (байтах)
- `Last-Modified` - дата последней модификации сущности
- `Connection` - содержит сведения о проведении соединения ( в данном случае keep-alive(постоянное соединение))
- `Etag` - содержит тег (уникальный идентификатор) версии сущности, используемый при кэшировании
- `Expires` - Дата предполагаемого истечения срока актуальности сущности
- `Cache-Control` - содержит Основные директивы для управления кешированием. max-age определяет время (в секундах), в течение которого файл должен храниться в кэше
- `Accept-Ranges` - содержит перечень единиц измерения диапозонов
