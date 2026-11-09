# Практическая работа № 2 — вариант 01

**Студент:** Архангельский Данила Андреевич  
**Группа:** ИСТ-05  
**Вариант:** 01 — первые 15 заявок из `rental_01.csv`.

## Структура
- `llm_demo.ipynb` — выполнение запросов GigaChat, базовый промпт, Few-shot, JSON и оценка.
- `data/rental_01.csv` — исходные 15 заявок.
- `gold_fields_01.csv` — ручная эталонная разметка для структурированных полей.
- `reflection2.md` — рефлексия.

## Запуск
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -U jupyter ipykernel langchain-gigachat pandas pydantic python-dotenv
jupyter notebook
```
Создать файл `.env` рядом с ноутбуком:
```dotenv
GIGA_KEY=ВАШ_НОВЫЙ_API_КЛЮЧ
```
Не публиковать ключ и не добавлять `.env` в Git.

Откройте `llm_demo.ipynb`, выполните ячейки сверху вниз. Результаты и метрики должны быть получены реальным запуском модели; до запуска они намеренно не указаны.
