﻿VerifyThatUserHasAccessToAnyBox
===============================

Метод :doc:`объекта интерфейса "Диадок". <Root-method>`

**Синтаксис**


VerifyThatUserHasAccessToAnyBox(<Thumbprint>).

**Параметры**


-  <Thumbprint> (строка, обязательный) - отпечаток сертификата

**Возвращаемое значение**


Булево.

**Описание**


Для указанного сертификата пытается найти пользователя Диадока и проверяет есть-ли у этого пользователя доступ в какой-либо ящик.
Возвращает "Истина", если есть доступ, "Ложь" в ином случае.
