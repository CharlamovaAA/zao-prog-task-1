# Решение задачи Two Sum (Сумма двух чисел)

## 📌 Описание задачи

Дан массив целых чисел `nums` и целочисленное значение `target`. 
Нужно вернуть индексы двух чисел, сумма которых равна `target`.

**Условия:**
- Нельзя использовать один и тот же элемент дважды
- У каждого входного набора есть только одно решение
- Порядок индексов в ответе не важен

## 📋 Примеры

| Входные данные | Выходные данные |
|----------------|-----------------|
| `nums = [2,7,11,15], target = 9` | `[0, 1]` |
| `nums = [3,2,4], target = 6` | `[1, 2]` |
| `nums = [3,3], target = 6` | `[0, 1]` |

## 🚀 Запуск программы

### Проверка работы функции в интерактивном режиме:

```python
from two_sum import two_sum

# Пример 1
print(two_sum([2, 7, 11, 15], 9))  # [0, 1]

# Пример 2
print(two_sum([3, 2, 4], 6))       # [1, 2]

# Пример 3
print(two_sum([3, 3], 6))          # [0, 1]



python -m unittest test_sum_of_two.py -v
test_example_1 (test_sum_of_two.TestTwoSum.test_example_1)
Тест из первого примера: nums = [2,7,11,15], target = 9 ... ok
test_example_2 (test_sum_of_two.TestTwoSum.test_example_2)
Тест из второго примера: nums = [3,2,4], target = 6 ... ok
test_example_3 (test_sum_of_two.TestTwoSum.test_example_3)
Тест из третьего примера: nums = [3,3], target = 6 ... ok
test_large_numbers (test_sum_of_two.TestTwoSum.test_large_numbers)
Тест с большими числами ... ok
test_negative_numbers (test_sum_of_two.TestTwoSum.test_negative_numbers)
Тест с отрицательными числами ... ok
test_order_doesnt_matter (test_sum_of_two.TestTwoSum.test_order_doesnt_matter)
Тест: порядок индексов не важен ... ok
test_same_value_different_indices (test_sum_of_two.TestTwoSum.test_same_value_different_indices)
Тест: одинаковые значения, но разные индексы ... ok
test_with_zero (test_sum_of_two.TestTwoSum.test_with_zero)
Тест с нулём ... ok
