﻿FormalizedRejectionContent
==========================

Объект предназначен для работы с метаданными отказа в подписи формализованного документа 
и является производным объектом от :doc:`BaseContent <BaseContent>`.

Свойства объекта
----------------


- **Signer** (:doc:`Signer <Signer>`, чтение) - данные подписанта документа

- **Comment** (строка, чтение/запись) - комментарий

- **Type** (строка, чтение) - тип контента (возвращает строку "XmlSignatureRejection")


Методы отсутствуют
