<img src="assets/hero-ru.svg" alt="MrKreet1: сервисы на Python, сайты и расчёты для химии" width="100%">

**Русский** / [English](README.en.md)

Пишу веб-сервисы и панели на FastAPI и Streamlit, ищу аномалии в данных, делаю многоязычные сайты и автоматизирую расчёты на Linux-серверах.

## Сервисы

<img align="left" width="320" src="assets/orca-web.svg" alt="Очередь задач и график нагрузки">

### ORCA Web

Панель для запуска расчётов на VPS. Очередь задач, live-логи, графики CPU и RAM, роли пользователей и защита от CSRF.

<sub>FastAPI, SQLAlchemy, SQLite</sub>

<br clear="left">

<img align="left" width="320" src="assets/cluster-service.svg" alt="Перебор параметров с отмеченной лучшей точкой">

### ORCA Cluster Service

Сервис для серий расчётов в контейнере. Сохраняет частичный прогресс и тестируется без самой ORCA.

<sub>Python, Docker</sub>

<br clear="left">

## Данные и машинное обучение

<img align="left" width="320" src="assets/anomalies.svg" alt="Облако обычных операций и три отмеченных выброса">

### Поиск аномалий в бухгалтерии

Находит подозрительные операции с помощью правил и Isolation Forest и объясняет каждое срабатывание.

<sub>FastAPI, Streamlit, scikit-learn, PostgreSQL, Docker</sub>

<br clear="left">

<img align="left" width="320" src="assets/documents.svg" alt="Операции, сопоставленные с документом, одна без пары">

### Сверка первичных документов

Сопоставляет операции с документами: читает PDF и сканы, распознаёт текст, оценивает риск.

<sub>Streamlit, pandas, scikit-learn, Tesseract</sub>

<br clear="left">

## Сайты

<img align="left" width="320" src="assets/website.svg" alt="Буквы Я, Ә и A: три языка сайта">

### Сайт медицинского центра

Русский, казахский и английский. Поиск по 14 направлениям, страница врачей, запись через WhatsApp, SEO-разметка.

<sub>HTML, CSS, JavaScript</sub>

<br clear="left">

## Вычислительная химия

<a href="https://github.com/MrKreet1/B6_ORCA_campaign"><img align="left" width="320" src="assets/b6.svg" alt="252 расчёта, 10 финальных, одна лучшая структура"></a>

### [B6_ORCA_campaign](https://github.com/MrKreet1/B6_ORCA_campaign)

Поиск устойчивой геометрии кластера B6: 252 расчёта в скрининге, 10 финальных на уровне PBE0-D4/def2-TZVP, проверка частот.

<sub>Python, Bash, ORCA 6.1</sub>

<br clear="left">

<a href="https://github.com/MrKreet1/B12_ORCA_workflow"><img align="left" width="320" src="assets/b12.svg" alt="Рассчитанная геометрия кластера B12"></a>

### [B12_ORCA_workflow](https://github.com/MrKreet1/B12_ORCA_workflow)

Поиск структур кластера B12, от объёмных до планарных. Результаты пока предварительные.

<sub>Python, Bash, ORCA 6.1</sub>

<br clear="left">

## Стек

**Языки:** Python, JavaScript, HTML, CSS, Bash<br>
**Веб:** FastAPI, SQLAlchemy, Jinja2, Streamlit<br>
**Данные:** pandas, scikit-learn, PostgreSQL, SQLite<br>
**Инфраструктура:** Docker, Linux VPS, GitHub Actions

<sub>Молекула на баннере движется по рассчитанной колебательной моде B6, под ней частоты из того же расчёта. Амплитуда увеличена.</sub>
