﻿TransferInfo
============

Объект предназначен для редактирования сведений о передаче.


Свойства объекта
----------------

- **OperationInfo** (строка, чтение/запись, обязательно для заполнения, строка длиной не более 255 символов) - содержание операции

- **OperationType** (строка, чтение/запись, строка длиной не более 255 символов) - вид операции

- **TransferDate** (дата, чтение/запись) - дата отгрузки

- **TransferTextInfo** (строка, чтение/запись, обязательно для заполнения, строка длиной не более 1000 символов) - сведения о транспортировке и грузе

- **Carrier** (объект :doc:`ExtendedOrganizationInfo <ExtendedOrganizationInfo>`, чтение) - перевозчик

- **Employee** (объект :doc:`Employee <Employee>`, чтение) - работник организации продавца

- **OtherIssuer** (объект :doc:`OtherIssuer <OtherIssuer>`, чтение) - иное лицо

- **CreatedThingTransferDate** (дата, чтение/запись) - дата передачи вещи, изготовленной по договору

- **CreatedThingInfo** (строка, чтение/запись) - сведения о передаче вещи, изготовленной по договору

- **AdditionalInfoId** (строка, чтение) - информационное поле документа

- **TransferBases** (:doc:`коллекция <Collection>` объектов :doc:`TransferBase <TransferBase>`, чтение) - основание отгрузки

- **Waybills** (:doc:`коллекция <Collection>` объектов :doc:`Waybill <Waybill>`, чтение) - транспортная накладная


Методы объекта
--------------

-  :doc:`AddTransferBase <AddTransferBase>` - добавляет основание отгрузки

-  :doc:`AddWaybill <AddWaybill>` - добавляет транспортную накладную


.. toctree::
   :name: Auto
   :hidden:

   AddTransferBase <AddTransferBase>
   AddWaybill <AddWaybill>
   Employee <Employee>
   OtherIssuer <OtherIssuer>
   TransferBase <TransferBase>
   Waybill <Waybill>