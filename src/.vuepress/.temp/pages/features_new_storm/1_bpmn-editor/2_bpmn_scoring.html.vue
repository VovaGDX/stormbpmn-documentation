<template><div><h1 id="оценка-качества" tabindex="-1"><a class="header-anchor" href="#оценка-качества"><span>Оценка качества</span></a></h1>
<h2 id="качество-диаграмм-bpmn" tabindex="-1"><a class="header-anchor" href="#качество-диаграмм-bpmn"><span>Качество диаграмм BPMN</span></a></h2>
<p>Система предоставляет мощные средства для управления качеством ваших диаграмм в BPMN, создаваемых по вашему соглашению о моделировании. \ 
Качественные диаграммы гарантируют минимальное время на обсуждение формальных признаков описания и позволяют сразу переходить к сути.</p>
<p>Система предоставляет ~30 правил проверки BPMN, которые система проверяет автоматически при каждом сохранении.  <br>
<strong>Включение</strong>, отключение проверки осуществляется кнопкой в <a href="#%D0%B2%D0%B5%D1%80%D1%85%D0%BD%D0%B5%D0%B5-%D0%BC%D0%B5%D0%BD%D1%8E">верхнем меню</a>.</p>
<p>Выявленные ошибки бывают трех типов:</p>
<ol>
<li><strong>Фатальная ошибка</strong> (<em>красного цвета</em>) - серьёзное нарушение BPMN, обязательно исправить.</li>
<li><strong>Предупреждение</strong> (<em>желтого цвета</em>)- лучше исправить</li>
<li><strong>Рекомендация</strong> (<em>стикер синего цвета</em>) - рекомендуем моделировать лучше</li>
</ol>
<h2 id="проверка-ошибок" tabindex="-1"><a class="header-anchor" href="#проверка-ошибок"><span>Проверка ошибок</span></a></h2>
<p>Доступна в правом меню на одноименной вкладке
У каждой ошибки есть кнопка, центрующая холст на элемент жиаграммы с этой ошибкой.</p>
<p>Для отображения подсказок обо всех ошибках на схеме установите галочку &quot;Показывать ошибки на схеме&quot;</p>
<p><img src="@source/features_new_storm/1_bpmn-editor/error-check-1.png" alt="image"></p>
<h2 id="настроика-правил-проверки" tabindex="-1"><a class="header-anchor" href="#настроика-правил-проверки"><span>Настройка правил проверки</span></a></h2>
<div class="hint-container tip">
<p class="hint-container-title">Совет</p>
<p>Данная функция работает только на тарифе TEAM и выше.</p>
</div>
<p>Вы так же можете настроить трактовку каждого из правил уникальным образом для своей команды, а также:</p>
<ul>
<li>Настроить минимальную среднюю оценку, которую требует ваша команда. При нарушении этого показателя члены команды постоянно будут видеть уведомление о низком качестве процессов.</li>
<li>Указать минимальный процент указания (задействования) систем, ролей, документов на схеме.</li>
<li>Включить или отключить; изменить заголовок, описание, важность, дополнительную ссылку для каждого из правил.<br>
<img src="@source/features_new_storm/1_bpmn-editor/error-check-2.png" alt="image"></li>
</ul>
<p>Настраивается в разделе <RouteLink to="/features_new_storm/team-work/#%D0%BF%D1%80%D0%BE%D1%87%D0%B8%D0%B5-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B8%D0%BA%D0%B8-%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D1%8B">команды</RouteLink>.</p>
<h2 id="симуляция-токена" tabindex="-1"><a class="header-anchor" href="#симуляция-токена"><span>Симуляция токена</span></a></h2>
<p>Вы так же можете выполнить проверку проходимости процесса <strong>токеном</strong>. Посмотрите это видео, если не знаете, что это такое:</p>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Gfx5atU3YDY?si=ARC0B7o3i9K1DCey" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<p>Для включения симуляции токена:</p>
<ol>
<li>нажмите кнопку включения симуляции токена</li>
<li>приблизьтесь к любому стартовому событию и нажмите на символ Play для запуска токена</li>
<li>используйте переключатель на шлюзах, чтобы вести токена по выбранному направлению:<br>
<img src="@source/features_new_storm/1_bpmn-editor/token-simulation.png" alt="image"></li>
</ol>
<p>Видео с примером:</p>
<p><img src="@source/features_new_storm/1_bpmn-editor/token-simulation-rm.gif" alt="image"></p>
</div></template>


