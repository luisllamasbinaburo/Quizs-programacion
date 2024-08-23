¿Qué hace el operador 'typeid'?
- Devuelve el tipo de dato en tiempo de ejecución
- Devuelve el tamaño del tipo de dato
- Convierte un tipo de dato a otro

¿Qué es una 'vtable'?
- Una tabla de punteros a funciones virtuales
- Una tabla de variables globales
- Una tabla de funciones estáticas

¿Qué es un 'functor'?
- Un objeto que se comporta como una función
- Un tipo especial de puntero a función
- Una función que opera sobre punteros

¿Qué es el 'heap'?
- La región de memoria dinámica
- La región de memoria estática
- El espacio donde se almacenan los punteros

¿Qué es el 'stack unwinding'?
- El proceso de limpiar la pila de llamadas durante el manejo de excepciones
- El proceso de asignar memoria en la pila
- El proceso de optimización de bucles en tiempo de compilación

¿Qué es el 'RTTI'?
- Runtime Type Information
- Real-Time Threading Interface
- Register Transfer Timing Information

¿Qué hace la palabra clave 'volatile'?
- Indica que una variable puede ser modificada en cualquier momento por procesos fuera del control del código
- Evita que una variable sea optimizada por el compilador
- Declara una variable como inmutable

¿Qué es el 'placement new'?
- Una técnica para construir un objeto en una ubicación de memoria previamente asignada
- Una forma de asignar memoria en el stack en lugar del heap
- Un mecanismo para optimizar la asignación de memoria dinámica

¿Qué es un 'template metaprogramming'?
- Una técnica para realizar cálculos en tiempo de compilación usando plantillas
- Un método para generar código fuente automáticamente
- Un mecanismo para optimizar las plantillas en tiempo de ejecución

¿Qué significa 'constexpr'?
- Una expresión que se evalúa en tiempo de compilación
- Una expresión que se evalúa en tiempo de ejecución
- Una expresión que retorna un puntero constante

¿Qué es el concepto de 'move semantics'?
- Permite la transferencia eficiente de recursos de un objeto a otro sin realizar copias
- Impide la sobrecarga de operadores de asignación
- Optimiza el código para operaciones matemáticas

¿Qué hace la función 'std::forward'?
- Preserva el tipo de referencia de un argumento para la invocación de una función
- Convierte un tipo de dato en un puntero
- Devuelve un puntero a una función

¿Qué es un 'smart pointer'?
- Un objeto que simula un puntero, pero gestiona automáticamente la memoria
- Un puntero que apunta a varias direcciones de memoria
- Un puntero que se adapta a diferentes tipos de datos

¿Qué hace la función 'std::unique_ptr'?
- Gestiona la propiedad única de un recurso y lo libera automáticamente cuando ya no es necesario
- Permite compartir la propiedad de un recurso entre múltiples punteros
- Crea una copia profunda de un puntero

¿Qué es un 'deadlock'?
- Una situación donde dos o más hilos están bloqueados permanentemente esperando recursos entre sí
- Un estado en el que un programa deja de responder debido a un bucle infinito
- Una situación donde un puntero nulo es dereferenciado

¿Qué significa 'RAII' en la gestión de recursos?
- Resource Acquisition Is Initialization
- Resource Allocation In Interrupts
- Resource Assignment Is Immediate

¿Qué es un 'forward declaration'?
- Una declaración de una función o clase antes de su definición completa
- Una instrucción para mover un puntero al siguiente elemento
- Una técnica para optimizar el uso de bucles

¿Qué es una 'thread-safe function'?
- Una función que se puede ejecutar de manera segura en un entorno multihilo sin causar problemas de sincronización
- Una función que solo se ejecuta en un único hilo
- Una función que siempre retorna el mismo valor

¿Qué hace la función 'std::async'?
- Lanza una tarea asíncrona en un hilo separado
- Sincroniza la ejecución de varios hilos
- Bloquea la ejecución hasta que se complete una tarea

¿Qué es el 'nullptr'?
- Un literal de puntero nulo específico que reemplaza a NULL
- Una función que retorna un puntero a nulo
- Un tipo de puntero especial utilizado en punteros inteligentes

¿Qué es una 'expresión regular'?
- Una secuencia de caracteres que forma un patrón de búsqueda
- Una expresión que siempre evalúa verdadero o falso
- Una expresión que solo contiene operaciones aritméticas básicas

¿Qué es una 'forward list'?
- Una lista enlazada unidireccional
- Una lista que permite insertar elementos solo al final
- Una lista que no permite duplicados

¿Qué es un 'race condition'?
- Una situación en la que el comportamiento de un programa depende del orden de ejecución de hilos
- Una condición en la que se produce una excepción debido a un puntero nulo
- Un escenario donde dos funciones compiten por el mismo recurso

¿Qué es una 'lambda capture'?
- Un mecanismo para capturar variables del contexto circundante dentro de una expresión lambda
- Un proceso para capturar la salida de una función lambda
- Una técnica para optimizar funciones lambda en tiempo de ejecución

¿Qué hace la función 'std::bind'?
- Vincula argumentos a una función, creando una nueva función parcial
- Convierte una función en un puntero a función
- Fusiona dos funciones en una sola

¿Qué es un 'tuple'?
- Una colección de elementos de diferentes tipos
- Un arreglo de punteros
- Un tipo especial de puntero inteligente

¿Qué es un 'shared_ptr'?
- Un puntero inteligente que comparte la propiedad del objeto apuntado con otros 'shared_ptr'
- Un puntero que puede cambiar de tipo dinámicamente
- Un puntero que garantiza la exclusividad de acceso a un recurso

¿Qué es un 'function object'?
- Un objeto que se comporta como una función al sobrecargar el operador ()
- Una función que retorna un objeto
- Un tipo especial de función que puede ser llamada con punteros



¿Qué es un "functor" en C++ y cómo se define?
- Una clase que sobrecarga el operador `()`
- Una clase que define un método estático
- Una función que se pasa como argumento

¿Qué diferencia hay entre `std::vector` y `std::array`?
- `std::vector` es dinámico y puede cambiar de tamaño; `std::array` es de tamaño fijo
- `std::array` es dinámico y puede cambiar de tamaño; `std::vector` es de tamaño fijo
- `std::vector` almacena elementos de tipos diferentes; `std::array` solo de un tipo

¿Cómo se realiza una conversión entre tipos usando `reinterpret_cast`?
- Para convertir entre tipos de datos de forma segura a nivel de bits
- Para realizar conversiones entre punteros a tipos no relacionados
- Para convertir entre punteros a clases base y derivadas

¿Qué es el "Rule of Five" en C++11 y cuándo se aplica?
- La necesidad de definir explícitamente un constructor de copia, destructor, operador de asignación de copia, constructor de movimiento y operador de asignación de movimiento cuando se manejan recursos dinámicos
- La necesidad de definir cinco métodos en una clase para su correcta funcionalidad
- La obligación de definir cinco operadores sobrecargados en una clase

¿Cómo se define un "alias template"?
- Usando la sintaxis `template <typename T> using Alias = Type<T>;`
- Usando `typedef template <typename T> Alias = Type<T>;`
- Usando `template <typename T> Alias<Type<T>>;`

¿Qué es el "type_traits" en C++ y cómo se utiliza?
- Una biblioteca que proporciona plantillas para consultar y modificar propiedades de tipos en tiempo de compilación
- Una biblioteca que permite la conversión dinámica entre tipos
- Una biblioteca que define operadores para tipos de datos

¿Cómo se realiza una especialización de plantilla?
- Definiendo una versión específica de una plantilla para un tipo particular
- Definiendo una plantilla sin parámetros
- Usando el operador `template` en el cuerpo de una función

¿Qué es una expresión "constexpr" y cómo se usa?
- Una expresión cuyo valor puede ser evaluado en tiempo de compilación
- Una expresión que permite la evaluación en tiempo de ejecución
- Una expresión que solo es válida dentro de funciones constexpr

¿Qué es la "SFINAE" en C++ y cómo se aplica?
- "Substitution Failure Is Not An Error", una técnica que permite seleccionar la función más adecuada en función de los tipos de parámetros
- Una técnica para forzar la sustitución de tipos en tiempo de compilación
- Un mecanismo para evitar errores en la evaluación de expresiones constantes

¿Qué hace el modificador `noexcept` en C++ y cómo se usa?
- Indica que una función no lanzará excepciones
- Permite que una función sea llamada solo en condiciones excepcionales
- Especifica que una función debe lanzar una excepción si ocurre un error

¿Cómo se implementa un "thread-safe singleton"?
- Usando un mutex o `std::call_once` para asegurar la inicialización única y segura en un entorno multihilo
- Implementando la clase singleton de forma estática sin sincronización
- Usando un puntero a miembro estático en una clase

¿Qué es un "rvalue reference" y cuándo se utiliza?
- Un tipo de referencia que permite la transferencia de recursos de un rvalue (valor temporal) a un lvalue
- Una referencia que solo puede ser utilizada para objetos constantes
- Una referencia que no puede ser utilizada para objetos temporales

¿Cómo se definen y utilizan las funciones miembro "default" y "delete" en una clase?
- Usando `= default` para indicar que se debe generar la implementación predeterminada y `= delete` para eliminar la función
- Usando `default` para eliminar funciones y `delete` para definirlas
- Usando `default` y `delete` como palabras clave en la definición de la clase

¿Qué es el "explicit" en la declaración de constructores y operadores?
- Se utiliza para evitar conversiones implícitas automáticas
- Indica que una función debe ser llamada explícitamente
- Especifica que un constructor debe ser generado automáticamente

¿Cómo se implementa un "unique_ptr" y cuál es su propósito?
- `std::unique_ptr` es un puntero inteligente que garantiza la propiedad única del objeto que apunta, eliminando la necesidad de gestión manual de memoria
- `std::unique_ptr` es un puntero que puede compartir la propiedad del objeto con otros punteros
- `std::unique_ptr` es un puntero que gestiona múltiples instancias del mismo objeto

¿Cómo se declara una función "template" que acepta un número variable de argumentos?
- Usando `template <typename... Args> void funcion(Args... args)`
- Usando `template <typename Arg1, typename Arg2> void funcion(Arg1, Arg2)`
- Usando `template <typename Args> void funcion(...)`

¿Qué es el "decltype" y cómo se utiliza?
- Una palabra clave que deduce el tipo de una expresión en tiempo de compilación
- Un tipo de datos que define un tipo a partir de una declaración
- Una palabra clave que convierte un tipo a un tipo de datos específico

¿Cómo se utiliza el "std::enable_if" para habilitar o deshabilitar funciones basadas en condiciones?
- Usando `std::enable_if` en la declaración de plantilla para habilitar funciones solo si se cumple una condición
- Usando `std::enable_if` para definir tipos de datos condicionales
- Usando `std::enable_if` para habilitar la sobrecarga de operadores

¿Qué es un "move constructor" y cómo se define?
- Un constructor que transfiere los recursos de un objeto temporal a un nuevo objeto
- Un constructor que copia los recursos de otro objeto
- Un constructor que inicializa un objeto desde un valor por defecto

¿Cómo se definen y usan las "lambda expressions" en C++11?
- Usando la sintaxis `[capture](parameters) -> return_type { // body }` para crear funciones anónimas
- Usando la sintaxis `lambda(parameters) { // body }` para definir funciones en línea
- Usando la sintaxis `function(parameters) { // body }` con la palabra clave `lambda`

¿Qué es un "tuple" en C++ y cómo se puede acceder a sus elementos?
- Una estructura que puede contener varios tipos de datos y se accede usando `std::get<índice>(tuple)`
- Una estructura que solo contiene elementos del mismo tipo y se accede usando `tuple[índice]`
- Una clase que contiene punteros a diferentes tipos de datos y se accede usando `tuple->índice`

¿Cómo se maneja la herencia múltiple en C++ y qué problemas puede causar?
- Se usa especificando múltiples clases base en la declaración de la clase derivada; puede causar problemas de ambigüedad y diamantes
- Se usa especificando una clase base secundaria en la declaración; no causa problemas
- Se usa especificando solo una clase base y extendiendo desde esa clase

¿Qué es el "CRTP" (Curiously Recurring Template Pattern) y cómo se utiliza?
- Un patrón de diseño en el que una clase template hereda de una instancia de sí misma para proporcionar comportamientos específicos en la clase base
- Un patrón de diseño que utiliza plantillas para generar clases derivadas automáticamente
- Un patrón de diseño que permite la recursión en funciones miembro de plantillas

¿Cómo se definen y utilizan las "traits" en C++ para comprobar propiedades de tipos?
- Usando plantillas especializadas para consultar y manipular propiedades de tipos en tiempo de compilación
- Usando funciones que retornan el tipo de datos de una variable
- Usando métodos que definen propiedades de tipos en tiempo de ejecución

¿Qué es el "non-static data member initialization" y cómo se usa en C++11?
- La capacidad de inicializar miembros de datos no estáticos directamente en su declaración
- La capacidad de inicializar miembros de datos estáticos en su declaración
- La capacidad de inicializar datos miembro solo en el constructor

¿Cómo se implementa una clase que utiliza el patrón de diseño "Observer"?
- Definiendo una interfaz para los observadores y un mecanismo para notificar a estos observadores de los cambios en el sujeto
- Definiendo una clase que hereda de múltiples clases base para manejar notificaciones
- Usando plantillas para definir observadores y sujetos en

tiempo de compilación

¿Qué es un "RAII" (Resource Acquisition Is Initialization) y cómo se aplica?
- Un patrón de diseño donde la adquisición de recursos ocurre en el constructor de una clase y su liberación en el destructor
- Un patrón de diseño que permite la adquisición y liberación automática de recursos en una función
- Una técnica para evitar la fuga de memoria mediante el uso de punteros crudos

¿Cómo se implementa el "double dispatch" en C++ utilizando la herencia y las funciones virtuales?
- Usando una combinación de funciones virtuales en la clase base y llamadas a métodos específicos en clases derivadas para resolver comportamientos en tiempo de ejecución
- Usando funciones no virtuales en la clase base y métodos estáticos en clases derivadas
- Usando múltiples constructores en la clase base para despachar métodos específicos

¿Qué es el "std::optional" en C++17 y cuándo se usa?
- Un contenedor que puede o no contener un valor, usado para evitar el uso de punteros nulos
- Un tipo de datos que permite realizar operaciones opcionales sobre una variable
- Un tipo de puntero que se puede inicializar opcionalmente en tiempo de ejecución

¿Cómo se realiza la "herencia privada" en C++ y qué implicaciones tiene?
- Usando `private` en la lista de clases base; los miembros de la clase base se convierten en privados en la clase derivada
- Usando `protected` en la lista de clases base; los miembros de la clase base se convierten en protegidos en la clase derivada
- Usando `public` en la lista de clases base; los miembros de la clase base se convierten en públicos en la clase derivada

¿Qué es un "volatile" en C++ y cuándo se debería usar?
- Un modificador que indica que una variable puede ser modificada de forma inesperada, evitando optimizaciones del compilador
- Un modificador que impide que una variable sea modificada por funciones externas
- Un tipo de dato especial que solo se puede modificar dentro de una función `volatile`

¿Cómo se usa el "std::forward" en combinación con funciones template?
- Para mantener la semántica de valor/rvalor en la transferencia de parámetros a funciones
- Para convertir un rvalue en un lvalue
- Para hacer que una función template acepte un número variable de argumentos

¿Qué es un "proxy pattern" y cómo se implementa?
- Un patrón de diseño que proporciona un sustituto o marcador de posición para controlar el acceso a un objeto, típicamente implementado mediante clases que actúan como intermediarias
- Un patrón de diseño que permite la creación de objetos complejos utilizando otros objetos
- Un patrón de diseño que permite la observación de cambios en un objeto desde múltiples puntos

¿Qué es un "strongly typed enum" en C++11 y cómo se declara?
- `enum class Color { Red, Green, Blue };`, una enumeración con nombres de tipo y valores fuertemente tipados
- `enum Color { Red, Green, Blue };`, una enumeración con valores implícitamente convertibles a int
- `enum struct Color { Red, Green, Blue };`, una estructura que contiene enumeraciones

¿Qué es el "pimpl idiom" y cómo ayuda a ocultar detalles de implementación?
- Un patrón que utiliza un puntero a una estructura de implementación en la declaración de la clase para ocultar los detalles de implementación y reducir las dependencias de compilación
- Un patrón que permite la creación de múltiples instancias de una clase usando plantillas
- Un patrón que define interfaces para acceder a detalles de implementación en una clase base

¿Cómo se implementa un "lock-free data structure" en C++ y qué ventajas tiene?
- Usando técnicas de programación concurrente que evitan la necesidad de bloquear para garantizar la consistencia de datos compartidos, mejorando el rendimiento en sistemas multihilo
- Usando mutexes para proteger el acceso a los datos en sistemas multihilo
- Usando semáforos para sincronizar el acceso a estructuras de datos en sistemas multihilo

¿Cómo se usa el "std::allocator" para gestionar la memoria personalizada en contenedores STL?
- Implementando un `std::allocator` personalizado para controlar la asignación y desasignación de memoria en contenedores como `std::vector`
- Usando `std::allocator` para definir tipos personalizados en contenedores
- Usando `std::allocator` para crear punteros inteligentes en contenedores

¿Qué es el "three-way comparison operator" en C++20 y cómo se define?
- Un operador `operator<=>` que compara dos valores y retorna un resultado basado en su orden relativo, proporcionando un soporte unificado para todos los operadores de comparación
- Un operador que permite comparar tres variables a la vez
- Un operador que retorna un booleano basado en la comparación de tres valores

¿Qué es la "ADL" (Argument Dependent Lookup) en C++ y cómo afecta la resolución de nombres?
- Un proceso en el que el compilador busca nombres de funciones en los espacios de nombres asociados con los tipos de los argumentos de la función
- Un mecanismo para evitar la ambigüedad en la sobrecarga de funciones
- Un proceso que resuelve nombres de variables dentro de una función de acuerdo con su tipo de retorno

¿Cómo se implementa una "state machine" en C++ usando clases?
- Usando clases para representar estados y métodos virtuales para definir transiciones entre estados, con una clase principal que maneja el estado actual
- Usando un `switch` dentro de una función para manejar diferentes estados
- Usando plantillas para definir estados y transiciones en tiempo de compilación

¿Cómo se utiliza la herencia virtual en C++ y para qué se emplea?
- Para evitar la ambigüedad en herencias múltiples, donde una clase base se hereda a través de múltiples rutas
- Para permitir la creación de instancias de clases base
- Para forzar la implementación de métodos virtuales en clases derivadas

¿Qué es un "placement new" y cómo se usa?
- Un operador `new` que permite la colocación de un objeto en una ubicación específica de memoria, útil para la sobrecarga de operadores `new` en clases personalizadas
- Un operador que permite la inicialización de objetos usando valores por defecto
- Un operador que libera memoria de manera personalizada para objetos creados en el montón

¿Cómo se define y usa un "metaprogramming"?
- Usando plantillas para realizar cálculos y transformaciones de tipos en tiempo de compilación, permitiendo generar código complejo de manera eficiente
- Usando macros para generar código repetitivo en tiempo de compilación
- Usando punteros y referencias para modificar el comportamiento de las funciones en tiempo de ejecución

¿Qué es un "span" en C++20 y cómo se utiliza?
- Una vista contigua no propia sobre una secuencia de elementos, que proporciona una forma segura de manejar arrays y otros contenedores sin copiar datos
- Un puntero inteligente que gestiona automáticamente la vida útil de los objetos
- Un tipo que permite la manipulación de cadenas de caracteres de forma eficiente

¿Cómo se implementa un "memory pool" en C++ y cuáles son sus ventajas?
- Usando una estructura que preasigna un bloque de memoria grande y lo subdivide en partes más pequeñas para la asignación rápida, minimizando la fragmentación de la memoria
- Usando `malloc` y `free` para gestionar la memoria de manera más eficiente
- Usando punteros inteligentes para controlar el acceso a la memoria compartida

¿Cómo se usa el "std::variant" y cuándo es apropiado?
- Un tipo seguro en tiempo de compilación que puede contener uno de varios tipos diferentes, útil cuando una variable puede tomar múltiples tipos pero solo uno a la vez
- Un contenedor que puede contener varios tipos de datos simultáneamente
- Un tipo que permite la conversión automática entre diferentes tipos de datos

¿Qué es un "coroutine" en C++20 y cómo se define?
- Una función que puede suspenderse y reanudarse, permitiendo la escritura de código asíncrono de manera más natural y legible
- Una función que se ejecuta en paralelo con otras funciones
- Un tipo de puntero inteligente que gestiona la concurrencia en un entorno multihilo

¿Cómo se maneja la especialización parcial de plantillas?
- Definiendo una versión de plantilla que aplica solo a un subconjunto de los tipos o parámetros posibles, proporcionando una implementación más específica
- Definiendo una plantilla que se especializa solo en tiempo de ejecución
- Usando macros para generar código de plantilla en función de los parámetros de entrada
