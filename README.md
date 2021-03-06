
**Бор**
```
Бор, также именуемый «префиксное дерево» — это древовидная структура данных,
которая особенно эффективна при решении задач на строки.
Она обеспечивает быстрое извлечение данных и чаще всего применяется для поиска слов в словаре,
автозавершений в поисковике и даже для IP-маршрутизации.

Вопросы о борах, часто задаваемые на собеседованиях:
-Подсчитайте общее количество слов, сохраненных в бору
-Выведите на экран все слова, сохраненные в бору
-Отсортируйте элементы массива при помощи бора
-Постройте слова из словаря, воспользовавшись бором
-Создайте словарь T9
```

**Граф**
```
Поиск кротчайшего пути является одной из классических задач теории графов
алгоритм Дейкстры — находит кратчайший путь от одной из вершин графа до всех остальных.
                    Алгоритм работает только для графов без рёбер отрицательного веса.
алгоритм Беллмана-Форда — находит кратчайшие пути от одной вершины графа до всех остальных во взвешенном графе.
                          Вес ребер может быть отрицательным.
алгоритм Флойда-Уоршелла — находит кратчайшие пути между всеми вершинами взвешенного ориентированного графа.
алгоритм Джонсона — находит кратчайшие пути между всеми парами вершин взвешенного ориентированного графа.
алгоритм Ли (волновой алгоритм) — находит путь между вершинами графа, содержащий минимальное количество промежуточных вершин (ребер).
                                  Используется для поиска кратчайшего расстояния на карте в стратегических играх.
алгоритм поиска A* — находит маршрут с наименьшей стоимостью от одной вершины (начальной) к другой (целевой, конечной),
                                         используя алгоритм поиска по первому наилучшему совпадению на графе.

```



**Бинарное дерево поиска**
```
Самыми простыми решениями задачи построения ассоциативного массива являются списки и массивы пар (ключ,данные).
Однако эти решения обладают рядом недостатков.
Списки обеспечивают быструю вставку и удаление элементов из произвольной позиции (при условии, что мы знаем
указатель на элемент в требуемой позиции), но поддерживают только линейный поиск, что в большинстве случаев
неприемлемо медленно.
Массивы могут обеспечить быстрый (двоичный или интерполяционный) поиск, но для этого массив должен быть
упорядочен, и вставка в упорядоченный массив требует сдвига большого числа элементов, что также неприемлемо медленно.
Дальнейшее развитие технологии предлагает использовать для построения ассоциативных массивов деревья.

Вопросы о деревьях, часто задаваемые на собеседованиях:

-Найдите высоту двоичного дерева
-Найдите k-ное максимальное значение в двоичном дереве поиска
-Найдите узлы, расположенные на расстоянии “k” от корня
-Найдите предков заданного узла в двоичном дереве


[www.o2b.ru](http://www.o2b.ru/%D0%BF%D0%BE%D0%B8%D1%81%D0%BA-%D1%81%D0%B0%D0%BC%D0%BE%D0%B3%D0%BE-%D0%B4%D0%B5%D1%88%D0%B5%D0%B2%D0%BE%D0%B3%D0%BE-%D0%BC%D0%B0%D1%80%D1%88%D1%80%D1%83%D1%82%D0%B0-%D0%BD%D0%B0-php/)

[medium.com](https://medium.com/nuances-of-programming/%D0%B2%D1%81%D0%B5-%D1%87%D1%82%D0%BE-%D0%BD%D1%83%D0%B6%D0%BD%D0%BE-%D0%B7%D0%BD%D0%B0%D1%82%D1%8C-%D0%BE-%D0%B4%D1%80%D0%B5%D0%B2%D0%BE%D0%B2%D0%B8%D0%B4%D0%BD%D1%8B%D1%85-%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%D1%85-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-d750444a77ec)

Деревья являются широко известными нелинейными структурами. 
Они хранят данные не линейным способом, а упорядочивают их иерархически.

Все узлы дерева соединены линиями, называемыми ребрами. 
Это важная часть деревьев, потому что она управляет связью между узлами.

Корень — самый верхний узел дерева.
Ребро — связь между двумя узлами.
Потомок — узел, имеющий родительский узел.
Родитель — узел, имеющий ребро, соединяющее его с узлом-потомком.
Лист — узел, не имеющий узлов-потомков на дереве.
Высота — это длина самого дальнего пути к листу.
Глубина — длина пути к корню.


Очень часто в программировании возникает задача построения ассоциативного массива, т. е. массива, индексами
которого являются либо вовсе не целые числа (например, строки или вещественные числа), либо целые числа из очень
широкого диапазона, при том, что используется реально лишь очень небольшая часть индексов, так что заводить
отдельную ячейку под каждое возможное значение индекса нецелесообразно.
В дальнейшем индекс в ассоциативном массиве, по которому ищется элемент, будем называть ключом, а сам
элемент — данными. Термин «ключ» взят из теории баз данных.
Самыми простыми решениями задачи построения ассоциативного массива являются списки и массивы пар (ключ,
данные). Однако эти решения обладают рядом недостатков.
Списки обеспечивают быструю вставку и удаление элементов из произвольной позиции (при условии, что мы знаем
указатель на элемент в требуемой позиции), но поддерживают только линейный поиск, что в большинстве случаев
неприемлемо медленно.
Массивы могут обеспечить быстрый (двоичный или интерполяционный) поиск, но для этого массив должен быть
упорядочен, и вставка в упорядоченный массив требует сдвига большого числа элементов, что также неприемлемо
медленно.
Дальнейшее развитие технологии предлагает использовать для построения ассоциативных массивов деревья. В
общем существует два основных способа использования деревьев для организации ассоциативных массивов.


Поиск в глубину (Depth-first search, DFS) — один из методов обхода дерева.
Стратегия поиска в глубину, как и следует из названия, состоит в том, чтобы идти «вглубь» дерева, насколько это возможно.
Алгоритм поиска описывается рекурсивно: перебираем все исходящие из рассматриваемой вершины рёбра.
Если ребро ведёт в вершину, которая не была рассмотрена ранее, то запускаем алгоритм от этой нерассмотренной вершины, а после возвращаемся и продолжаем перебирать рёбра.
Возврат происходит в том случае, если в рассматриваемой вершине не осталось рёбер, которые ведут в не рассмотренную вершину.
 Если после завершения алгоритма не все вершины были рассмотрены, то необходимо запустить алгоритм от одной из не рассмотренных вершин.

• Поиск в ширину (breadth-first search, BFS) — метод обхода дерева и поиска пути. Поиск в ширину является одним из неинформированных алгоритмов поиска.
Поиск в ширину работает путём последовательного просмотра отдельных уровней дерева, начиная с узла-источника.
Рассмотрим все рёбра, выходящие из узла.
Если очередной узел является целевым узлом, то поиск завершается; в противном случае узел добавляется в очередь.
После того, как будут проверены все рёбра, выходящие из узла, из очереди извлекается следующий узел, и процесс повторяется.


Бинарное дерево поиска
“Бинарное (двоичное) дерево поиска иногда называют упорядоченными бинарными деревьями, оно хранит значения упорядоченно,
таким образом поиск и другие операции могут строится на принципах бинарного поиска ”
```