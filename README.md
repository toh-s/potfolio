# 🧩 Портфолио

## 🚀 Корпоративный портал — разработанный мной масштабный SPA на Nuxt 3 (Vue 3 + Pinia, TypeScript)

**Описание:**  
Корпоративный сайт с более 39 страницами, динамическим контентом, блогом, сложной версткой и интерактивными SVG-анимациями. Контент, метатеги и данные для графиков поступают с Laravel backend через REST API; фронтенд собирает и рендерит данные, включая фрагменты путей изображений с переменными окружения.

**Ключевые особенности:**
- Ручные слайдеры с плавной микроанимацией и адаптацией под разные устройства;
- Динамические slug-страницы с возможностью добавления/удаления самих страниц и их редактирования, в том числе порядка секций через админку;
- Динамическая карта сайта, строящаяся скриптом на основе данных с сервера;
- Масштабируемый адаптивный UI-kit и собственные Sass-миксины для резинового макета (widescreen/desktop/tablet/mobile);
- SEO-настройки (тайтлы, метатеги, schema.org) управляются с админки;
- Сложные SVG-анимации, видео-слайдеры, калькулятор расчета стоимости аренды серверов, интеграция Яндекс.Карт с кастомной стилизацией, конструктор логотипа;
- Переиспользуемый компонент динамических SVG-стрелочек/линий: автоматическая отрисовка и перерисовка при ресайзе/скролле, вычисление координат DOM-элементов и приведение к единой системе отсчета с SVG, настраиваемые маркеры, цвет, ширина, анимация stroke-dash, поддержка нескольких линий (extraPaths) и адаптивное масштабирование под разные устройства;
- Санитизация всех входящих и исходящих данных, собственный компонент для корректной обработки и санитизации входящего текста.

**Стек:** Nuxt 3, Vue 3, Pinia, TypeScript, Sass, Swiper, Highcharts, editorjs-html, isomorphic-dompurify, REST API, Laravel backend  
**Примечание:** проект проходит последний этап тестирования перед продакшн-развертыванием.  
**Demo:** [link](https://e-3-xca2-2ba7xdodc-alealeanles-projects.vercel.app/)

---

## 📁 Медиа-менеджер (модуль CRM-системы) — комплексное файловое решение на Nuxt 3 + TypeScript

Разработал полнофункциональный медиа-менеджер с поддержкой изображений, видео и папочной структуры, реализовав сложную бизнес-логику управления файлами.

**Ключевые особенности:**
- Кастомные composables (useInventoryMedia) для API-взаимодействий  
- Паттерн приостановки выполнения кода с резолверами для синхронной работы с модальными окнами  
- Нативный Drag & Drop с визуальным ghost-элементом и множественным выделением  
- Групповые операции с файлами (удаление, перемещение, переименование)  
- Горячие клавиши для навигации (Escape, стрелки) и массовых действий  
- Реализация масштабирования и панорамирования изображений с границами  
- Многопоточная загрузка файлов с прогресс-трекингом  
- Оптимизированные re-renders через computed properties  
- Три режима отображения (список, сетка, крупная сетка)  
- Адаптивный дизайн с mobile-first подходом  
- Кастомные модальные окна и контекстные меню  
- Древовидная структура папок с хлебными крошками  
- Валидация типов файлов и размеров  
- Подтверждение деструктивных операций  
- Безопасная обработка файловых операций  

**Технический стек:** Vue 3, TypeScript, Composition API, Pinia, Sass, REST API  
**Website:** [link](https://lk.etour.center/)

---

## 🧠 Tests — платформа для создания и прохождения тестов (React + Redux-Saga, TypeScript)

**Stack:** React (Hooks), Redux Toolkit + Saga, TypeScript, React Router, Axios, SCSS Modules, Vite, Framer Motion, ESLint + Prettier, Git (Git Flow)

**Описание:**  
SPA для создания, редактирования и прохождения тестов с авторизацией и разграничением ролей (админ/пользователь). Основной фокус — чистая бизнес-логика, надежная архитектура и универсальные UI-компоненты.

**Функционал:**
- Авторизация/регистрация с проверкой токена, защищённые маршруты и редиректы;
- CRUD тестов, вопросов и ответов с drag-and-drop, модальные окна подтверждения;
- Асинхронные цепочки действий (создание/редактирование/удаление теста → вопросы → ответы);
- Главная страница с фильтрацией, сортировкой и пагинацией списка тестов;
- Прохождение тестов с расчетом результатов, кастомные хуки для управления состоянием;
- Интеграция с REST API через централизованный Axios, контроль ошибок через Redux-Saga;
- Типизированные Redux-модели и модульная SCSS-архитектура.

**Результат:** Production-ready SPA, демонстрирующая навыки: TypeScript, Redux-Saga, REST API, архитектура и проектирование UI-компонентов.  
**Примечание:** запуск возможен только через Firefox из-за настроек сервера (CORS).  
**GitHub:** [tests_Vite-React-TS](https://github.com/alealeanle/tests_Vite-React-TS) | **GitHub без TS:** [tests](https://github.com/alealeanle/tests) | **README:** [link](https://github.com/alealeanle/tests_Vite-React-TS/blob/develop/README.md)

---

## 👥 InternsList — SPA “Список стажёров” (React, Redux, LocalStorage)

**Stack:** React (Hooks), Redux Toolkit, React Router, SCSS Modules, LocalStorage, Git, Git Flow  
**Описание:** Управление списком стажёров с CRUD, фильтрацией, модальными окнами и роутингом. Состояние хранится в Redux Toolkit с синхронизацией в LocalStorage.  
**GitHub:** [interns_list](https://github.com/alealeanle/interns_list) | **Demo:** [interns_list](https://alealeanle.github.io/interns_list)

---

## ✅ ToDo List — React + Redux (LocalStorage)

**Stack:** React (Hooks), Redux Toolkit, SCSS Modules, LocalStorage, CRACO, Git  
**Описание:** SPA для управления списком задач с CRUD, фильтрацией и inline-редактированием. Состояние сохраняется между сессиями, архитектура модульная и оптимизированная.  
**GitHub:** [todo_react](https://github.com/alealeanle/todo_react) | **Demo:** [todo_react](https://alealeanle.github.io/todo_react)

---

## 🌍 YourTour — лендинг на Next.js (SSR + адаптив)

**Stack:** Next.js, SCSS Modules, clsx, UUID, Sharp, Google Fonts API  
**Описание:** Адаптивный лендинг туристического сервиса с серверным рендерингом, оптимизацией изображений, модульной архитектурой компонентов и SEO.  
**GitHub:** [yourtour](https://github.com/alealeanle/yourtour_next) | **Demo:** [yourtour](https://alealeanle.github.io/yourtour_next)

---

## 📝 ToDo List — на чистом JavaScript (ES6+, LocalStorage)

**Stack:** HTML5, SCSS, JavaScript (ES6+), LocalStorage  
**Описание:** Интерактивное приложение без фреймворков с CRUD, фильтрацией, inline-редактированием. Модульная архитектура, mini-store, SOLID-подход, адаптивная верстка.  
**GitHub:** [todo](https://github.com/alealeanle/todo) | **Demo:** [todo](https://alealeanle.github.io/todo)

---

## 🧭 YourTour — адаптивная Pixel Perfect вёрстка (Gulp + Webpack)

**Stack:** HTML5, SCSS, Gulp 4, Webpack 5, Autoprefixer, CleanCSS, Imagemin, BEM  
**Описание:** Pixel Perfect-вёрстка главной страницы туристического сервиса по макету Figma с полной адаптацией под 1920/1024/360 px. Сборка настроена вручную через Gulp + Webpack.  
**GitHub:** [yourtour](https://github.com/alealeanle/yourtour) | **Demo:** [yourtour_build](https://alealeanle.github.io/yourtour_build)
