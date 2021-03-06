# Description EDF
---

### Documents
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**DateAt**|Дата создания документа|
|**Initiator**|Инициатор документа|
|**Description**|Описание документа|
|**ChangeAt**|Кто последний изменил документ|
|**ChangeDate**|Дата и время изменения|
|**NextAt**|Кто следущий должен подписать документ|
|**Contragent**|Контрагент|
|**Summ**|Сумма договора|
|**DueDate**|Срок окончания договора|
|**Relations**|Связанные документы|
|**Type**|Тип документа (см. справочник типов документа)|
|**Vidv|Вид документа (см. справочник видов документа)|
|**Predmet**|Предмет правочину|
|**SigDateIn**|Дата подписания договора - документа внутри|
|**SigDateOut**|Дата подписания договора - документа внешней компанией|
|**DogNumber**|Номер договора |
|**DogDate**|Дата договора |
|**Period**|Срок действия договора |
|**Note**|Примечание |
|**Status**|Текущий статус договора|
|**AddNum**|Номер дополнительного соглашения |
|**AddDate**|Дата дополнительного соглашения |
|**AddNote**|Описание |
|**Vutr**|Сатья расходов |
|**Sheduller**| Недельный график оплат|
|**Rasp**|Распредление оплат между отделами |
|**Place**|Место сбережения документа|


### Загруженные документы
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**Iddoc**|Id документа|
|**Name**|Имя файла|
|**Date**|Дата создания файла |
|**Size**|Размер файла |
|**Ext**|Расширение файла|


### Подписанты 
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**Iddoc**|Id документа|
|**Name**|Фамилия Имя|
|**Datesign**|Дата время подписи|
|**Note**|Примечание|

### Пользователи cистемы
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**Iddoc**|Фамилия|
|**Name**| Имя|
|**Company**|Компания|
|**Department**|Отдел|
|**Position**|Должность|
|**Card**|Карточка|
|**Extnumber**|Внутренний телефон|
|**Email**|Електронная почта|
|**Note**|Примечание|


## Контрагенты
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**Name**|Имя компании|
|**Edrpou**|Едрпоу|
|**Okpo**|ОКПО|
|**Contact**|Контактное лицо|
|**Telephone**|Телефон|
|**Mobile**|Телефон|
|**Email**|Електронная почта|
|**Status**|Статус|
|**Type**|Тип собственности|
|**Director**|Директор компании|
|**Accountant**|Бухгалтер компании|
|**Account**|Счет компании для оплаты|
|**Bank**|Банк|
|**Mfo**|Мфо банка|
|**City**|Город|
|**Address**|Адресс|
|**Street**|Улица|
|**Code**|Почтовый код|
|**Remark**|Примечание|
|**Owner**|Кто завел компанию|

### Log
|Field|Description|
|----|----------|
|**Id**|Уникальный код|
|**Date**|Дата опреации|
|**Name**|Наименование операции|
|**Type**|Тип операции W-warning, I-information, D-danger|
|**User**|Id пользователя совершившего операцию в системе|


### Right
### Matrix sign
### Department
### Position
### Branch
