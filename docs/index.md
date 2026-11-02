# Документация проекта Calculator

## Назначение

Проект демонстрирует настройку непрерывной интеграции с помощью
GitHub Actions.

## Функции

### Сложение

```python
from calculator import add

result = add(2, 3)
```

### Вычитание

```python
from calculator import subtract

result = subtract(10, 4)
```

### Тестирование

Для запуска тестов используется команда:

```bash
python -m pytest -v
```