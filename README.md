Проект містить функції, які забезпечують виконання різноманітних операцій над графами,
наприклад розфарбування, пошук ейлерового та гамільтонового циклів,
перевірка на дводольність, тощо.

У проекті графи зчитуються з csv файлу як список їх ребер, розділених пробілом.
Зберігаються за допомогою списків суміжності (реалізованих словником) чи матриці суміжності.

### Поділ роботи:
- Ліля - [Знаходження ейлерового циклу](https://github.com/bohdanhlovatskyi/dm_project/tree/main/euler_cycle)
- Стефан - [Знаходження гамільтоного циклу](https://github.com/bohdanhlovatskyi/dm_project/tree/main/hamiltonian)
- Богдан - [Розфарбування графа, основа зчитування файлу](https://github.com/bohdanhlovatskyi/dm_project/tree/main/colouring)
- Михайло - [Ізоморфізм, зчитування файлу]()
- Микола - [Дводольність](https://github.com/bohdanhlovatskyi/dm_project/tree/main/duality)

![Graph](https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Line_graph_construction_1.svg/270px-Line_graph_construction_1.svg.png)
```
{1: {4,3,2}, 2: {1,5}, 5: {2, 4}, 4: {1,3}, 3: {1,4} }
```
