### Анализ цифр трёхзначного числа

Программа принимает трёхзначное целое число, разбивает его на сотни, десятки и единицы, а затем вычисляет сумму и произведение его цифр[span_1](start_span)[span_1](end_span).

```python
print("Введите трёхзначное число:")
n = int(input())

digit_1 = n // 100
digit_2 = (n % 100) // 10
digit_3 = n % 10

digit_sum = digit_1 + digit_2 + digit_3
digit_prod = digit_1 * digit_2 * digit_3

print("Сумма цифр:", digit_sum)
print("Произведение цифр:", digit_prod)
```

