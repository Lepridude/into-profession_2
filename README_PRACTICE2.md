# Практическая работа № 2 — вариант 01

**Студент:** Архангельский Данила Андреевич  
**Группа:** ИСТ-05  
**Вариант:** 01

## Состав
- `llm_demo.ipynb` — ноутбук: базовый PromptTemplate, Few-shot, JSON-парсер, Pydantic и расчёт метрик.
- `data/rental_01.csv` — 15 исходных заявок.
- `gold_fields_01.csv` — ручная эталонная разметка дополнительных полей.
- `reflection2.md` — рефлексия.

## Запуск
Установить Python 3.10+, создать виртуальное окружение и установить:
```bash
python -m venv .venv
source .venv/bin/activate
pip install -U jupyter ipykernel langchain-gigachat pandas pydantic python-dotenv
jupyter notebook
```
Создать локальный `.env` рядом с ноутбуком:
```dotenv
GIGA_KEY=ВАШ_НОВЫЙ_КЛЮЧ
```
Не добавлять `.env` в Git.

Метрики появятся после фактического запуска ячеек с GigaChat. В репозитории нет API-ключа.
