# Домашнее задание №10 - Pac-Man (1 балл)

Реализовать игру _Pac-Man_ по следующим правилам:
* Существует поле 10 на 10 клеток. Оси координат направлены слева-направо и сверху-вниз.
* В начале игры в клетке с координатами (1, 1) стоит _Пакман_, в клетке с координатами (10, 10)
  лежит _Еда_
* Задача игрока довести Пакмана до Еды. Для этого он управляет им, последовательно вводя команды
  числами. Команда 1 перемещает Пакмана на одну клетку влево, 2 - вправо, 3 - вверх, 4 - вниз.
* За границы поля Пакман выйти не может. Если игрок пытается сделать это, команда ни к чему не
  приводит, Пакман остаётся на месте.

Прочитать с клавиатуры число `С` типа `int`. Затем прочитатать `C` команд. Если Пакман на своём
пути хоть раз побывал в клетке с Едой, вывести число 1. Иначе вывести число 0.

Если число `С` меньше 0, либо в качестве команды вводится некорректное значение, нужно вывести
сообщение об ошибке `Incorrect input` и прервать выполнение программы.

## Пример

### Входные данные

```
18
2 4 2 4 2 4 2 4 2 4 2 4 2 4 2 4 2 4
```

### Выходные данные

```
1

```
