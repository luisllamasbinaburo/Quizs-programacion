¿Cómo se pasa un arreglo a una función?
- `void funcion(int arr[])`
- `void funcion(int arr[10])`
- `void funcion(arr int[])`

¿Qué es una referencia?
- Un alias para otra variable
- Un tipo de puntero
- Una función especial

¿Cuál es la diferencia entre `++i` y `i++` en un bucle `for`?
- No hay diferencia en un bucle `for`, ambos funcionan igual
- `++i` incrementa antes de usar el valor; `i++` incrementa después
- `++i` incrementa en dos pasos; `i++` en uno

¿Cómo se implementa un operador de sobrecarga en una clase?
- Definiendo una función con el nombre `operator+`
- Usando una función normal con el nombre del operador
- Declarando una función miembro llamada `add`

¿Cuál es la forma correcta de manejar excepciones?
- `try { // código } catch (excepción) { // manejo }`
- `handle { // código } catch (excepción) { // manejo }`
- `error { // código } except (excepción) { // manejo }`

¿Cómo se define una función miembro estática en una clase?
- `static void funcion()`
- `void static funcion()`
- `static function void()`

¿Cómo se accede a un miembro de una clase desde fuera de la clase?
- Usando el operador de acceso `.` o `->`
- Usando el operador `::`
- Usando el operador `[]`

¿Qué es un constructor?
- Una función especial que se llama al crear un objeto
- Una función que retorna un valor por defecto
- Un método que destruye un objeto

¿Cómo se inicializa una lista de inicialización en un constructor?
- `Clase() : miembro1(valor1), miembro2(valor2) {}`
- `Clase() { miembro1 = valor1; miembro2 = valor2; }`
- `Clase() { initialize(miembro1, valor1, miembro2, valor2); }`

¿Qué es una clase base y una clase derivada en la herencia?
- La clase base es la que se hereda, y la clase derivada es la que hereda
- La clase base es la que no tiene miembros, y la clase derivada es la que tiene
- La clase base y derivada son sinónimos en herencia

¿Qué significa "polimorfismo"?
- La capacidad de una función o método para tener diferentes comportamientos en función del tipo de objeto
- La capacidad de una variable para tomar diferentes valores
- La capacidad de una clase para ser instanciada de múltiples maneras

¿Cómo se usa el operador `->`?
- Para acceder a miembros de un objeto a través de un puntero
- Para declarar un puntero a un miembro de clase
- Para sobrecargar un operador

¿Qué es un destructor?
- Una función especial que se llama al destruir un objeto
- Una función que inicializa un objeto
- Una función que define el valor por defecto de una clase

¿Cómo se define un método virtual en una clase base?
- `virtual void metodo()`
- `void virtual metodo()`
- `virtual void metodo() = 0;`

¿Cuál es la diferencia entre `public`, `protected`, y `private` en la encapsulación?
- `public` es accesible desde fuera, `protected` solo desde clases derivadas, `private` solo desde la propia clase
- `public` es accesible solo desde la propia clase, `protected` desde fuera, `private` desde cualquier parte
- `public` y `protected` son accesibles desde fuera, `private` desde la propia clase y derivadas

¿Cómo se usa el `static_cast`?
- Para realizar una conversión explícita entre tipos
- Para convertir punteros en referencias
- Para definir una clase estática

¿Qué es un template?
- Una característica que permite definir funciones y clases genéricas
- Un método para definir plantillas de diseño
- Un tipo especial de variable

¿Cómo se definen variables miembro constantes en una clase?
- `const int miembro;`
- `int const miembro;`
- `const miembro;`

¿Cómo se accede a los miembros estáticos de una clase?
- Usando el nombre de la clase seguido de `::`
- Usando el operador `->`
- Usando el operador `.`

¿Cómo se define una función sobrecargada?
- Con el mismo nombre pero diferente lista de parámetros
- Con un nombre diferente en la misma clase
- Con un tipo de retorno diferente en la misma clase

¿Qué es una función `inline`?
- Una función cuyo código se inserta en el lugar donde se llama
- Una función que no tiene parámetros
- Una función que retorna un valor `void`

¿Cómo se define una clase abstracta?
- Incluyendo al menos un método virtual puro
- Incluyendo solo métodos públicos
- Incluyendo solo constructores

¿Cómo se declaran variables miembro en una clase sin inicializarlas?
- Solo declarando el tipo y nombre
- Declarando y asignando un valor por defecto
- Solo con una inicialización en el constructor

¿Cómo se define un método de clase que no necesita acceso a miembros de instancia?
- Marcándolo como `static`
- Marcándolo como `const`
- Declarando el método como `public`

¿Cómo se realiza un `dynamic_cast`?
- Usando `dynamic_cast` para convertir punteros o referencias a tipos derivados
- Usando `static_cast` para tipos no relacionados
- Usando `reinterpret_cast` para tipos desconocidos

¿Qué es un puntero a miembro?
- Un puntero que apunta a un miembro de una clase
- Un puntero que apunta a una función global
- Un puntero que apunta a una dirección de memoria específica

¿Cómo se implementa la sobrecarga del operador `==` en una clase?
- Definiendo una función `bool operator==(const Clase& otra) const`
- Definiendo una función `bool igual(const Clase& otra) const`
- Definiendo una función `bool operator=(const Clase& otra) const`

¿Qué es la "encapsulación" en programación orientada a objetos?
- El ocultamiento de datos y la exposición de métodos para interactuar con ellos
- La herencia de una clase a otra
- La creación de múltiples instancias de una clase

¿Cómo se utiliza el operador `::`?
- Para acceder a miembros estáticos y métodos de clase
- Para definir nuevas funciones dentro de una clase
- Para eliminar variables de la memoria

¿Qué hace la función `sizeof`?
- Devuelve el tamaño en bytes de una variable o tipo de datos
- Devuelve el número de elementos en un arreglo
- Devuelve el valor de una variable

¿Cuál de las siguientes palabras clave se utiliza para definir una función miembro en una clase?
- void
- int
- for

¿Qué operador se usa para acceder a los miembros de una estructura a través de un puntero?
- ->
- .
- &

¿Qué método de la clase `std::vector` se utiliza para agregar un elemento al final?
- push_back
- insert
- erase

¿Cuál es la manera correcta de declarar un puntero a una función que recibe un entero y devuelve un `double`?
- double (*func)(int)
- double func(int*)
- double *func(int)

¿Cuál es la diferencia principal entre `std::vector` y `std::list`?
- `std::vector` permite acceso aleatorio, mientras que `std::list` no
- `std::list` permite acceso aleatorio, mientras que `std::vector` no
- Ambos permiten acceso aleatorio

¿Qué función se usa para liberar memoria dinámica?
- delete
- free
- release

¿Qué operador se usa para sobrecargar la suma de dos objetos?
- +
- &
- *

¿Cuál es la forma correcta de inicializar un arreglo de enteros con 10 elementos?
- int arr[10]
- int arr = new int[10]
- int arr(10)

¿Qué significa la palabra clave `virtual` en una función miembro de una clase?
- Permite la polimorfia
- Define una función estática
- Indica que la función es privada

¿Cuál de las siguientes es una forma correcta de definir una constante en una clase?
- static const int VALUE = 10
- const static int VALUE = 10
- int const static VALUE = 10

¿Cómo se declara una variable estática dentro de una función miembro?
- static int count
- int static count
- static count int

¿Cuál es el resultado de intentar acceder a un índice fuera de los límites de un arreglo?
- Comportamiento indefinido
- Se lanza una excepción estándar
- El programa se detiene con un error

¿Qué operador se utiliza para definir el constructor de una clase?
- ::
- ~
- =

¿Qué palabra clave se usa para evitar la herencia de una clase base?
- final
- private
- protected

¿Cuál es la forma correcta de definir una función miembro dentro de una clase?
- void func() {}
- func void() {}
- void func() ;

¿Qué tipo de dato se usa para representar una variable que puede tener solo dos valores posibles?
- bool
- char
- int

¿Cómo se declara una variable miembro constante en una clase?
- const int value
- int const value
- value const int

¿Cuál es la manera correcta de definir un template de clase que toma un tipo genérico?
- template <typename T>
- template <class T>
- template <T>

¿Cuál es el propósito de la palabra clave `protected` en una clase?
- Permitir acceso a clases derivadas
- Restringir acceso solo a métodos estáticos
- Hacer que la variable sea constante

¿Qué operador se usa para acceder a los miembros de un objeto a través de un puntero?
- ->
- .
- ::

¿Cómo se inicializa una variable `std::string` con una cadena literal?
- std::string str = "hello"
- std::string str("hello")
- std::string str("hello");

¿Cuál es la manera correcta de pasar un objeto por referencia a una función para evitar la copia?
- void func(MyClass& obj)
- void func(MyClass obj&)
- void func(MyClass* obj)

¿Cómo se define una función de miembro en línea dentro de una clase?
- inline void func() {}
- void inline func() {}
- void func() inline {}

¿Qué palabra clave se usa para evitar la redefinición de funciones en una clase derivada?
- override
- virtual
- abstract

¿Qué biblioteca estándar se utiliza para manejar la entrada y salida de archivos?
- fstream
- iostream
- cstdlib

¿Qué hace la función `std::sort`?
- Ordena los elementos de un contenedor
- Busca un elemento en un contenedor
- Elimina duplicados de un contenedor

¿Cuál es la función de `static_cast`?
- Realiza una conversión segura entre tipos
- Realiza una conversión de tipo implícita
- Realiza una conversión forzada sin chequeo

¿Qué significa el término `RAII` en el contexto de C++?
- Gestión de recursos mediante la duración de vida del objeto
- Acceso aleatorio a índices de elementos
- Inicialización automática de arreglos