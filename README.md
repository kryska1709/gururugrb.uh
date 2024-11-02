Использование классов Rectangle и Circle
Эти два класса предоставляют простой, но эффективный способ работы с геометрическими фигурами – прямоугольником и кругом – в Ваших Java-программах.  Они инкапсулируют данные (ширину, высоту, радиус) и предоставляют методы для вычисления площади и периметра/окружности.

Класс Rectangle:

Этот класс моделирует прямоугольник, определяемый его шириной и высотой.

Конструктор:

Rectangle(double width, double height): Создает новый объект Rectangle с заданными шириной и высотой.  Выбросит исключение IllegalArgumentException, если ширина или высота отрицательны.  Это гарантия целостности данных –  невозможно создать прямоугольник с отрицательными размерами.

Методы:

getArea(): Возвращает площадь прямоугольника (ширина * высота).
getPerimeter(): Возвращает периметр прямоугольника (2 * (ширина + высота)).
Пример использования Rectangle:

Этот класс моделирует круг, определяемый его радиусом.

Конструктор:

Circle(double radius): Создает новый объект Circle с заданным радиусом. Выбросит исключение IllegalArgumentException, если радиус отрицателен.  Аналогично Rectangle, это защищает от некорректных данных.

Методы:

getArea(): Возвращает площадь круга (π * радиус²).
getCircumference(): Возвращает длину окружности круга (2 * π * радиус).