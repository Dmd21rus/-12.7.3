# -12.7.3
Домашнее задание

per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
money = int(input("Enter the amount of money: "))

deposit = [int(money * per_cent[key] / 100) for key in per_cent]

print(deposit)
max_deposit = max(deposit)
print(f"Максимальная сумма, которую вы можете заработать — {max_deposit}")
