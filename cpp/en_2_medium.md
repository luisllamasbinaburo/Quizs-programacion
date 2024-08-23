¿Cómo se pasa un arreglo a una función en C++?
- `void funcion(int arr[])`
- `void funcion(int arr[10])`
- `void funcion(arr int[])`

¿Qué es una referencia en C++?
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

¿Cuál es la forma correcta de manejar excepciones en C++?
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

¿Qué es un constructor en C++?
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

¿Qué significa "polimorfismo" en C++?
- La capacidad de una función o método para tener diferentes comportamientos en función del tipo de objeto
- La capacidad de una variable para tomar diferentes valores
- La capacidad de una clase para ser instanciada de múltiples maneras

¿Cómo se usa el operador `->` en C++?
- Para acceder a miembros de un objeto a través de un puntero
- Para declarar un puntero a un miembro de clase
- Para sobrecargar un operador

¿Qué es un destructor en C++?
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

¿Cómo se usa el `static_cast` en C++?
- Para realizar una conversión explícita entre tipos
- Para convertir punteros en referencias
- Para definir una clase estática

¿Qué es un template en C++?
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

¿Qué es una función `inline` en C++?
- Una función cuyo código se inserta en el lugar donde se llama
- Una función que no tiene parámetros
- Una función que retorna un valor `void`

¿Cómo se define una clase abstracta en C++?
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

¿Cómo se realiza un `dynamic_cast` en C++?
- Usando `dynamic_cast` para convertir punteros o referencias a tipos derivados
- Usando `static_cast` para tipos no relacionados
- Usando `reinterpret_cast` para tipos desconocidos

¿Qué es un puntero a miembro en C++?
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

¿Cómo se utiliza el operador `::` en C++?
- Para acceder a miembros estáticos y métodos de clase
- Para definir nuevas funciones dentro de una clase
- Para eliminar variables de la memoria

¿Qué hace la función `sizeof` en C++?
- Devuelve el tamaño en bytes de una variable o tipo de datos
- Devuelve el número de elementos en un arreglo
- Devuelve el valor de una variable