---
order: 3
---
# Редактор оргструктуры

Stormbpmn позволяет моделировать оргструктуру предприятия, соединять ее с ролями на бизнес-процессах и конкретными сотрудниками. Такая связь может однозначно ответить, что именно делает конкретная должность или даже сотрудник в бизнес-процессах.  
![image](orgchart-1.png)

Решение такой задачи базируется на нескольких тезисах:

- У задачи может быть только 1 роль
- Должность может выполнять сколько угодно ролей
- Роль может выполняться каким угодно количеством должностей
- Сотрудник может быть назначен на любое количество должностей
- Сотрудник не может быть назначен на роль напрямую

::: warning

Оргструктура работает на подписке TEAM и выше.
:::

![image](orgchart-2.png)

## Меню и редактор

Создать огрструктуру можно по [ссылке](https://stormbpmn.com/app/team/orgchart).

::: tip
Сейчас реализована возможность создать только одну структуру на команду.
:::

Верхнее меню позволяет:

- Скачать оргструктуру в .PNG.
- Выровнять оргструктуру.
- Найти на схеме конкретную должность.
- Найти на схеме должности, участвующие в конкретном процессе.

![image](orgchart-3.png)

Карточка элемента архитектуры позволяет:

1. Увидеть количество процессов, где используется должность.
2. Посмотреть, сколько человек назначено на должность.
3. Открыть редактирование карточки.
4. Удалить карточку.
5. Добавить подчинённый элемент.
6. Присоединить подчинённый элемент.

## Карточка должности

Карточка должности позволяет:

1. Сменить цвет, тип, название, описание должности.
2. Управлять привязкой ролей к должности.
3. Управлять привязкой сотрудников к должности.
   ![image](orgchart-4.png)

## Заполнение из CSV

Содержимое оргструктуры может быть загружено из CSV файла ([шаблон](https://docs.google.com/spreadsheets/d/1xaq8ZSEKHGS-ZYH3HQtlab87TFVcUuf3tzNdHuCf4uQ/edit#gid=0)) в разделе команды:

![image](orgchart-5.png)

