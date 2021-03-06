﻿Соединение
==========

Объект DiadocConnection предназначен для управления логическим соединением с сервером Диадока.


Свойства объекта
----------------

- **Login** (строка, чтение) - имя пользователя, по которому произошла авторизация

- **AuthenticateType** (строка, чтение) - способ аутентификации

- **Certificate** (:doc:`PersonalCertificate <PersonalCertificate>`, чтение) - сертификат, по которому произошла авторизация

- **Token** (строка, чтение) - маркер авторизации в Диадок API

Свойство **AuthenticateType** принимает одно из следующих значений:
-  "Login" - возвращается в случае, когда при подключении к серверу Диадока использовались логин и пароль
-  "Certificate" - возвращается в случае, когда при подключении к серверу Диадока использовался сертификат


Методы объекта
--------------

-  :doc:`GetOrganizationList <GetOrganizationList>` - возвращает :doc:`коллекцию <Collection>` :doc:`организаций <Organization>`, к которым текущий пользователь имеет доступ

-  :doc:`GetOrganizationById <GetOrganizationById>` - возвращает :doc:`организацию <Organization>`, к которой текущий пользователь имеет доступ, по идентификатору организации

-  :doc:`CreateCloudSignTask <CreateCloudSignTask>` - возвращает :doc:`объект<CloudSignTask>`, с помощью которого можно подписать документы облачной подписью

-  :doc:`GetCloudCertificates <GetCloudCertificates>` - возвращает список облачных сертификатов, которые доступны текущему пользователю. Доступны только в случае, если соединение выполнено по логину и паролю.

-  :doc:`GetMyUser <GetMyUser>` - возвращает объект, содержащий информацию о текущем авторизованном пользователе


Объект можно получить, вызвав метод :doc:`CreateConnectionByLogin <CreateConnectionByLogin>` (авторизация по логину и паролю пользователя), либо вызвав метод :doc:`CreateConnectionByCertificate <CreateConnectionByCertificate>` (авторизация по сертификату с указанным отпечатком) :doc:`объекта интерфейса "Диадок" <Root-method>`.

.. toctree::
   :name: Auto
   :hidden:

   PersonalCertificate <PersonalCertificate>
   GetOrganizationList <GetOrganizationList>
   GetOrganizationById <GetOrganizationById>
   CreateCloudSignTask <CreateCloudSignTask>
   GetCloudCertificates <GetCloudCertificates>
   GetMyUser <GetMyUser>

