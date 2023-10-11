# qwert
# способ №1 - слияние списков с удалением дубликатов
list1 = [1, 2, 3, 4]
list2 = [4, 5, 6, 7]
list3 = list(set(list1+list2))
print(list3)
# способ №2 - слияние списков только по общим элементам
list1 = [1, 2, 3, 4]
list2 = [3, 4, 5, 6]
list3 = list(set(list1).intersection(set(list2)))
print(list3)
