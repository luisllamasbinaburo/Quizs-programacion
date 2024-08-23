¿Qué hace el decorador `@staticmethod`?
- Define un método que no accede a la instancia de la clase
- Define un método que solo accede a la instancia de la clase
- Define un método que solo accede a las variables de clase

¿Qué es un `generator`?
- Una función que retorna un iterador
- Un objeto que se ejecuta en paralelo
- Un tipo de lista especial

¿Qué función de Python devuelve el tamaño de un objeto en bytes?
- sysgetsizeof()
- size()
- getsize()

¿Cuál es el propósito del método `__init__` en una clase?
- Inicializar una nueva instancia de la clase
- Definir métodos estáticos
- Definir propiedades de clase

¿Qué módulo se usa para realizar solicitudes HTTP?
- requests
- http
- socket

¿Cómo se crea una lista por comprensión (list comprehension)?
- [x**2 for x in range(10)]
- for x in range(10): x**2
- [x^2; x in range(10)]

¿Qué hace el decorador `@classmethod`?
- Define un método que accede solo a variables de clase
- Define un método que no accede a variables de clase
- Define un método que accede solo a variables de instancia

¿Cómo se manejan múltiples excepciones en un solo bloque `except`?
- except (ValueError, TypeError):
- except ValueError or TypeError:
- except ValueError, TypeError:

¿Qué función se usa para mapear una función sobre un iterable?
- map()
- filter()
- reduce()

¿Qué es un contexto (`with`)?
- Una forma de manejar recursos automáticamente
- Un tipo especial de función
- Un bucle que se ejecuta hasta que una condición se cumple

¿Cómo se define un método privado en una clase?
- Comienza con `__` (doble guion bajo)
- Comienza con `_` (guion bajo)
- Comienza con `priv`

¿Qué módulo se usa para trabajar con archivos JSON?
- json
- pickle
- csv

¿Qué hace el método `__repr__` en una clase de Python?
- Devuelve una representación oficial de la instancia
- Devuelve una cadena amigable al usuario de la instancia
- Invoca automáticamente la conversión de la instancia a cadena

¿Qué hace la función `zip()`?
- Combina dos o más iterables en tuplas
- Fusiona dos listas en una
- Ordena elementos de múltiples listas

¿Qué método se usa para detener un hilo (`thread`)?
- No hay un método oficial para detener un hilo
- stop()
- terminate()

¿Qué módulo se usa para crear interfaces gráficas?
- tkinter
- pygame
- pygui

¿Qué hace el método `@property` en una clase de Python?
- Convierte un método en una propiedad de solo lectura
- Convierte una clase en un singleton
- Convierte una propiedad en una variable de clase

¿Qué función de Python se usa para compilar expresiones regulares?
- recompile()
- regexcompile()
- regex()

¿Cómo se crea un diccionario por comprensión?
- {x: x**2 for x in range(5)}
- {x => x^2 for x in range(5)}
- dict(x: x**2 for x in range(5))

¿Qué es `GIL`?
- Global Interpreter Lock
- Global Instance Lock
- General Interface Library

¿Cómo se lee todo el contenido de un archivo?
- fileread()
- filereadlines()
- filereadline()

¿Qué hace el operador `//`?
- Realiza una división entera
- Realiza una división normal
- Realiza una operación de módulo

¿Qué palabra clave se usa para declarar un generador?
- yield
- generate
- return

¿Qué hace el método `__call__` en una clase de Python?
- Permite que una instancia de la clase se llame como una función
- Convierte una instancia en un hilo
- Convierte una instancia en un iterador

¿Qué módulo se usa para trabajar con archivos CSV?
- csv
- excel
- spreadsheet

¿Cómo se define una excepción personalizada?
- Crear una nueva clase que herede de `Exception`
- Usar la palabra clave `custom`
- Crear una nueva clase que

¿Qué hace el método `__eq__` en una clase de Python?
- Compara si dos instancias son iguales
- Asigna una nueva instancia a una variable
- Verifica si dos instancias son idénticas

¿Cómo se combina el contenido de dos listas en una sola?
- lista1extend(lista2)
- lista1append(lista2)
- lista1 += [lista2]

¿Qué método de un archivo se usa para escribir una cadena en él?
- write()
- append()
- insert()

¿Cómo se ejecuta un código solo si un archivo de Python se ejecuta directamente?
- Usando `if __name__ == "__main__":`
- Usando `if __main__ == "__name__":`
- Usando `if __file__ == "__main__":`

¿Qué método se utiliza para aplicar una función a cada elemento de una lista?
- map
- apply
- iterate

¿Cuál es la manera correcta de definir una propiedad en una clase utilizando `@property`?
- @property
- @method
- @attribute

¿Cómo se realiza la introspección de métodos y atributos en un objeto?
- dir
- inspect
- methods

¿Qué es una función generadora y cómo se define?
- Usando `yield`
- Usando `return`
- Usando `yield from`

¿Cómo se utiliza el decorador `@staticmethod` en una clase de Python?
- Define un método que no recibe una instancia de la clase como primer argumento
- Define un método que modifica el estado de la instancia
- Define un método que necesita acceso al estado de la instancia

¿Cómo se implementa un método mágico `__getitem__` en una clase?
- Para permitir el acceso a los elementos de la clase mediante indexación
- Para permitir la iteración sobre la clase
- Para permitir la comparación de la clase

¿Cómo se puede implementar la programación concurrente utilizando `asyncio`?
- Usando `async` y `await`
- Usando `threads` y `locks`
- Usando `multiprocessing`

¿Qué método se utiliza para eliminar elementos de una colección en un contexto de manejo de excepciones?
- `discard`
- `remove`
- `pop`

¿Qué es un `context manager` y cómo se implementa?
- Usando `__enter__` y `__exit__`
- Usando `with` y `as`
- Usando `try` y `except`

¿Cómo se crea una subclase que sobrecarga un método de la superclase?
- Definiendo un método con el mismo nombre en la subclase
- Usando `super()` para llamar al método de la superclase
- Usando `override` para definir el método

¿Qué técnica se utiliza para la serialización de objetos?
- `pickle`
- `json`
- `marshal`

¿Cómo se maneja el acceso a variables de clase y de instancia en una clase?
- Usando `self` para variables de instancia y el nombre de la clase para variables de clase
- Usando `cls` para variables de instancia y `self` para variables de clase
- Usando `self` para todas las variables

¿Cuál es el propósito del método mágico `__init__` en una clase?
- Inicializar los atributos de la instancia
- Crear una instancia de la clase
- Definir el tipo de la instancia

¿Cómo se implementa un algoritmo de búsqueda binaria utilizando listas ordenadas?
- Comparando el valor objetivo con el valor medio de la lista
- Iterando sobre cada elemento de la lista
- Dividiendo la lista en dos partes iguales

¿Cómo se maneja el acceso concurrente a recursos compartidos?
- Usando `threading.Lock`
- Usando `asyncio.Queue`
- Usando `multiprocessing.Lock`

¿Qué es un descriptor y cómo se implementa?
- Usando métodos `__get__`, `__set__` y `__delete__`
- Usando `@property` y `@setter`
- Usando `get` y `set`

¿Cómo se define y utiliza un `metaclass`?
- Usando la clase `type` como una metaclase
- Usando `metaclass` como una propiedad de la clase
- Usando `class` para definir el `metaclass`

¿Cómo se realiza el análisis léxico y sintáctico de código Python en tiempo de ejecución?
- Usando `tokenize` y `ast`
- Usando `parser` y `compiler`
- Usando `lex` y `yacc`

¿Cómo se implementa un decorador de clase?
- Definiendo una función que toma una clase y devuelve una clase modificada
- Definiendo un método dentro de la clase que actúa como decorador
- Definiendo una función dentro del `__init__` de la clase

¿Qué es un `weakref` y para qué se utiliza?
- Para evitar la referencia fuerte y permitir la recolección de basura
- Para crear referencias circulares entre objetos
- Para garantizar que los objetos no sean eliminados por el recolector de basura

¿Cómo se implementa un protocolo utilizando `abc`?
- Usando `abstractmethod` y `ABCMeta`
- Usando `protocol` y `abstractmethod`
- Usando `interface` y `abstract`

¿Cómo se realizan operaciones matemáticas avanzadas utilizando la biblioteca `numpy`?
- Usando funciones como `numpy.dot` y `numpy.linalg`
- Usando operadores aritméticos estándar
- Usando funciones básicas de la biblioteca `math`

¿Qué es un `Coroutine` y cómo se define?
- Usando `async def` para definir una función que puede ser pausada
- Usando `yield` para definir una función que no se completa
- Usando `def` con `return` para definir una función regular

¿Cómo se realiza la personalización del comportamiento de los operadores en una clase?
- Definiendo métodos especiales como `__add__` y `__sub__`
- Definiendo métodos estándar como `add` y `subtract`
- Definiendo métodos de clase como `plus` y `minus`

¿Qué es un `descriptor protocol` y cómo se utiliza?
- Un protocolo que define métodos para manejar la accesibilidad de atributos
- Un protocolo para manejar la sincronización de hilos
- Un protocolo para definir la conversión de tipos

¿Cómo se utiliza `itertools` para crear iteradores personalizados?
- Usando funciones como `itertools.chain` y `itertools.cycle`
- Usando `iter` y `next` para definir iteradores
- Usando `list` y `range` para crear secuencias