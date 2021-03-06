﻿TovTorgBuyerContent
====================

Объект предназначен для работы с содержанием титула покупателя формализованного документа "ТОРГ-12" в формате приказа `ММВ-7-10/551@ <https://normativ.kontur.ru/document?moduleId=1&documentId=265102>`_ и является производным объектом от :doc:`BaseContent <BaseContent>`.

Свойства объекта
----------------

- **Type** (строка, чтение) - тип документа (возвращает строку "TovTorgBuyerTitle")

- **DocumentCreator** (строка, чтение/запись) - составитель файла обмена (информации покупателя)

- **DocumentCreatorBase** (строка, чтение/запись) - основание, по которому экономический субъект является составителем файла обмена

- **OperationCode** (строка, чтение/запись) - вид операции

- **OperationContent** (строка, чтение/запись) - содержание операции

- **AcceptanceDate** (дата, чтение/запись) - дата принятия товаров (результатов выполненных работ) или имущественных прав (подтверждения факта оказания услуг)

- **Employee** (:doc:`Employee <Employee>`, чтение) - работник организации покупателя

- **OtherIssuer** (:doc:`OtherIssuer <OtherIssuer>`, чтение) - иное лицо

- **AdditionalInfo** (:doc:`AdditionalInfoId <AdditionalInfoId>`, чтение) - информационное поле документа

- **Signers** (:doc:`коллекция <Collection>` объектов :doc:`ExtendedSigner <ExtendedSigner>`, чтение) - подписанты документа. Для документа должен быть указан по крайней мере один подписант.

Методы объекта
--------------

-  :doc:`AddSigner <AddSigner-(TovTorgBuyerContent)>` - добавляет подписанта

.. toctree::
   :name: Auto
   :hidden:

   AddSigner <AddSigner-(TovTorgBuyerContent)>
