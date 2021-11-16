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
Основные понятия
```{=html}
</title>
```
```{=html}
<meta name="topic-status" content="Draft" />
```
`<link rel="stylesheet" type="text/css" href="assets/css/default.css" />`{=html}
```{=html}
<meta name="rh-authors" content="" />
```
```{=html}
</head>
```
```{=html}
<body>
```
```{=html}
<h1>
```
Основные понятия
```{=html}
</h1>
```
```{=html}
<p>
```
`<strong>`{=html}Проект (Project)`</strong>`{=html} --- верхнеуровневая
сущность, внутри которой определяются настройки и профили сканирования
для конкретного приложения. Каждый проект однозначно связывается со
сканируемым приложением (пакетом) либо на этапе создания, либо при
первом сканировании. На уровне проекта могут быть переопределены правила
сканирования, которые будут применяться только для этого проекта. Имя
проекта уникально в рамках системы.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Профиль (Profile)`</strong>`{=html} --- профиль
сканирования, включающий в себя настройки каждого модуля, список
проверяемых стандартов и требований информационной безопасности. Имя
профиля уникально в рамках проекта, к которому он относится.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Модуль (Module)`</strong>`{=html} --- компоненты для
сбора различной информации во время сканирования приложения на
устройстве (мониторинг системного журнала, использование файлов,
операции с базой данных и т. д.). Каждый модуль имеет свои уникальные
настройки и может быть зависимым от результатов других модулей.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Тест кейсы (Test cases)`</strong>`{=html} ---
записанный сценарий работы пользователя с приложением. Включает в себя
все действия пользователя (нажатия, передаваемый текст, любые
взаимодействия с интерфейсом приложения и т. д.). Тест кейс
привязывается к конкретному проекту и может быть воспроизведен только в
рамках него. Тест кейс запускается только если имя приложения
(package_id) при запуске совпадает с именем приложения, для которого был
записан тест кейс.`<br />`{=html}
`<strong>`{=html}Сканирование`</strong>`{=html} --- процесс анализа, во
время которого пользователь вручную или система по записанным ранее тест
кейсам взаимодействуют с приложением. Во время сканирования система
Stingray собирает всю доступную информацию о работе приложения и затем
проводит поиск уязвимостей и проверку на соответствие стандартам
безопасности.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Метод сканирования/запуска`</strong>`{=html} --- cпособ
сканирования, определяющий, запускать ли записанный ранее тест кейс или
ожидать ручных операций с приложением. Возможные варианты:
```{=html}
</p>
```
```{=html}
<ul class="Disc">
```
```{=html}
<li>
```
`<strong>`{=html}Автоматический`</strong>`{=html} --- запускает
сканирование и запускает выбранный тест кейс.
```{=html}
</li>
```
```{=html}
<li>
```
`<strong>`{=html}Ручной`</strong>`{=html} --- после запуска сканирования
необходимо вручную совершать операции с запущенным приложением.
```{=html}
</li>
```
```{=html}
</ul>
```
```{=html}
<p>
```
`<strong>`{=html}Имя пакета (Package name)`</strong>`{=html} --- имя
пакета сканируемого приложения. 
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Правила анализа (Rules)`</strong>`{=html} --- правила
анализа, по которым происходит поиск части уязвимостей. Правила
представляют собой набор строк или регулярных выражений, которые
необходимо искать в собранных данных. Для удобства добавление правил
оформлено в виде конструктора, в котором необходимо указать какую строку
искать, в результатах каких модулей и в каком месте данных (XML-тэг,
значение в JSON и т. д.).
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Требование (Requirement)`</strong>`{=html} ---
требования информационной безопасности, на соответствие которому будет
проверено приложение. С требованием соотносятся определенные типы
дефектов, при нахождении которых в приложении требование будет считаться
не выполненным. Требования могут быть сгруппированы в виде категорий или
относиться напрямую к стандартам.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Категория (Category)`</strong>`{=html} --- группировка
требований информационной безопасности по различным признакам.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Стандарт (Standard)`</strong>`{=html} --- совокупность
требований или категорий требований информационной безопасности, на
соответствие которым может проверяться приложение. Стандарты могут быть
как общемировые, так и внутренние стандарты компании.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Дефекты (Defects)`</strong>`{=html} --- выявленные во
время сканирования дефекты приложения или, по-другому, уязвимости. У
каждого дефекта есть тип, описание и рекомендации по устранению.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Собранные данные (Collected Data)`</strong>`{=html} ---
вся собранная информация о работе приложения за время сканирования.
Данные разделены по модулям, каждый из которых отвечает за сбор
определенной информации. Эти данные так же можно скачать и
проанализировать локально, при желании.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}CI/CD (Continuous Integration / Continuous
Delivery)`</strong>`{=html} --- системы для непрерывной интеграции и
непрерывных поставок приложения. Примерами таких систем могут быть
Jenkins, Teamcity, GitLab CI.
```{=html}
</p>
```
```{=html}
<p>
```
`<strong>`{=html}Эмулятор (Emulator)`</strong>`{=html} --- виртуальный
эмулятор имитирующее реальное устройство Android. Характеризуется
различной архитектурой и версией операционной системы.
```{=html}
</p>
```
```{=html}
<p>
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