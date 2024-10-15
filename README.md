def get_matrix(n, m, value):
    matrix = []  # Создаем пустой список для матрицы
    for i in range(n):  # Внешний цикл для строк
        row = []  # Создаем пустой список для строки
        for j in range(m):  # Внутренний цикл для столбцов
            row.append(value)  # Заполняем строку значением
        matrix.append(row)  # Добавляем строку в матрицу
    return matrix  # Возвращаем заполненную матрицу

# Пример использования функции
result1 = get_matrix(2, 10, 0)
result2 = get_matrix(3, 5, 42)
result3 = get_matrix(4, 3, 13)

print(result1)
print(result2)
print(result3)
