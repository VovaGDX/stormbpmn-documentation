<template><div><h1 id="элементы-архитектуры" tabindex="-1"><a class="header-anchor" href="#элементы-архитектуры"><span>Элементы архитектуры</span></a></h1>
<p>Элементы архитектуры предназначены для указания ресурсов и объектов, используемых для выполнения задачи.</p>
<p>Основные их типы:</p>
<ul>
<li><strong>Система</strong> - программное обеспечение, используемое для выполнения пользовательской или сервисной задачи;</li>
<li><strong>Документ</strong> - артефакт, содержащий контекст бизнес-процесса;</li>
<li><strong>Коммуникация</strong> - отражает способ, канал коммуникации;</li>
<li><strong>Действие</strong> - используют для типизации действий, абстрактных задач и ручных операций.</li>
</ul>
<p>Дополнительные типы: клиент; сущность; прочее.</p>
<p>Элементы архитектуры являются обогащённой альтернативой таким элементам BPMN, как объект данных и артефакты.
Они позволяют не перегружать диаграмму, а включение их отображения раскрывает информацию о процессе и улучшает его понимание.</p>
<div class="hint-container tip">
<p class="hint-container-title">Совет</p>
<p>Элементы архитектуры образуют справочник. Созданные Элементы можно использовать в нескольких диаграммах.</p>
</div>
<h2 id="создание-элемента-архитектуры" tabindex="-1"><a class="header-anchor" href="#создание-элемента-архитектуры"><span>Создание Элемента архитектуры</span></a></h2>
<div class="hint-container warning">
<p class="hint-container-title">Примечание</p>
<p>Создавать Элементы архитектуры  может только <strong>администратор команды</strong>. Элементы архитектуры - это часть платной подписки TEAM или Enterprise. Без подписки их использование невозможно.</p>
</div>
<p>При создании Элемента архитектуры можно указать:</p>
<ul>
<li><strong>Внешний ID</strong> - идентификатор элемента в другой системе. Будет полезно, если вы загружаете элементы из других систем.</li>
<li><strong>Ссылка во внешней системе</strong> - ссылка на внешнюю систему. Будет красиво отображаться, если заполнена. Поддерживается плейсхолдер.</li>
<li><strong>Статус</strong> - отображет информацию о том, в каком состоянии находится Элемент архитектуры.</li>
<li><strong>Цвет</strong> - используется в оверлеях.</li>
</ul>
<h3 id="с-интерфеиса-процесса-в-контекстом-меню" tabindex="-1"><a class="header-anchor" href="#с-интерфеиса-процесса-в-контекстом-меню"><span>С интерфейса процесса в <RouteLink to="/features/1_bpmn-editor.html#%D0%BA%D0%BE%D0%BD%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BD%D0%BE%D0%B5-%D0%BC%D0%B5%D0%BD%D1%8E">контекстом меню</RouteLink></span></a></h3>
<p><img src="@source/features/create-element_architecture.png" alt="image"></p>
<h3 id="с-интерфеиса-процесса-в-описании-задач" tabindex="-1"><a class="header-anchor" href="#с-интерфеиса-процесса-в-описании-задач"><span>С интерфейса процесса в <RouteLink to="/features/1_bpmn-editor.html#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B7%D0%B0%D0%B4%D0%B0%D1%87">описании задач</RouteLink></span></a></h3>
<p><img src="@source/features/create-element_architecture-2.png" alt="image"></p>
<h3 id="c-отдельного-представления" tabindex="-1"><a class="header-anchor" href="#c-отдельного-представления"><span>C отдельного представления</span></a></h3>
<p>По <a href="https://stormbpmn.com/app/team/assets/" target="_blank" rel="noopener noreferrer">ссылке<ExternalLinkIcon/></a>:<br>
<img src="@source/features/create-element_architecture-3.png" alt="image"></p>
<h3 id="c-помощью-загрузки-из-csv" tabindex="-1"><a class="header-anchor" href="#c-помощью-загрузки-из-csv"><span>C помощью загрузки из .csv</span></a></h3>
<p>Разделитель - запятая, кодировка - UTF8.
По <a href="https://stormbpmn.com/app/team" target="_blank" rel="noopener noreferrer">ссылке<ExternalLinkIcon/></a>:<br>
<img src="@source/features/create-element_architecture-4.png" alt="image"></p>
<h3 id="c-помощью-rest-api" tabindex="-1"><a class="header-anchor" href="#c-помощью-rest-api"><span>C помощью <RouteLink to="/enterprise/rest-api.html#%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B0-%D0%B8-%D0%B8%D0%BB%D0%B8-%D0%BE%D0%B1%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%BE%D0%B2-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D1%8B">REST API</RouteLink></span></a></h3>
<h2 id="редактирование-элементов-архитектуры" tabindex="-1"><a class="header-anchor" href="#редактирование-элементов-архитектуры"><span>Редактирование Элементов архитектуры</span></a></h2>
<p>Редактирование Элементов архитектуры возможно в контекстом меню или с отдельного представления по <a href="https://stormbpmn.com/app/team/assets" target="_blank" rel="noopener noreferrer">ссылке<ExternalLinkIcon/></a>.</p>
<h2 id="удаление-элементов-архитектуры" tabindex="-1"><a class="header-anchor" href="#удаление-элементов-архитектуры"><span>Удаление Элементов архитектуры</span></a></h2>
<p>Удалить Элемент архитектуры можно только с отдельного представления по <a href="https://stormbpmn.com/app/team/assets" target="_blank" rel="noopener noreferrer">ссылке<ExternalLinkIcon/></a>.</p>
<p><img src="@source/features/delete-element_architecture.png" alt="image"></p>
<div class="hint-container caution">
<p class="hint-container-title">Предупреждение</p>
<p>Если Элемент архитектуры использован в диаграмме, то система не позволит его удалить и покажет перечень диаграмм в которых он использован. Отвяжите его перед удалением.
<img src="@source/features/list_chart-delete-element_architecture.png" alt="image"></p>
</div>
<h2 id="кастомные-элементы-архитектуры" tabindex="-1"><a class="header-anchor" href="#кастомные-элементы-архитектуры"><span>Кастомные элементы архитектуры</span></a></h2>
<p>Система позволяет вводить свои типы элементов архитектуры. Типичной практикой является создание своих справочников:</p>
<ul>
<li>Метрик</li>
<li>Функциональных разрывов</li>
<li>Проектов</li>
<li>Рисков</li>
<li>Типа операций</li>
</ul>
<p>Это отличный способ описывать те аспекты процессов, которые интересуют именно вашу организацию.</p>
<h3 id="создание-определении-элементов-архитектуры" tabindex="-1"><a class="header-anchor" href="#создание-определении-элементов-архитектуры"><span>Создание определений элементов архитектуры</span></a></h3>
<p>По ссылке <a href="https://stormbpmn.com/app/team/assets" target="_blank" rel="noopener noreferrer">https://stormbpmn.com/app/team/assets<ExternalLinkIcon/></a> нажмите определение элементов:</p>
<p><img src="@source/features/custom-ea-1.png" alt="alt text"></p>
<p>При создании укажите:</p>
<ul>
<li>Иконка - будет использоваться в оверлееях.</li>
<li>Имя - название справочника.</li>
<li>Код - используется в API и при генерации документов.</li>
<li>Описание.</li>
<li>Связывается с - укажите к чему может быть применим справочник.</li>
</ul>
<p><img src="@source/features/custom-ea-2.png" alt="alt text"></p>
<h3 id="создание-элемента-по-кастомному-справочнику" tabindex="-1"><a class="header-anchor" href="#создание-элемента-по-кастомному-справочнику"><span>Создание элемента по кастомному справочнику</span></a></h3>
<p>Не откличается о создания ЭА, просто выберите тип:</p>
<p><img src="@source/features/custom-ea-3.png" alt="alt text"></p>
<h3 id="использование-в-практике" tabindex="-1"><a class="header-anchor" href="#использование-в-практике"><span>Использование в практике</span></a></h3>
<p>Не отличается от использования обычных ЭА.</p>
</div></template>


