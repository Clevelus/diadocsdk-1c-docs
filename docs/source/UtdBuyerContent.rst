﻿UtdBuyerContent
================

Объект предназначен для работы с содержанием титула покупателя универсального передаточного документа в формате приказа `ММВ-7-15/155@ <https://normativ.kontur.ru/document?moduleId=1&documentId=271958>`_ или универсального корректировочного документа в формате приказа `ММВ-7-15/189@ <https://normativ.kontur.ru/document?moduleId=1&documentId=273231>`_ и является производным объектом от :doc:`BaseContent <BaseContent>`.

Свойства объекта
----------------

- **Type** (строка, чтение) - тип документа (возвращает строку "UniversalTransferDocumentBuyerTitle")

- **Creator** (строка, чтение/запись) - составитель файла обмена счета-фактуры (информации покупателя)

- **CreatorBase** (строка, чтение/запись) - основание, по которому экономический субъект является составителем файла обмена счета-фактуры

- **OperationCode** (строка, чтение/запись) - вид операции

- **OperationContent** (строка, чтение/запись) - содержание операции

- **AcceptanceDate** (дата, чтение/запись) - дата принятия товаров (результатов выполненных работ) или имущественных прав (подтверждения факта оказания услуг)

- **Employee** (:doc:`Employee <Employee>`, чтение) - работник организации покупателя

- **OtherIssuer** (:doc:`OtherIssuer <OtherIssuer>`, чтение) - иное лицо

- **AdditionalInfoId** (:doc:`AdditionalInfoId <AdditionalInfoId>`, чтение) - информационное поле документа

- **Signers** (:doc:`коллекция <Collection>` объектов :doc:`ExtendedSigner <ExtendedSigner>`, чтение) - подписанты документа. Для документа должен быть указан по крайней мере один подписант.


Методы объекта
--------------

-  :doc:`AddSigner <AddSigner-(UtdBuyerContent)>` - добавляет подписанта


.. toctree::
   :name: Auto
   :hidden:

   AddSigner <AddSigner-(UtdBuyerContent)>
   
