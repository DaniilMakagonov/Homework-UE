Работу выполнил Макагонов Даниил

1. Алгоритм комнат.
 Алгоритм генерации комнат на самом деле генерирует их фиктивно: в игре присутствует одна единственная комната, сожиержиоме которой пересоздается при достижении точки перехода на следующий уровень. 

 В игре присутствуюет два типа ловушек: статичные и подвижные (двигаются по окружности). Оба типа ловушек наносят одинаковый урон, зависящий от уровня сложности (урон = уровень сложноусти * 5). Генереруются ловушки в случайных координатах внутри игровой зоны, тип ловушки выбирается случайно (вероятность генерации статичной - 0.8, вероятность генерации подвижной - 0.2 соответственно).

При выборе комнаты с повышением слодности также генерируется сфера, восстанавливающая здоровье, которая пропадает, если комната пройдена без того, чтобы эту сферу собрать.

Вся игровая статистика выводится игроку на экран. Также при приближении игрока к двум дверям в конце комнаты появляется информация о том, к какому результату приведет выбор той или иной двери.

Весь код написан самостоятельно, не было никаких заимствований.