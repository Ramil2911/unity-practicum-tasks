# Задача 1 «Фруктовый ниндзя»

Тип задания: «проработанный пример» (задача для работы на занятии)

### Что нужно знать?

Создание GameObject и префабов, прикрепление компонентов, в том числе кастомных

### Дано:

Скрипты FruitSpawner, Fruit, DestroyOnBelow

### Цель:

Разработать 2D игру-кликер, в которой игрок должен нажатиями уничтожать падающие сверху предметы (фрукты). Предметы должны самоуничтожаться вне экрана (по условию высоты)

### Решение:

1. Создать префаб фрукта с компонентом Fruit и DestroyOnLowerThan

2. Создать GameObject с компонентом FruitSpawner, добавить в нём ссылку на префаб фрукта

3. Исследовать код скриптов :)
