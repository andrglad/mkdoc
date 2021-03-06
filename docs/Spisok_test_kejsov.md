``
<?xml version="1.0" encoding="utf-8" ?>
```
\<!DOCTYPE html>
``
<html xmlns="http://www.w3.org/1999/xhtml">
```
``
<head>
```
``
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
```
``
<meta name="generator" content="Adobe RoboHelp 2020"/>
```
``
<title>
```
Тест кейсы
``
</title>
```
``
<meta name="topic-status" content="Draft"/>
```
`<link rel="stylesheet" type="text/css" href="assets/css/default.css"/>
``
</head>
```
``
<body>
```
``
<h2>
```
Тест кейсы
``
</h2>
```
``
<p data-list-level="2">
```
Работа с тест кейсами в системе производится через пункты основного меню
**Список тест кейсов** и
**Записать тест кейс**. Для начала работы
выберите пункт **Список тест кейсов**.
<img alt="Рисунок 219" height="499" src="/smimg/image82.png" width="30%"/>
На странице **Список тест кейсов**
отображены все записанные тест кейсы для различных проектов и
приложений.
<img alt="Изображение выглядит как текст, компьютер, снимок экрана, ноутбук
Автоматически созданное описание" height="550" src="/smimg/image83.png" width="100%"/>
В таблице представлены следующие элементы:

**Id** --- цифровой идентификатор тест
кейса.
**Имя** --- имя записанного тест кейса.
**Описание** --- подробное описание тест
кейса.
**Имя пакета** --- имя пакета
(приложения), для которого был записан тест кейс.
**Статус** --- статус записи тест кейса.
**Проект** --- проект, для которого
записывался тест кейс.
**Дата создания** --- время, в которое
был записан тест кейс.

На данной странице можно, используя расположенное справа раскрывающееся
меню, удалить тест кейс или скачать лог-файл для него.
Кроме этого, если в данный момент тест кейс записывается, используя
данное меню можно завершить или отменить запись.
При нажатии на строку таблицы, когда соответствующий тест кейс имеет
статус **Создан**,
**Запущен** или
**Запускается**, происходит переход на
страницу с экраном устройства.
<img alt="Изображение выглядит как текст, компьютер, снимок экрана, ноутбук
Автоматически созданное описание" src="/smimg/image84.png"/>
``
</p>
```
``
<h3 data-list-level="3">
```
Запись тест кейса
На странице **Записать тест кейс**
представлены необходимые поля для запуска записи нового тест кейса:

Кнопка **Выбрать файл** справа вверху
позволяет выбрать файл приложения ‎для загрузки. Пока файл приложения не
выбран, остальные поля недоступны для редактирования. `<br/>
**Примечание:** Если пакет с выбранным
именем и хеш суммой уже загружен, в целях экономии ресурсов его
повторная загрузка не производится, а используется файл, уже имеющийся
на сервере.
**Имя** --- имя создаваемого тест кейса.
**Описание** --- подробное описание тест
кейса.
**Проект** --- проект, для которого будет
записан тест кейс. `<br/>
**Примечание:** Для выбора доступны либо
проекты с незаполненным при создании полем **Имя
пакета** (см.
раздел `<a data-xref="{title}" href="Projects.htm">Проекты`</a>),
либо те, для которых в данном поле указан пакет, выбранный в предыдущем
шаге. Таким образом, не исключена ситуация, когда в данном поле будут
отсутствовать доступные для выбора элементы. В этом случае следует
создать новый проект с пустым полем **Имя
пакета** или, указав в нем соответствующий пакет.
**Архитектура** --- архитектура
устройства, на котором будет запущено приложение. Отметим, что в данном
поле будет доступна для выбора только соответствующая загруженному файлу
архитектура.
<img src="/img/image72.png"/>
После заполнения всех полей и нажатия на кнопку **Начать
запись** будет отображена страница с экраном устройства.
<img alt="Рисунок 51" height="893" src="/smimg/image86.png" width="100%"/>
После совершения необходимых действий и нажатия на кнопку
**Завершить запись** --- будет открыта
страница **Список тест кейсов** с новым
добавленным тест кейсом.
**Примечание:** Так как запускаемое для
сканирования приложение подвергается вмешательству, скорость его работы
может несколько снижаться. При записи тест кейсов рекомендуется делать
небольшую (2--3 секунды) задержку между действиями в интерфейсе
приложения.
``
</p>
```
``
<h3 data-list-level="3">
```
Редактирование / удаление тест кейса
Рассмотрим способы управления тест кейсами в системе. Редактирование
и/или удаление тест кейса может быть произведено на странице
**Список тест кейсов**.
Для редактирования тест кейса нажмите на строку таблицы, соответствующую
необходимому тест кейсу. В результате будет открыта страница просмотра и
редактирования тест кейса.
Доступные действия на экране --- просмотр записанного тест кейса и
редактирование параметров:

**Имя** тест кейса.
**Описание** тест кейса.
``
</li>
```
``
</ul>
```
``
<p class="a1" style="text-align: center">
```
`<img alt="Изображение выглядит как текст, снимок экрана, монитор
Автоматически созданное описание" src="/smimg/image87.png"/>
Также на этой странице можно просмотреть запись тест кейса и скачать его
лог-файл.
Для удаления тест кейса по нажатию кнопки
**Удалить** необходимо подтвердить или
отменить удаление тест кейса в окне **Удаление тест
кейса**.
<img  height="168" src="/smimg/image88.png" width="50%"/>
Кроме этого, тест кейс может быть удален непосредственно на странице
**Список тест кейсов** с помощью
расположенного справа от строки соответствующего тест кейса
раскрывающегося меню.
<img alt="Рисунок 37" height="439" src="/smimg/image89.png" style="cursor: nwse-resize;" width="100%"/>
``
</p>
```
``
<p class="a1" style="text-align: center">
```
 
``
</p>
```
``
</body>
```
``
</html>
```
