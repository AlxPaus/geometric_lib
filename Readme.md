# Geometric Library

## Общее описание проекта:
	Проект представляет из себя библиотеку, состоящую из 4 файлов  		
	написанных на языке Python(3.11)
	В каждом файле содержатся функции, для подсчета периметра или площади 
	определенной геометрической фигуры.

## Файлы проекта:
### `circle.py`
	area(r):
    Принимает радиус окружности, возвращает её площадь.
    
	Параметры:
		r (float): радиус окружности
	Возвращаемое значение:
		S (float) : площадь окружности
		
	perimeter(r):
    Принимает радиус окружности, возвращает её периметр.
    
    Параметры:
		r (float): радиус окружности
	Возвращаемое значение:
		 P (float) : периметр окружности
    
#### Примеры вызова:
`print(area(3))`  - Вывод 28.274333882308138 
`print(area(4/(math.pi ** 0.5)))`  - Вывод 15.999999999999998
`print(perimeter(6))`  - Вывод 37.69911184307752
`print(perimeter(4/math.pi))` - Вывод 8.0

### `rectangle.py`
	area(a, b):
	Принимает две стороны прямоугольника, возвращает площадь прямоугольника.
	
    Параметры:
	    a (float) : первая сторона прямоугольника
	    b (float) : вторая сторона прямоугольника
	Возвращаемое значение:
		S (float) : площадь прямоугольника
	
    perimeter(a, b):
    Принимает две стороны прямоугольника, возвращает периметр прямоугольника.
    
    Параметры:
		a (float) : первая сторона прямоугольника
	    b (float) : вторая сторона прямоугольника

        Возвращаемое значение:
            P (float) : периметр прямоугольника
   
    
#### Примеры вызова:
`print(area(2, 4))` - Вывод 8.0
`print(area(100, 0.01))` - Вывод 1.0
`print(perimeter(3, 4))` - Вывод 14.0
`print(perimeter(3.5, 2.7))` - Вывод 12.4

 ### `square.py`
    area(a):
	Принимает сторону квадрата, возвращает площадь квадрата
	
    Параметры:
	    a (float) : сторона квадрата
	Возвращаемое значение:
		S (float) : площадь квадрата	
	
    perimeter(a):
    Принимает сторону квадрата, возвращает периметр квадрата.
    
    Параметры:
		a (float) : сторона квадрата
    Возвращаемое значение:
            P (float) : периметр прямоугольника
                 
#### Примеры вызова:
`print(area(2))` - Вывод 4.0
`print(area(2.5))` - Вывод 6.25
`print(perimeter(7))` - Вывод 28.0
`print(perimeter(1.5))` - Вывод 6

### `triangle.py`
	area(a, h):
	Принимает сторону треугольника и высоту к ней. Возвращает площадь треугольника
	
    Параметры:
	    a (float) : сторона треугольника
	    h (float) : высота к стороне треугольника
	Возвращаемое значение:
		S (float) : площадь треугольника
	
    perimeter(a, b, c):
    Принимает три стороны треугольника, возвращает периметр треугольника.
    
    Параметры:
		a (float) : первая сторона треугольника
	    b (float) : вторая сторона треугольника
	    c (float) : третья сторона треугольника

        Возвращаемое значение:
            P (float) : периметр треугольника
   
    
#### Примеры вызова:
`print(area(2, 5))` - Вывод 5.0
`print(area(16, 0.5))` - Вывод 4.0
`print(perimeter(3, 4, 5))` - Вывод 12.0
`print(perimeter(1.1, 2.2, 3.3)` - Вывод 6.6

## История изменений проекта
	218656b (HEAD -> new_features_467032) fix() fixed circle.py and triangle.py
	0e0d1de docs(): added comments in all files
	f6150d9 build(): created files from lab_01
	d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
	8ba9aeb L-03: Circle and square addeded
