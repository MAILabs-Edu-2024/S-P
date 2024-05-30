# Разработка собственного с-подобного языка на F#

| **Имя**                                                              | **Роль в в проекте**              |
|----------------------------------------------------------------------|-----------------------------------|
| Павел Малько | Разработка дерева |
| Руслан Шамбилов | Разработка лексера |
| Артур Адамов | Разработка парсера |

# Документация и краткое описание структуры системы

https://0hesoyam0.github.io/beautifulSooP/

## Реализованы такие функции:
```
Именованные переменные
Функции
Классы
Циклы
Условные операторы
Ввод-вывод файлов и консоли
```

# Эссе

link...

# Примеры программ

## while.soop

```
namespace Foo {
	class A {
		public def a():Unit {
			while a < 3
				Console.Println(a);

			while x < 6 {
				i = x + 6;
				Console.Println(i);
			}
		}
	}
}
```

## expr.soop

```
namespace Foo {
	class A {

		private a: Int = (1+3)*4-5;
		protected b: Int = (1+2)*Namespace.Class.function(a,b,c);

		private c: Int = (a.b(1,2)).c(3,4).d(5);
	}
}
```

## if.soop

```
namespace Foo {
	class A {
		public def a():Unit {

			if x > 10 {
				c:Int = x+10;
				Console.Println(c);
			}
			else if x < 1
				Console.Println(1);
			else
				Console.Println(4);
		}
	}
}
```

## localVar.soop

```
namespace Foo {
	class A {
		private a:Int = 4;
	}
}
```

## fullClass.soop

```
namespace Foo {
	class A {
		private cat: Int = 1;
		public dog: Int = 6;

		public A(a: Int){}

		protected def add(a: Int, b: Int):Int {}
	}
}
```
