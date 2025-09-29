# foodscan-ml

    Модели компьютерного зрения для распознавания еды.

## Структура
- `data/` - датасеты
- `notebooks/` - исследования
- `src/` - код для тренировки/инференса
- `models/` - веса (под DVC/S3, не в git)

## Быстрый старт
```bash
pip install -r requirements.txt
python src/train.py