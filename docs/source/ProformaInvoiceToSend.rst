﻿ProformaInvoiceToSend
=====================

Объект представляет собой неформализованный документ на отправку "Счет на оплату" и является производным объектом от :doc:`DocumentToSend <DocumentToSend>`

Свойства объекта
----------------

- **Type** (строка, чтение) - тип документа (возвращает строку "NonformalizedProforma")

- **Comment** (строка, чтение/запись) - комментарий к документу

- **CustomDocumentId** (строка, чтение/запись) - внешний идентификатор документа

- **FileName** (строка, чтение/запись) - имя файла вложения

- **DocumentDate** (дата, чтение/запись, обязательно для заполнения) - дата документа

- **DocumentNumber** (строка, чтение/запись, строка длиной не более 256 символов) - номер документа

- **Total** (число с плавающей точкой, чтение/запись) - сумма с учетом НДС

- **Vat** (число с плавающей точкой, чтение/запись) - сумма НДС

- **Grounds** (строка, чтение/запись) - основание документа


Методы отсутствуют.