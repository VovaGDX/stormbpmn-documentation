<template><div><h1 id="_1-урок-bpm-bpmn-bpms" tabindex="-1"><a class="header-anchor" href="#_1-урок-bpm-bpmn-bpms"><span>1 урок: BPM, BPMN, BPMS</span></a></h1>
<p>Привет!</p>
<p>Буквы почти одинаковые, а смысл разный. Сегодня разберем, что это значит и какое вам до этого дело.</p>
<h2 id="bpm-business-process-management" tabindex="-1"><a class="header-anchor" href="#bpm-business-process-management"><span>BPM, Business Process Management</span></a></h2>
<p>Это способ вести бизнес, когда вы заставляете организацию работать в четкой последовательности и так, чтобы сотрудники внутри не спихивали ответственность друг на друга, а взаимодействовали.</p>
<p>Официальное определение <a href="https://abpmp.org.ru/resource/bpm-glossary/#bpm" target="_blank" rel="noopener noreferrer">тут<ExternalLinkIcon/></a>.</p>
<h3 id="bpm-и-проекты" tabindex="-1"><a class="header-anchor" href="#bpm-и-проекты"><span>BPM и проекты</span></a></h3>
<p>Управление процессами похоже на управление проектами - есть ответственные за результат, прописаны регламенты, выделены сотрудники, есть специальный софт.</p>
<p>Отличие заключается в результатах: по проекту вы делаете что-то уникальное и одно, а по процессам - много и одинаковое.</p>
<h3 id="bpm-и-функциональныи-подход" tabindex="-1"><a class="header-anchor" href="#bpm-и-функциональныи-подход"><span>BPM и функциональный подход</span></a></h3>
<p>В функциональном подходе организация делится на части, которые делают строго определенную работу. Вы такое могли видеть, если работали в крупных организациях - когда в соседний отдел нужно писать служебку, чтобы вам починили мышку.</p>
<p>В BPM организация делится на части, которые тоже делают строго определенную работу, но уже в рамках последовательности работ, которая выстроена вокруг клиента.</p>
<p>За прохождение заявки клиента через всю организацию отвечает один человек.<br>
<img src="@source/bpmn/1_lesson_1.png" alt="image"></p>
<p>BPM сконцентрирован на операционной части бизнеса - доставках, счетах, заявках. На том, что делается каждый день в большом количестве.</p>
<p>Управление процессами скорее поможет сэкономить деньги, чем начать зарабатывать их больше.</p>
<div class="hint-container tip">
<p class="hint-container-title">Совет</p>
<p>Подходы не противоречат друг другу, а работают вместе - функциональный подход помогает развивать компетенции сотрудников, проекты позволяют достигать новых вершин к конкретным срокам, а процессы - качественно выполнять много сложной работы.</p>
</div>
<h2 id="bpmn-business-process-model-and-notation" tabindex="-1"><a class="header-anchor" href="#bpmn-business-process-model-and-notation"><span>BPMN, Business Process Model and Notation</span></a></h2>
<p>Это набор значков и правил их применения. Значки использую для описания процессов. BPMN придумали как способ общения между айтишниками и бизнесом.</p>
<p>Если схема процесса составлена с помощью BPMN, то она в таком же виде может быть скомпилирована программой. Таким образом бизнес видит, как работает процесс и программа на его основе, а ИТ быстрее может вносить изменения.</p>
<p><img src="@source/bpmn/1_lesson_2.png" alt="image"></p>
<p>BPMN - это инструмент, одного его знания не хватит для успешного управления процессами. Как наличие фотоаппарата не делает вас фотографом.</p>
<p>BPMN визуально выглядит простым. Кажется, что его очень легко освоить. Но если не пройти обучение, то схемы будут плохие, и основные преимущества BPMN потеряются.</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/AlE3G3IMcqA?si=trNXByxk1jy2Xm8U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<h2 id="bpms-business-process-management-suite" tabindex="-1"><a class="header-anchor" href="#bpms-business-process-management-suite"><span>BPMS, Business Process Management Suite</span></a></h2>
<p>Это класс программ, в которых с помощью BPMN можно моделировать процессы, компилировать схемы в приложения и постоянно эти приложения улучшать.</p>
<p>Например, у вас есть процесс &quot;Заказ пиццы&quot; из трёх задач:</p>
<ul>
<li>
<p>Выбрать пиццу;</p>
</li>
<li>
<p>Согласовать с начальником;</p>
</li>
<li>
<p>Оплатить.</p>
</li>
</ul>
<p>Для такого процесса BPMS:</p>
<ul>
<li>Создаст веб-страницу с авторизацией;</li>
<li>Нарисует кнопку &quot;заказать пиццу&quot;;</li>
<li>Сверстает визуальную форму для задачи &quot;указать параметры пиццы&quot;;</li>
<li>Отправит письмо ответственному за задачу &quot;Согласовать покупку&quot;;</li>
<li>Передаст данные из формы &quot;указать параметры пиццы&quot; в форму &quot;Согласовать пиццу&quot;;</li>
<li>Учтёт количество задач для каждого пользователя;</li>
<li>Учтёт количество заказов пиццы;</li>
<li>Посчитает временные интервалы - сколько времени занимает процессы и выгрузит его в Excel;</li>
<li>Много других вещей: генерирует регламенты к процессам; уведомляет начальников, если кто-то не успевает вовремя; показывает визуально, где процесс и т.д.</li>
</ul>
<p>Часто бывает, что BPMS используют исключительно как софт, без цельного подхода к BPM.</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/TkB7OA5VGXg?si=G0ZkDZj9v8BPImcx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<h2 id="_3-термина-вместе" tabindex="-1"><a class="header-anchor" href="#_3-термина-вместе"><span>3 термина вместе</span></a></h2>
<p>Вот так соотносятся термины в мире бизнеса:</p>
<p><img src="@source/bpmn/1_lesson_3.png" alt="image"></p>
<p>Можно прекрасно управлять процессами в Excel, использовать BPMN, чтобы рисовать схемы движения документов, программировать в BPMS складской учёт.</p>
<p>Но эффективнее применять всё вместе.</p>
<h2 id="факультатив" tabindex="-1"><a class="header-anchor" href="#факультатив"><span>Факультатив</span></a></h2>
<iframe width="560" height="315" src="https://www.youtube.com/embed/qp6vv_M8hBY?si=5zFyoNjI4Rt3AkdY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div></template>


