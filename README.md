# Игра "Жизнь" 

Игра "Жизнь" - это клеточный автомат, придуманный британским математиком Джоном Конвеем в 1970 году. 
В этой игре у каждой клетки на двумерном поле есть два состояния: "живая" или "мертвая". 

В каждом новом поколении состояние клетки определяется по следующим правилам:
1. Любая живая клетка с меньше чем двумя живыми соседями умирает (от одиночества).
2. Любая живая клетка с двумя или тремя живыми соседями выживает до следующего поколения.
3. Любая живая клетка с более чем тремя живыми соседями умирает (от перенаселённости). 
4. Любая мертвая клетка с ровно тремя живыми соседями оживает (как будто по репродукции).

Соседями клетки считаются 8 клеток, окружающих данную клетку по вертикали, горизонтали и диагонали.
___
В файле ```main.py``` - реализация с pygame <br>
В файле ```game_of_life_matplotlib.py``` реализация с matplotlib