﻿InvoiceCorrectionToSend
=======================

Объект представляет собой формализованный документ на отправку "Корректировочный счет-фактура" в формате приказа `ММВ-7-6/93@ <https://normativ.kontur.ru/document?moduleId=1&documentId=249567&rangeId=83296>`_ и является производным объектом от :doc:`DocumentToSend <DocumentToSend>`

Свойства объекта
----------------

- **Type** (строка, чтение) - тип документа (возвращает строку "InvoiceCorrection")

- **Comment** (строка, чтение/запись) - комментарий к документу

- **CustomDocumentId** (строка, чтение/запись) - внешний идентификатор документа

- **Content** (:doc:`InvoiceCorrectionContent <InvoiceCorrectionContent>`, чтение) - содержимое документа


Методы отсутствуют.