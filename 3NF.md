Третья нормальная форма: 

______


**Таблица: Пользователи**
ИД | Фамилия
--- | ---
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx111 | Лещук
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx112 | Иванов
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx113 | Петров

**Таблица: Документы**
ИД | Номер документа | Тип документа | Описание документа
--- | ---
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx1 | 2345123123 | ВУ | Водительское удостоверение
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx2 | 8976567567 | ВУ | Водительское удостоверение
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx3 | 1223987876 | СТС | Свидетельство о регистрации ТО
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx4 | 3451232212 | СТС | Свидетельство о регистрации ТО

**Таблица: Связь документа и пользователя**
ИД Пользователя | ИД Документа
--- | ---
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx111 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx1
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx112 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx2
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx112 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx3
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxx113 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx4

______


**Таблица: Документы**
ИД | Номер документа | ИД типа документа
--- | ---
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx1 | 2345123123 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx11
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx2 | 8976567567 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx11
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx3 | 1223987876 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx12
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxxx4 | 3451232212 | xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx12


**Таблица: Типы документов**
ИД | Номер документа
--- | ---
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx11 | ВУ | Водительское удостоверение
xxxxxxxx-xxxx-ххxx-хxxx-xxxxxxxxxx12 | СТС | Свидетельство о регистрации ТО