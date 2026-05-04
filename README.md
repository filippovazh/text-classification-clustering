# Кластеризация и многоклассовая классификация на датасете 20Newsgroups

## Результаты

- **Лучшая модель:** LogisticRegression + TF‑IDF (F1-macro = 0.907)
- **Бинарная классификация space/religion:** F1 = 0.96
- **Кластеризация:** KMeans, ARI = 0.26

## Файлы

- `project.ipynb` – основной ноутбук
- `requirements.txt` – зависимости

### Сводная таблица результатов

| Векторизация | Классификатор | F1-macro |
|--------------|---------------|----------|
| BoW | LogisticRegression | 0.8779 |
| BoW | SVM | 0.8454 |
| **TF-IDF** | **LogisticRegression** | **0.9072** |
| TF-IDF | SVM | 0.9030 |
| Word2Vec | SVM | 0.8419 |

**Лучшая комбинация:** LogisticRegression + TF-IDF (F1-macro = 0.9072)

## Автор
Филиппова Евгения
