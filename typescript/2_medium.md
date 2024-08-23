¿Cuál de las siguientes opciones permite crear un tipo personalizado?
- type Alias = tipo
- let Alias: tipo
- var Alias = tipo

¿Qué es un "type assertion"?
- Una forma de decirle al compilador que confíe en que un valor es de un tipo específico
- Una forma de crear un tipo de datos personalizado
- Una forma de definir una interfaz

¿Cómo se puede evitar que una propiedad de un objeto sea modificable?
- Usando `readonly` en la declaración de la propiedad
- Usando `private` en la declaración de la propiedad
- Usando `static` en la declaración de la propiedad

¿Cómo se define un tipo de función que acepta un parámetro y no retorna nada?
- (parametro: tipo) => void
- (parametro: tipo) => null
- (parametro: tipo) => tipo

¿Qué palabra clave se usa para definir una función que puede retornar diferentes tipos de valores?
- union
- any
- type

¿Cómo se declara una clase abstracta?
- abstract class Nombre {}
- class abstract Nombre {}
- class Nombre abstract {}

¿Qué palabra clave se usa para indicar que un método debe ser implementado en una clase derivada?
- abstract
- virtual
- required

¿Cómo se puede definir un tipo de dato que puede ser una cadena o un número?
- type Nombre = string | number
- type Nombre = string & number
- type Nombre = (string | number)

¿Qué palabra clave se usa para definir un parámetro predeterminado en una función?
- =
- default
- static

¿Qué tipo de dato es `unknown`?
- Un tipo de dato que no se conoce y requiere comprobación de tipo antes de su uso
- Un tipo de dato que siempre es `null`
- Un tipo de dato que acepta cualquier valor

¿Cómo se puede asegurar que una función retorna un valor de tipo específico?
- Usando una declaración de tipo de retorno
- Usando una declaración de variable global
- Usando `any` en la declaración de la función

¿Cuál es la forma correcta de crear un tipo de dato para una función que puede aceptar un número de parámetros variables?
- (...parametros: tipo[]) => tipo
- (parametros: tipo) => tipo
- (parametros: tipo[]) => tipo

¿Cómo se definen múltiples tipos de datos para una variable?
- type Nombre = tipo1 | tipo2
- let Nombre: tipo1, tipo2
- let Nombre: tipo1 & tipo2

¿Qué significa la palabra clave `super` en una clase TypeScript?
- Se usa para acceder a métodos y propiedades de la clase base
- Se usa para definir una clase base
- Se usa para implementar una interfaz

¿Cómo se indica que un parámetro de una función es obligatorio?
- No se usa el símbolo `?` en la declaración del parámetro
- Se usa el símbolo `!` en la declaración del parámetro
- Se usa `default` en la declaración del parámetro

¿Cuál es la sintaxis correcta para crear una interfaz con métodos?
- interface Nombre { metodo(): tipo }
- class Nombre { metodo(): tipo }
- type Nombre = { metodo(): tipo }

¿Cómo se puede limitar los valores posibles de una propiedad a un conjunto específico?
- Usando un tipo literal
- Usando una interfaz
- Usando `any`

¿Qué es un "enum"?
- Un conjunto de valores nombrados
- Un tipo de dato que acepta cualquier valor
- Una estructura para manejar tipos de datos complejos

¿Cómo se declara una clase que implementa múltiples interfaces?
- class Nombre implements Interface1, Interface2 {}
- class Nombre extends Interface1, Interface2 {}
- class Nombre uses Interface1, Interface2 {}

¿Qué tipo de dato representa un objeto sin propiedades?
- {}
- []
- null

¿Cómo se puede definir un tipo de dato opcional en una interfaz?
- propiedad?: tipo
- propiedad! tipo
- propiedad: tipo?

¿Qué palabra clave se usa para crear un tipo que se basa en otro?
- extends
- implements
- inherits

¿Cómo se utiliza la palabra clave `as`?
- Para realizar una afirmación de tipo
- Para declarar un nuevo tipo
- Para crear una clase

¿Cómo se especifica un tipo de retorno en una función de flecha?
- const funcion = (parametro: tipo): tipo => {}
- const funcion = (parametro: tipo) => tipo
- const funcion = (parametro) => tipo

¿Qué significa la palabra clave `public` en una clase de TypeScript?
- La propiedad o método es accesible desde cualquier parte
- La propiedad o método es accesible solo dentro de la clase
- La propiedad o método es accesible solo en la clase derivada

¿Cómo se puede hacer que una propiedad de una clase sea privada?
- Usando la palabra clave `private`
- Usando la palabra clave `protected`
- Usando la palabra clave `readonly`

¿Cómo se definen propiedades opcionales en una interfaz?
- Propiedad?: tipo
- Propiedad! tipo
- Propiedad: tipo?

¿Qué tipo de dato se usa para representar valores indefinidos?
- undefined
- null
- any

¿Qué palabra clave se usa para crear un tipo genérico?
- <T>
- <type>
- <generic>

¿Cómo se define un tipo de dato que puede ser un número o una cadena?
- type Nombre = number | string
- type Nombre = number & string
- type Nombre = (number | string)

¿Qué es una "tuple"?
- Un array con un número fijo de elementos y tipos específicos
- Un array sin tipos específicos
- Un objeto con propiedades opcionales

¿Cómo se accede a un tipo dentro de una tupla?
- Tuple[índice]
- Tuple.get(índice)
- Tuple.índice

¿Qué palabra clave se usa para declarar una interfaz?
- interface
- type
- class

¿Cómo se declara un método en una interfaz que debe ser implementado por una clase?
- metodo(): tipo
- metodo(tipo): tipo
- metodo: tipo

¿Qué es una "namespace"?
- Un contenedor para agrupar variables y funciones relacionadas
- Un tipo de dato
- Una función especial

¿Cómo se especifica un tipo para una propiedad en una interfaz?
- propiedad: tipo
- propiedad? tipo
- propiedad: (tipo)

¿Cómo se realiza la conversión de un tipo?
- Usando `as` para la conversión de tipo
- Usando `convert`
- Usando `cast`

¿Qué es un "decorador"?
- Una función que modifica la clase o método al que se aplica
- Un tipo de dato especial
- Un operador para la manipulación de tipos

¿Cómo se declara un tipo para una función que acepta una función como parámetro?
- type Nombre = (param: (arg: tipo) => tipo) => tipo
- type Nombre = (param: Function) => tipo
- type Nombre = (param: tipo) => Function

¿Cómo se define una clase que implementa una interfaz?
- class Nombre implements Interface {}
- class Nombre extends Interface {}
- class Nombre uses Interface {}

¿Qué palabra clave se usa para definir propiedades accesibles solo dentro de la clase base?
- protected
- private
- public

¿Cómo se define un tipo de dato que no permite valores nulos o indefinidos?
- NonNullable<tipo>
- Required<tipo>
- Exclude<tipo, null>

¿Qué es una "generics"?
- Un mecanismo para crear tipos reutilizables
- Un tipo de dato específico
- Una función con parámetros predeterminados

¿Cómo se puede garantizar que una propiedad de una clase es solo de lectura?
- Usando `readonly`
- Usando `static`
- Usando `private`

¿Qué es una "intersección de tipos"?
- Un tipo que combina múltiples tipos en uno solo
- Un tipo que excluye valores
- Un tipo que solo acepta valores nulos

¿Cómo se define un tipo de dato complejo utilizando una interfaz?
- interface Nombre { propiedad: tipo }
- class Nombre { propiedad: tipo }
- type Nombre = { propiedad: tipo }

¿Qué significa `never`?
- Un tipo que representa valores que nunca ocurren
- Un tipo que acepta cualquier valor
- Un tipo que representa valores indefinidos

¿Cómo se declara un parámetro de una función como opcional?
- parametro?: tipo
- parametro! tipo
- parametro: tipo?

¿Cómo se define una función que acepta un número variable de argumentos?
- (...args: tipo[]) => tipo
- (args: tipo[]) => tipo
- (args: tipo) => tipo

¿Qué es una "interface extending"?
- Una interfaz que extiende de otra interfaz
- Una clase que hereda de una interfaz
- Un tipo de dato que hereda de una interfaz

¿Cómo se define un tipo que puede ser tanto un número como una cadena y también puede ser `null`?
- type Nombre = number | string | null
- type Nombre = number & string | null
- type Nombre = (number | string) & null

¿Qué significa la palabra clave `export`?
- Hace que un módulo o variable sea accesible fuera del archivo
- Declara una variable local
- Define un tipo de dato global

¿Cómo se define un alias para una función?
- type Nombre = (param: tipo) => tipo
- function Nombre = (param: tipo) => tipo
- let Nombre = (param: tipo) => tipo

¿Qué significa `Partial<T>`?
- Un tipo que hace todas las propiedades de `T` opcionales
- Un tipo que hace todas las propiedades de `T` obligatorias
- Un tipo que excluye algunas propiedades de `T`

¿Cómo se declara un tipo que es un subconjunto de otro tipo?
- type Subtipo = Pick<Tipo, 'propiedad'>
- type Subtipo = Omit<Tipo, 'propiedad'>
- type Subtipo = Exclude<Tipo, 'propiedad'>

¿Cómo se crea una interfaz que hereda de múltiples interfaces?
- interface Nombre extends Interface1, Interface2 {}
- class Nombre extends Interface1, Interface2 {}
- type Nombre = Interface1 & Interface2

¿Qué palabra clave se usa para crear un tipo de dato que se basa en otro tipo pero con algunas propiedades excluidas?
- Omit
- Exclude
- Pick