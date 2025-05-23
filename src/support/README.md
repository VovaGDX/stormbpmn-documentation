---
dir:
  order: -4
  link: true
  text: Тех.поддержка
  collapsible: false
index: true
icon: "handshake-angle"
order: -4
---

# Тех.поддержка и администрирование

В данном разделе описаны варианты поддержки пользователей облачной версии и Enterprise-версии.

Для пользователей Enterprise-версии описаны традиционные задачи технического администрирования системы.

## Каналы поддержки

Мы предоставляем 4 канала поддержки:

- Чат в приложении (кружочек в правой нижней части). Работает только в облачной версии.
- Почта **help@stormbpmn.com** 
- Портал [техподдержки](https://stormbpmn.portal.happydesk.ru/login). Способ для просмотра ваших заявок и статусов. На портале отдельная регистрация от облачной версии.
- [@Stormbpmn_bot](https://t.me/stormbpmn_bot) - бот в телеграмм

## Информация для устранения неисправности

Для быстрого устранения неисправности приложите в свою заявку:

- Версию браузера _(если дело касается пользовательской ошибки)_
- Версию образа контейнера (мы записывает ее в теги контейнера)
- [HAR-архив](https://yandex.cloud/ru/docs/support/create-har), записанный в момент неисправности _(если дело касается пользовательской ошибки)_
- Актуальный лог контейнера
- Описание сценария воспроизведения ошибки
- Электронную почту пользователя _(если дело касается пользовательской ошибки)_
- Ссылку на диаграмму _(если дело касается конкретной диаграммы)_

### Как посмотреть версию\теги образа контейнера
Если вы используете docker:
```
docker ps -a --format '{{.ID}} {{.Image}} {{.Names}}'
```
Если у вас k8s, то вы и сами знаете.

### Как собрать актуальный лог контейнера 

```
docker logs <container_name_or_id>
```

Для вывода в файл:
```
docker logs my-container > logs.txt
```

## SLA

| #   | Название                                   | Team          | Enterprise     |
| --- | ------------------------------------------ | --------------- | -------------- |
| 1   | Время реагирования                         | 5 рабочих дней  | 16 часов       |
| 2   | Время устранения критической неисправности | 30 рабочих дней | 15 рабочих дней |

- **Рабочее время**: с 11:00 до 20:00 по МСК (GMT+3), выходные и будни по ТК РФ.
- **Критическая неисправность**: невозможность применять инструмент для 100% пользователей.

Для прочих типов неисправностей SLA для устранения не предоставляется.

::: info
Это SLA по-умолчанию, входящий в базовую поставку лицензий.

Для команд >50 пользователей (облако) или Enterprise он может быть пересмотрен в рамках отдельного соглашения.
:::
