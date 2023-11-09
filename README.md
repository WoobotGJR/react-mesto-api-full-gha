[![Статус тестов](../../actions/workflows/tests.yml/badge.svg)](../../actions/workflows/tests.yml)

<h1 align="center">Дипломный проект: "Mesto" (backend)</h1>

<a name="summary">
  <details>
    <summary>Оглавление</summary>
    <ol>
      <li><a href="#project-description">Описание проекта</a></li>
      <li><a href="#project-installation">Эксплуатация проекта</a></li>
      <li><a href="#project-functionality">Функциональность проекта</a></li>
      <li><a href="#project-enhancement">Планы по улучшению</a></li>
    </ol>
  </details>
</a>

<a name="project-description"><h2>1. Описание проекта</h2></a>
Учебный проект Mesto - веб-приложение, которое представляет собой социальную сеть, в которой пользователи могут делиться посещёнными местами. Для создания проекта использовались express.js 

Проект доступен по ссылке:
<br>
frontend - https://woobotgjr.mesto.nomoredomainsicu.ru/
<br>
backend - https://api.woobotgjr.mesto.nomoredomainsicu.ru/
<br>
IP 158.160.35.223
<br>

<i>Проект был проверен опытными ревьюерами согласно чеклисту</i>

<a name="project-installation"><h2>2. Эксплуатация проекта</h2></a>

1. git clone https://github.com/WoobotGJR/react-mesto-api-full-gha - клонировать репозиторий
2. npm i - установить зависимости (dependencies)
3. npm run start - запустить приложение
4. npm run build - создать build приложения

<a name="functionality"><h2>3. Функциональность проекта</h2></a>

- CORS технология
- Защита запросов (например от межсайтового скриптинга)
- Ограничение лимита запросов на сервер с одного ip
- Валидация запросов, приходяших на сервер с помощью JOI
- Работа с базой данных (MongoDB) при помощи mongoose

<a name="enhancement"><h2>4. Планы по улучшению</h2></a>

- Переписать проект на node.js для лучшего понимания функциональности используемых инструментов
