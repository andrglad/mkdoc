```{=html}
<?xml version="1.0" encoding="utf-8" ?>
```
\<!DOCTYPE html>
```{=html}
<html xmlns="http://www.w3.org/1999/xhtml">
```
```{=html}
<head>
```
```{=html}
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
```
```{=html}
<meta name="generator" content="Adobe RoboHelp 2020" />
```
```{=html}
<title>
```
Автоматическое сканирование
```{=html}
</title>
```
```{=html}
<meta name="topic-status" content="Draft" />
```
`<link rel="stylesheet" type="text/css" href="assets/css/default.css" />`{=html}
```{=html}
</head>
```
```{=html}
<body>
```
```{=html}
<h3 data-list-level="3">
```
Автоматическое сканирование
```{=html}
</h3>
```
```{=html}
<p>
```
Для запуска сканирования в автоматическом режиме необходимо сделать
следующие шаги:
```{=html}
</p>
```
```{=html}
<ul class="Disc">
```
```{=html}
<li class="a0">
```
Выбрать и загрузить файл мобильного приложения с расширением *.apk или
*.ipa, для которого будет проводиться сканирование.`<br />`{=html}
`<strong>`{=html}Примечание:`</strong>`{=html} Если пакет с выбранным
именем и хеш суммой уже загружен, в целях экономии ресурсов его
повторная загрузка не производится, а используется файл, уже имеющийся
на сервере.
```{=html}
</li>
```
```{=html}
<li class="a0">
```
Выбрать проект из выпадающего списка существующих в системе
проектов.`<br />`{=html} `<strong>`{=html}Примечание:`</strong>`{=html}
Для выбора доступны либо проекты с незаполненным при создании полем
`<strong>`{=html}Имя пакета`</strong>`{=html} (см.
раздел `<a data-xref="{title}" href="Projects.htm">`{=html}Проекты`</a>`{=html}),
либо те, для которых в данном поле указан пакет, выбранный в предыдущем
шаге. Таким образом, не исключена ситуация, когда в данном поле будут
отсутствовать доступные для выбора элементы. В этом случае следует
создать новый проект с пустым полем `<strong>`{=html}Имя
пакета`</strong>`{=html} или, указав в нем соответствующий пакет.
```{=html}
</li>
```
```{=html}
<li class="a0">
```
Выбрать профиль сканирования из выпадающего списка.
```{=html}
</li>
```
```{=html}
<li class="a0">
```
Выбрать `<strong>`{=html}Автоматический`</strong>`{=html} режим
сканирования из выпадающего списка.
```{=html}
</li>
```
```{=html}
<li class="a0">
```
Во вновь появившемся внизу поле выбрать имя уже существующего в системе
тест кейса для запуска сканирования в автоматическом режиме.
```{=html}
</li>
```
```{=html}
<li class="a0">
```
Выбрать архитектуру, на которой будет проводиться сканирование. Отметим,
что в данном поле будет доступна для выбора только та архитектура, на
которой был записан тест кейс и которая активна в системе.
```{=html}
</li>
```
```{=html}
</ul>
```
```{=html}
<p class="a1" style="text-align: center">
```
`<img alt="Рисунок 43" src="assets/images/UG_files/image76.png" />`{=html}
```{=html}
</p>
```
```{=html}
<p class="a1">
```
По нажатию кнопки `<strong>`{=html}Запустить
сканирование`</strong>`{=html} происходит переход на страницу
`<strong>`{=html}Запуск сканирования`</strong>`{=html}. Будет отображена
страница с экраном устройства без возможности взаимодействия с ним.
Передача изображения с экрана устройства необходима для анализа работы
тест кейса. В ходе сканирования на экране устройства отображаются
следующие статусы:
```{=html}
</p>
```
```{=html}
<ul class="Disc">
```
```{=html}
<li class="a1">
```
`<strong>`{=html}Поиск свободного устройства`</strong>`{=html} ---
осуществляется поиск свободного сканирующего агента.
```{=html}
</li>
```
```{=html}
<li class="a1">
```
`<strong>`{=html}Запуск приложения`</strong>`{=html} --- выполняется
запуск приложения.
```{=html}
</li>
```
```{=html}
</ul>
```
```{=html}
<p class="a1" style="text-align: center">
```
`<img alt="Рисунок 59" src="assets/images/UG_files/image77.png" />`{=html}
```{=html}
</p>
```
```{=html}
<p class="a1">
```
Во время проведения автоматического сканирования также идет запись
видео, которое при завершении доступно на вкладке
`<strong>`{=html}Запись сканирования`</strong>`{=html} на странице
`<strong>`{=html}Результат сканирования`</strong>`{=html} для данного
теста.
```{=html}
</p>
```
```{=html}
<p class="a1">
```
При нажатии на кнопку `<strong>`{=html}К результатам
сканирований`</strong>`{=html} будет осуществлен переход к странице со
списком всех сканирований. При переходе на страницу
`<strong>`{=html}Результаты сканирований`</strong>`{=html} можно увидеть
новую строку, отображающую текущий результат автоматического
сканирования со статусом `<strong>`{=html}Запущен`</strong>`{=html}. При
нажатии на строку таблицы, когда соответствующее сканирование имеет
статус `<strong>`{=html}Создан`</strong>`{=html},
`<strong>`{=html}Запускается`</strong>`{=html} или
`<strong>`{=html}Запущен`</strong>`{=html} происходит возврат на
страницу с экраном устройства. После завершения сканирования приложения
статус примет значение `<strong>`{=html}Анализируется`</strong>`{=html}
на время обработки полученных результатов. Затем статус сканирования
поменяется на `<strong>`{=html}Успешно`</strong>`{=html} или
`<strong>`{=html}Ошибка`</strong>`{=html} в зависимости от результата.
Если нажать на строку, когда сканирование имеет статус
`<strong>`{=html}Анализируется`</strong>`{=html},
`<strong>`{=html}Успешно`</strong>`{=html} или
`<strong>`{=html}Ошибка`</strong>`{=html}, произойдет переход на
страницу `<strong>`{=html}Результат сканирования`</strong>`{=html}, см.
раздел
`<a data-xref="{title}" href="Rezultaty_skanirovanij.htm">`{=html}Результаты
сканирований`</a>`{=html}.
```{=html}
</p>
```
```{=html}
<p class="a1">
```
 
```{=html}
</p>
```
```{=html}
</body>
```
```{=html}
</html>
```