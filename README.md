# sortFruit
Сортировка списка фруктов по различным критериям, например, по алфавиту, цвету, весу и т. д.



fruits = [
    {"name": "Apple", "weight": 200},
    {"name": "Banana", "weight": 150},
    {"name": "Cherry", "weight": 50},
    {"name": "Mango", "weight": 300}
]

fruits.sort(key=lambda x: x["weight"])  # Сортировка по весу
print(fruits)
