---
order: 9
---

# FAQ - ответы на часто задаваемые вопросы

## Тип_элемента
### Как изменить тип (маркер) элемента?
1) встаньте на элемент
2) нажмите на кнопку изменения типа/вида (гаечный ключ)
3) выберите необходимый тип (маркер)

![image](FAQ-change_marker.png)


## Копирование
### Как скопировать элементы из одной схемы в другую?
Для копирования элементов и их вставку в другую модель (между вкладками браузера)
используйте кнопки верхнего меню 

![image](FAQ-copy_paste.png)


## Изменение цвета
### Как изменить цвет?
1) встаньте на элемент, чей цвет вы хотите изменить
2) в верхнем меню нажмите на кнопку изменения цвета
3) нажмите на окно выбора что меняете: заливку или границу
4) выберите что меняете: заливку или границу
5) нажмите на цвет, в который хотите покрасить

![image](FAQ-change-color.png)


## Выравнивание
### Как выровнять элементы по горизонтали?
### Как сделать стрелки одинаковой длины?

1) выделите несколько элементов
2) в появившемся справа контексном меню выберите кнопку выравнивания и откроется подменю с типами выравнивания
3) в подменю нажмите на выравнивание по горизонтали или по вертикали 

![image](FAQ-alignment.png)


## Восстановление
### Как восстановить процесс?

::: warning
Версионирование  - это часть платной подписки PersonalPro, TEAM или Enterprise. Без подписки её использование невозможно.
:::

Зайдите в меню Мои процессы или [Папки](#папки) и найдите искомую модель
1) нажмите на кнопку в виде трёх горизонтальных линий (находится в правом углу)
2) нажмите "Все версии"

![image](FAQ-versioning_1.png)

3) система откроет список всех версий, в котором вы сможете просмотреть каждую, нажав на соответствующую кнопку

![image](FAQ-versioning_2.png)

4) Выберите ту версию, из которой хотите восстановить свою модель. Нажмите в левом верхнем углу зеленую кнопку "Установить как текущую"

![image](FAQ-recovery.png)


## Cвязи
### создание связи
#### создание связи у call-activity
1) встаньте на элемент call-activity
2) нажмите на кнопку расширенных настроек (карандаш)
3) в поле "Название процесса" заполните название схемы call-activity 
   (начните набирать любое слово из его названия и система автоматически предложит вам схемы из имеющихся)

![image](FAQ-create_link_CA.png)

#### создание связи через отправку, получение месседжа
1) встаньте на элмент "отправка месседжа"
2) нажмите на кнопку расширенных настроек (карандаш)
3) нажмите кнопку "Создать событие отправки"
4) система присвоит название этому событию 

![image](FAQ-create_link_MT.png)

5) встаньте на элмент "получение месседжа"
6) нажмите на кнопку расширенных настроек (карандаш); 
7) поставьте курсов в поле "Событие"; система откроет список доступных событий отправки месседжа
8) выберите событие от которого получаем месседж
9) нажмите кнопку "Связать событие с выбранным"
10) система создаст линк связи

![image](FAQ-create_link_MC.png)


### удаление связи
1) перейдите на вкладку "Регламент"
2) выберите пункт "Связи процессов"
3) удалите связь, нажав кнопку справа от названия связанной схемы

![image](FAQ-delete_link.png)
