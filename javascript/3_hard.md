¿Qué método se usa para obtener una lista de propiedades enumerables de un objeto?
- Object.keys
- Object.values
- Object.entries

¿Cuál es el comportamiento del método `Object.freeze()`?
- Previene la modificación de propiedades del objeto
- Permite la eliminación de propiedades del objeto
- Clona el objeto en un nuevo objeto

¿Qué método de array se usa para encontrar el primer elemento que cumple una condición especificada por una función?
- find
- filter
- some

¿Cuál es la diferencia principal entre `Object.assign()` y el operador de propagación (`...`)?
- `Object.assign()` realiza una copia superficial mientras que el operador de propagación puede hacer una copia profunda
- El operador de propagación hace una copia superficial mientras que `Object.assign()` realiza una copia profunda
- `Object.assign()` no puede copiar objetos anidados mientras que el operador de propagación sí

¿Cómo se puede acceder a una propiedad de un objeto utilizando un string como nombre de la propiedad?
- obj[propertyName]
- obj.propertyName
- obj->propertyName

¿Qué método se usa para obtener la clase interna de un objeto?
- Object.prototype.toString.call(obj)
- obj.getClass()
- obj.constructor.name

¿Qué característica de las funciones flecha (arrow functions) las hace diferentes de las funciones tradicionales?
- No tienen su propio `this` y usan el `this` del contexto léxico
- Son más rápidas en ejecución
- Permiten una mayor cantidad de parámetros

¿Cuál es el propósito del método `Reflect.apply()`?
- Permite invocar una función con un determinado contexto y argumentos
- Crea una nueva función a partir de una función existente
- Cambia el contexto de `this` en una función

¿Cómo se puede garantizar que una función es ejecutada solo una vez?
- Utilizando un patrón de diseño de función única o un `Set`
- Llamando a la función dentro de un bucle
- Definiendo la función como `async`

¿Qué función de `Promise` se usa para manejar múltiples promesas en paralelo?
- Promise.all
- Promise.race
- Promise.any

¿Qué método se utiliza para crear una función que se ejecuta solo después de un cierto número de llamadas?
- debounce
- throttle
- once

¿Cuál es el resultado de `Object.getPrototypeOf(Object.create(null))`?
- null
- Object.prototype
- undefined

¿Qué método se usa para combinar varios arreglos en uno solo sin modificar los arreglos originales?
- concat
- push
- merge

¿Cuál es la diferencia entre `null` y `undefined`?
- `null` es un valor asignado explícitamente, mientras que `undefined` indica la ausencia de asignación
- Ambos son valores que indican la ausencia de valor
- `undefined` es un valor asignado explícitamente, mientras que `null` indica la ausencia de asignación

¿Cómo se puede verificar si una función es constructora (es decir, se puede usar con el operador `new`)?
- Comprobando si la función tiene una propiedad `prototype`
- Verificando si la función tiene un nombre
- Evaluando si la función retorna un valor

¿Qué método se usa para definir un método estático en una clase?
- static
- prototype
- instance

¿Cuál es el propósito del método `Symbol.for()`?
- Crear o recuperar un símbolo global que puede ser compartido entre diferentes partes del código
- Crear un nuevo símbolo único para cada llamada
- Convertir un símbolo en una cadena de texto

¿Qué técnica se usa para hacer una función que retorne otra función?
- Currying
- Memoization
- Closures

¿Cómo se puede manejar errores en una promesa utilizando `async/await`?
- Usando `try` y `catch`
- Usando `finally`
- Usando `resolve` y `reject`

¿Qué método se usa para cambiar el contexto de una función?
- bind
- apply
- call

¿Qué operador se usa para definir un getter o setter en una clase?
- get/set
- define/get
- function/get

¿Cuál es el comportamiento del método `Array.prototype.flat()`?
- Aplana un array anidado en un solo nivel
- Crea un nuevo array sin elementos duplicados
- Ordena los elementos de un array

¿Qué diferencia existe entre `Object.seal()` y `Object.preventExtensions()`?
- `Object.seal()` previene la adición de nuevas propiedades y marca las propiedades existentes como no configurables, mientras que `Object.preventExtensions()` solo previene la adición de nuevas propiedades
- `Object.seal()` solo previene la adición de nuevas propiedades, mientras que `Object.preventExtensions()` también previene la eliminación de propiedades
- `Object.seal()` no permite modificar propiedades existentes, mientras que `Object.preventExtensions()` permite modificar las propiedades existentes

¿Cuál es el propósito del método `Object.create()`?
- Crear un nuevo objeto con el prototipo especificado
- Clonar un objeto existente
- Definir una nueva clase

¿Qué función se usa para realizar una operación sobre cada elemento de un array y devolver un nuevo array con los resultados?
- map
- reduce
- forEach

¿Cómo se puede manejar el error de una promesa utilizando `Promise.all()`?
- `Promise.all()` retorna una promesa que se rechaza si alguna de las promesas en el array es rechazada
- `Promise.all()` maneja el error sin rechazar ninguna promesa
- `Promise.all()` retorna una promesa que se resuelve si todas las promesas en el array son resueltas

¿Qué método se usa para obtener una lista de pares clave-valor de un objeto?
- Object.entries
- Object.keys
- Object.values

¿Cuál es la diferencia entre `Object.prototype.hasOwnProperty()` y `in` en la verificación de propiedades de un objeto?
- `Object.prototype.hasOwnProperty()` verifica si la propiedad es propia del objeto, mientras que `in` verifica si la propiedad existe en el objeto o en su cadena de prototipos
- `in` verifica si la propiedad es propia del objeto, mientras que `Object.prototype.hasOwnProperty()` verifica si la propiedad existe en el objeto o en su cadena de prototipos
- Ambos verifican si la propiedad es propia del objeto o en su cadena de prototipos

¿Qué método de `Proxy` se usa para interceptar operaciones de lectura de propiedades en un objeto?
- get
- set
- apply

¿Cuál es la diferencia entre `Object.defineProperty()` y `Object.defineProperties()`?
- `Object.defineProperty()` define una sola propiedad, mientras que `Object.defineProperties()` define múltiples propiedades
- `Object.defineProperties()` define una sola propiedad, mientras que `Object.defineProperty()` define múltiples propiedades
- Ambos métodos definen propiedades, pero `Object.defineProperty()` es para propiedades privadas y `Object.defineProperties()` para públicas

¿Qué método de `Reflect` se utiliza para obtener la lista de propiedades de un objeto?
- Reflect.ownKeys
- Reflect.getOwnPropertyNames
- Reflect.keys

¿Cómo se puede realizar una importación dinámica de módulos?
- import()
- require()
- fetch()

¿Qué operador se usa para declarar una propiedad computada en un objeto literal?
- []
- ()
- {}

¿Qué diferencia principal hay entre `Object.getOwnPropertyDescriptor()` y `Object.getOwnPropertyDescriptors()`?
- `Object.getOwnPropertyDescriptor()` devuelve un descriptor de una sola propiedad, mientras que `Object.getOwnPropertyDescriptors()` devuelve descriptores de todas las propiedades
- `Object.getOwnPropertyDescriptors()` devuelve un descriptor de una sola propiedad, mientras que `Object.getOwnPropertyDescriptor()` devuelve descriptores de todas las propiedades
- Ambos métodos devuelven descriptores de propiedades individuales, pero `Object.getOwnPropertyDescriptors()` es para propiedades anidadas

¿Cómo se puede utilizar `WeakMap` para mantener referencias a objetos sin evitar su recolección de basura?
- `WeakMap` mantiene referencias débiles a los objetos, permitiendo que sean recolectados por el garbage collector
- `WeakMap` mantiene referencias fuertes a los objetos, evitando su recolección de basura
- `WeakMap` crea una referencia a los objetos sólo si están en el mismo contexto

¿Qué función de `Intl` se usa para formatear números de acuerdo con las reglas locales?
- Intl.NumberFormat
- Intl.DateTimeFormat
- Intl.PluralRules

¿Cuál es la diferencia entre `Object.prototype.hasOwnProperty.call()` y `in` para verificar la existencia de una propiedad?
- `Object.prototype.hasOwnProperty.call()` verifica si la propiedad es propia del objeto, mientras que `in` verifica en el prototipo también
- `in` verifica si la propiedad es propia del objeto, mientras que `Object.prototype.hasOwnProperty.call()` verifica en el prototipo también
- Ambos métodos verifican si la propiedad existe en el prototipo del objeto

¿Qué método se usa para definir una propiedad de solo lectura en un objeto?
- Object.defineProperty
- Object.create
- Object.seal

¿Cuál es el comportamiento de `Array.prototype.flatMap()` en comparación con `Array.prototype.map()` seguido de `Array.prototype.flat()`?
- `flatMap()` combina la funcionalidad de `map()` y `flat()` en una sola operación
- `flatMap()` primero aplana el array y luego aplica `map()`
- `flatMap()` es equivalente a `map()` sin aplanar el array

¿Cómo se maneja el caso en el que una función generadora se detiene sin ser completada?
- Usando el método `return` en la función generadora
- Usando la función `next()` sin argumentos
- La función generadora se reinicia automáticamente

¿Cuál es el propósito del método `Object.getPrototypeOf()`?
- Obtener el prototipo de un objeto
- Crear un nuevo prototipo para un objeto
- Cambiar el prototipo de un objeto

¿Qué técnica se usa para encapsular el estado privado en una clase de JavaScript?
- Usando campos privados con el símbolo `#`
- Usando el patrón módulo
- Usando `Object.create`

¿Qué método de `Promise` se usa para ejecutar un conjunto de promesas y devolver la primera que se resuelva o se rechace?
- Promise.race
- Promise.all
- Promise.allSettled

¿Cuál es el propósito del operador `??` (nullish coalescing)?
- Proveer un valor por defecto cuando el valor es `null` o `undefined`
- Proveer un valor por defecto cuando el valor es `falsy`
- Proveer un valor por defecto solo cuando el valor es `false`

¿Cómo se puede controlar el acceso a los métodos y propiedades de una clase en JavaScript usando `Symbol`?
- Definiendo métodos y propiedades con claves `Symbol`
- Usando `Symbol` en el constructor de la clase
- Aplicando `Symbol` a los métodos públicos de la clase

¿Qué método se usa para crear una nueva instancia de `Set` que contiene todos los valores únicos de un array?
- new Set(array)
- array.toSet()
- Set.from(array)

¿Cómo se pueden crear y usar `WeakSet` para manejar un conjunto de objetos de manera que los objetos puedan ser recolectados por el garbage collector?
- `WeakSet` mantiene referencias débiles a los objetos, permitiendo su recolección por el garbage collector
- `WeakSet` mantiene referencias fuertes a los objetos para evitar su recolección
- `WeakSet` solo puede manejar un número fijo de objetos

¿Qué función de `URLSearchParams` se usa para obtener el valor de un parámetro de la consulta de URL?
- get()
- find()
- retrieve()

¿Qué diferencia hay entre `Object.setPrototypeOf()` y `Object.create()`?
- `Object.setPrototypeOf()` cambia el prototipo de un objeto existente, mientras que `Object.create()` crea un nuevo objeto con el prototipo especificado
- `Object.create()` cambia el prototipo de un objeto existente, mientras que `Object.setPrototypeOf()` crea un nuevo objeto con el prototipo especificado
- Ambos métodos crean nuevos prototipos para los objetos

¿Cómo se implementa un iterador personalizado en una clase de JavaScript?
- Implementando el método `[Symbol.iterator]`
- Usando el método `iterator()`
- Definiendo el método `next()`

¿Qué operador se usa para extender los métodos de una clase?
- super
- extend
- this

¿Cuál es la función de `Intl.Collator`?
- Comparar cadenas de acuerdo con la configuración local y las reglas de colación
- Formatear números y fechas de acuerdo con la configuración local
- Traducir cadenas de un idioma a otro

¿Qué método de `Object` se usa para obtener todos los descriptores de propiedades de un objeto?
- Object.getOwnPropertyDescriptors
- Object.getPropertyDescriptors
- Object.getAllPropertyDescriptors

¿Cómo se usa `Proxy` para interceptar la asignación de valores a las propiedades de un objeto?
- Implementando el método `set`
- Implementando el método `get`
- Implementando el método `apply`

¿Cuál es la diferencia entre `Promise.allSettled()` y `Promise.all()`?
- `Promise.allSettled()` espera a que todas las promesas se completen, ya sea resueltas o rechazadas, mientras que `Promise.all()` se rechaza si alguna promesa es rechazada
- `Promise.all()` espera a que todas las promesas se completen, ya sea resueltas o rechazadas, mientras que `Promise.allSettled()` se rechaza si alguna promesa es rechazada
- Ambos métodos esperan a que todas las promesas se completen de la misma manera

¿Qué método de `Reflect` se usa para cambiar el contexto de `this` al invocar una función?
- Reflect.apply
- Reflect.bind
- Reflect.call