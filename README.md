# cbr-rates

Pet-проект на Python: ETL-пайплайн курсов валют ЦБ РФ (Extract → Transform → Load).

## Что делает (план)

- **Extract** — скачивает курсы валют через API ЦБ
- **Transform** — чистит и приводит данные к таблице (pandas)
- **Load** — загружает в PostgreSQL

## Структура

- `src/cbr_rates/` — код пайплайна 
- `tests/` — тесты
- `.env.example` — шаблон настроек (скопировать в `.env`) 
