# ifmo-2019
# Планы контента дисциплин


Серверные веб-технологии и системы управления контентом

см. https://github.com/GossJS/ifmo-2018
---


### Исследование экосистем веб-языков и веб-технологий


| #  | Тема  |  Контент |
|---|---|---|
| 1 | Исследование стандарта ECMAScript | Эволюция стандарта ECMAScript. Предложения tc39.  Развивающиеся возможности последних версий стандарта. Транспиляция. Основные характеристики синтаксиса JavaSript.  Термы. Переменные, операторы, литералы и выражения. Запуск программ. Динамическая типизация, неявные преобразования типов. Области видимости, блоки. Браузерный (клиентский), внебраузерный (серверный) и изоморфный JavaScript. 
| 2 | Модульность и менеджмент зависимостей | Нативные модули ECMAScript в браузере и вне браузера. Импорт и экспорт. Модули и пакеты. Менеджеры пакетов npm и yarn. Инициализация проекта. Файл манифеста. Девелоперские зависимости. Зависимости с точки зрения управления версиями. Папка node_modules. Сборка (интеграция) проекта с помощью бандлера (webpack). Инструменты командной строки (CLI). Публикация (развёртывание) проекта.
| 3 | Функциональный стиль и его поддержка в экосистеме JavaScript. Асинхронное программирование. | Лябмды (безымянные функции, стрелки), «самовыполняющиеся» функции. Замыкания, каррирование.  Обработка событий. Слушатели событий, коллбэки, ад обратных вызовов. AJAX/CORS. Асинхронное программирование и неблокирующий код. Промисы. Генераторы. Ожидание промисов (async/await). Особенности JavaScript:  функции как данные (объекты первого класса), «немедленно выполняющиеся функции» (IIFE).
| 4 | Объекты и классы JavaScript. Сравнение с массивами и строками. Метапрограммирование. | Глобальный объект и объект window. Обычные и необычные объекты.  Множества и ассоциативные массивы. Строки (и шаблоны строк) и массивы. Мутабельность и ссылочность. Литеральные объекты. Создание объекта с прототипом и без. Контекст this. Собственные свойства объекта. Символы и элементы метапрограммирования. Классы и конструкторы. Классы и модули. Декораторы. Байндинг, пользовательские события и сообщения.
| 5 | Исследование интерфейсов прикладного программирования JavaScript (API) | Взаимодействие с хостом и с DOM. Веб-воркеры. Подписка и публикация событий. Потоки. Canvas и WebGL API. Анимация. Audio/video API. Device API (Bluetooth, Vibration). Notification API.  Интерфейсы хранения данных: WebStorage, IndexedDB. Интерфейсы геолокации.
| 6 | Библиотеки и фреймворки экосистемы JavaScript | Различия библиотек и фреймворков. Императивный и декларативный подходы. Шаблонизация в браузерном JavaScript. Внедрение зависимостей. Паттерны. Реактивное программирование.


---

### Управление электронным обучением на веб-платформе

| #  | Тема  |  Контент |
|---|---|---|
| 1 | Терминология, структура и качество информационных ресурсов и инструментов электронного обучения |    Терминология электронных информационно-образовательных сред (ЭИОС). Электронные курсы, онлайн-курсы и MOOC как компоненты ЭИОС. Электронные образовательные ресурсы и средства управления электронной информационно-образовательной средой. Открытые и закрытые модели ЭИОС. Оценка качества информационных ресурсов электронного обучения (онлайн-курсов). Инструменты электронного обучения на платформе Node.js. Развёртывание, запуск и настройка  системы управления информационными ресурсами на платформе Node.js.
| 2 | Развёртывание технологической платформы электронной информационно-образовательной среды | Функции и типичная структура LMS. Рекомендации по выбору LMS. Сходства и различия в сравнении с CMS. Терминология LMS (роли, аккаунты, курсы, темы, блоки, тесты, пакеты, плагины и др.). Слайдовая, скроллинговая и другие модели содержимого. Конструкторы целей обучения и компетенций.  Сравнительный анализ LMS (Moodle, edX). Роли, аккаунты и профили. Способы аутентификации и  регистрации пользователей. Структурные единицы содержания. Роли внутри курсов, способы записи пользователей на курс; группы и потоки. Варианты организации содержания в рамках курса (Learning aequence). Режимы редактирования и просмотра. Виды содержимого внутри курса: статические ресурсы и динамическое интерактивные элементы. Отчуждаемый контент в форме IMS-пакетов и SCORM-пакетов. Оценка деятельности, тесты и банк вопросов, проектирование вопросов (на примере фасетов), журнал оценок. Развёртывание в контейнере. Облачные решения (PaaS). Подключение и настройка визуального редактора. Импорт и отображения медиа, математических формул, анимации. Подключение вебинаров. Управление плагинами. Резервное копирование и восстановление содержания, повторное использование компонентов контента.
| 3. | Разработка отчуждаемого контента для повторного использования |     Стандарт SCORM. Файл манифеста. Понятие организации. Внутренняя организация пакета. SCORM API и обмен данными с LMS. Встраивание пакета. Хранение информации о пользователе и баллах. Запись данных в журнал оценок. Способы разработки пакетов. Генерация пакетов с помощью инструментов электронного обучения. Использование визуальных редакторов. Подходы к организации хранения пакетов.
| 4. | Управление электронным обучением на базе систем управления контентом | Подходы к использованию CMS в качестве системы управления электронным обучением. Расширение терминологии CMS. Реализация LMS на основе CMS WordPress. Плагин LifterLMS. Конструктор курсов. Управление метками, категориями, планами доступа, медиаконтентом. Эволюция стандартов электронного обучения: от SCORM к Tin Can (xAPI) и LRS.
 


---

### Проектирование и анализ языков веб-решений

| #  | Тема  |  Контент |
|---|---|---|
| 1 | Языки описания веб-проектов и конфигураций веб-решений |   Инфраструктура проекта современного веб-приложения. Инфраструктура коллективной среды разработки веб-проекта. Конфигурирование веб-приложения и его зависимостей. Файл манифеста проекта. JavaScript Object Notation (JSON), BSON. Разработка JSON-схемы и валидация документа относительно схемы. Языки конфигурирования YAML, TOML
| 2 | Языки, основанные на XML и CSS |  Обобщённый язык разметки XML. Формальная грамматика XML. Document Type Definition и XML-схемы. Разработка XML-схемы и валидация документа относительно схемы. Язык математической разметки MathML. Язык разметки векторной графики SVG. Язык стилей XSL. Разработка предметного языка разметки на основе XML. Языки препроцессоров CSS и шаблонизации (SASS, SCSS, Pug). Сборка проекта с использованием WebPack.
| 3 | Проектирование веб-ресурсов с помощью предметно-ориентированных языков | Понятие предметно-ориентированного языка и  языково-ориентированного программирования. Автоматизация развёртывания веб-решения с помощью сценариев на предметно-ориентированных языках. Технология контейнеризации Docker, создание конфигураций развёртывания приложений с помощью Docker Compose. Развёртывание приложений с помощью Vagrant
| 4 | Стандарты веб-языков, их синтаксис и развитие | Развитие стандарта ECMAScript. ES2015, ES2017, ES.Next. Технология WebAssembly. Языки, альтернативные и сопутствующие языку JavaScript. Языки Dart, Rust и Kotlin, их сравнительный анализ и компиляция в байт-код на стороне клиента.   


---

