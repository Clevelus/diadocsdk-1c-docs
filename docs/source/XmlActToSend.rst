﻿XmlActToSend
============

Объект представляет собой формализованный документ на отправку "Акт о выполнении работ" в формате приказа `ММВ-7-6/172@ <https://normativ.kontur.ru/document?moduleId=1&documentId=261859&rangeId=83282>`_ и является производным объектом от :doc:`DocumentToSend <DocumentToSend>`

Свойства объекта
----------------

- **Type** (строка, чтение) - тип документа (возвращает строку "XmlAcceptanceCertificate")

- **Comment** (строка, чтение/запись) - комментарий к документу

- **CustomDocumentId** (строка, чтение/запись) - внешний идентификатор документа

- **Content** (:doc:`AcceptanceCertificateSellerContent <AcceptanceCertificateSellerContent>`, чтение) - содержимое документа


Методы отсутствуют.