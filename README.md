# Sentiment Analysis of Russian Geo-Reviews (Cafes & Restaurants)

## Описание задачи

Данный проект решает задачу **классификации тональности текстовых отзывов** о заведениях общественного питания (кафе и рестораны) на русском языке. 

### Цель
Предсказать эмоциональную окраску отзыва на основе его текста:
- **Negative** (негативный) — рейтинг 1-2
- **Neutral** (нейтральный) — рейтинг 3  
- **Positive** (позитивный) — рейтинг 4-5

### Источник данных
- Датасет: [d0rj/geo-reviews-dataset-2023](https://huggingface.co/datasets/d0rj/geo-reviews-dataset-2023)
- Формат: Apache Parquet
- Язык: Русский

---

## Инструкция по запуску

### 1. Клонирование репозитория
```bash
git clone https://gitverse.ru/Chaizee/NLP_classificator_lab_test.git
cd NLP_classificator_lab_test