<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img src="assets/banner-light.svg" alt="MrKreet1: Python, веб-разработка, вычислительная химия" width="100%">
</picture>

**Русский** · [English](README.en.md)

Пишу сервисы на Python и делаю сайты для бизнеса:

- веб-сервисы и панели управления на FastAPI и Streamlit;
- анализ данных: поиск аномалий, OCR, отчёты;
- многоязычные сайты с онлайн-записью и SEO-разметкой;
- автоматизация расчётов на Linux-серверах.

### Сервисы

| Проект | Что это | Стек |
|---|---|---|
| **ORCA Web** | Панель для запуска расчётов на VPS: очередь задач, live-логи, графики CPU/RAM, роли и защита от CSRF | FastAPI, SQLAlchemy, SQLite |
| **ORCA Cluster Service** | Сервис для серий расчётов в контейнере: сохраняет частичный прогресс, тестируется без самой ORCA | Python, Docker |

### Данные и машинное обучение

| Проект | Что это | Стек |
|---|---|---|
| **Поиск аномалий в бухгалтерии** | Находит подозрительные операции с помощью правил и Isolation Forest и объясняет каждое срабатывание | FastAPI, Streamlit, scikit-learn, PostgreSQL, Docker |
| **Сверка первичных документов** | Сопоставляет операции с документами: чтение PDF и сканов, OCR, оценка риска | Streamlit, pandas, scikit-learn, Tesseract |

### Сайты

| Проект | Что это | Стек |
|---|---|---|
| **Сайт медицинского центра** | Три языка (RU / KK / EN), поиск по 14 направлениям, страница врачей, запись через WhatsApp, SEO-разметка | HTML, CSS, JavaScript |

### Вычислительная химия

| Проект | Что это | Стек |
|---|---|---|
| [B6_ORCA_campaign](https://github.com/MrKreet1/B6_ORCA_campaign) | Поиск устойчивой геометрии кластера B6: 252 расчёта в скрининге, уточнение на PBE0-D4/def2-TZVP, проверка частот | Python, Bash, ORCA 6.1 |
| [B12_ORCA_workflow](https://github.com/MrKreet1/B12_ORCA_workflow) | Поиск структур кластера B12, от объёмных до планарных. Результаты пока предварительные | Python, Bash, ORCA 6.1 |

### Стек

**Языки:** Python, JavaScript, HTML, CSS, Bash<br>
**Веб:** FastAPI, SQLAlchemy, Jinja2, Streamlit<br>
**Данные:** pandas, scikit-learn, PostgreSQL, SQLite<br>
**Инфраструктура:** Docker, Linux VPS, GitHub Actions

<sub>На баннере рассчитанная геометрия кластера B6 из проекта B6_ORCA_campaign.</sub>
