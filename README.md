# Решатель квадратных уравнений
Скрипт предназначен для решения квадратных уравнений вида 
ax 2+bx+c = 0.

# Как использовать



 Импортирование скрипта в проект
```python
from quadratic_equation import get_roots
```
Функция get_roots(a, b, c) принимает три аргумента - коэффициенты уравнения.
Возвращает значение корней в виде (root1, root2) ( root1, None) или (None, None)

Пример использования:

```python
roots = get_roots(1,2,4)
print(roots)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
