¿Cómo se declara un tipo que combina dos tipos, asegurando que las propiedades de ambos tipos estén presentes?
- type Combined = Type1 & Type2
- type Combined = Type1 | Type2
- type Combined = Type1 + Type2

¿Qué hace el tipo `ReturnType<T>`?
- Obtiene el tipo de retorno de una función tipo `T`
- Obtiene el tipo del primer parámetro de una función tipo `T`
- Obtiene el tipo del segundo parámetro de una función tipo `T`

¿Cómo se define un tipo condicional?
- type Result = Condition extends TrueType ? TypeA : TypeB
- type Result = Condition ? TypeA : TypeB
- type Result = Condition ? TypeA & TypeB : TypeC

¿Qué es un tipo mapeado?
- Un tipo que se construye a partir de otro tipo aplicando una transformación a cada propiedad
- Un tipo que combina múltiples tipos en uno solo
- Un tipo que se define como un conjunto de propiedades opcionales

¿Cómo se define un tipo que acepta un número de parámetros variables de diferentes tipos?
- (...args: [Tipo1, Tipo2, ...]) => Tipo
- (args: [Tipo1, Tipo2, ...]) => Tipo
- (...args: Tipo[]) => Tipo

¿Qué es el tipo `keyof`?
- Un operador que obtiene un conjunto de claves de un tipo
- Un tipo que combina todas las claves posibles
- Un tipo que se usa para definir claves opcionales en un objeto

¿Cómo se define un tipo que es la intersección de una propiedad opcional y una propiedad obligatoria?
- type Combined = { prop1?: Tipo1 } & { prop2: Tipo2 }
- type Combined = { prop1: Tipo1 } | { prop2: Tipo2 }
- type Combined = { prop1?: Tipo1, prop2?: Tipo2 }

¿Qué significa `Exclude<T, U>`?
- Un tipo que excluye de `T` los tipos que están en `U`
- Un tipo que incluye todos los tipos en `T` que están en `U`
- Un tipo que combina `T` y `U` en un nuevo tipo

¿Cómo se define un tipo que puede ser una promesa de un tipo específico?
- Promise<Tipo>
- Future<Tipo>
- Async<Tipo>

¿Qué hace la utilidad `Partial<T>`?
- Convierte todas las propiedades de `T` en opcionales
- Convierte todas las propiedades de `T` en obligatorias
- Convierte algunas propiedades de `T` en opcionales

¿Cómo se declara un tipo que representa un objeto cuyas propiedades son todas funciones?
- type Funciones = { [key: string]: () => Tipo }
- type Funciones = { [key: string]: Function }
- type Funciones = { [key: string]: Tipo }

¿Qué es un tipo "union" y cómo se utiliza?
- Un tipo que permite un valor de uno de varios tipos posibles
- Un tipo que permite valores combinados de múltiples tipos
- Un tipo que restringe un valor a uno de varios tipos predefinidos

¿Cómo se define un tipo que es una función que retorna otra función?
- type FunctionReturningFunction = (param: Tipo) => () => Tipo
- type FunctionReturningFunction = (param: Tipo) => Tipo
- type FunctionReturningFunction = () => (param: Tipo) => Tipo

¿Qué es un tipo "inferido" y cómo se usa?
- Un tipo que se determina automáticamente a partir de la inferencia de tipo del compilador
- Un tipo que se define explícitamente en el código
- Un tipo que solo se usa para funciones anónimas

¿Cómo se define un tipo que es un objeto con propiedades de tipos genéricos?
- type GenericObject<T> = { [key: string]: T }
- type GenericObject<T> = { key: T }
- type GenericObject<T> = { key: T[] }

¿Qué significa `Readonly<T>`?
- Un tipo que convierte todas las propiedades de `T` en solo lectura
- Un tipo que hace que todas las propiedades de `T` sean opcionales
- Un tipo que elimina todas las propiedades de `T`

¿Cómo se define un tipo que es una función que acepta y retorna una función?
- type Func = (fn: (arg: Tipo) => Tipo) => (arg: Tipo) => Tipo
- type Func = (fn: Tipo) => (arg: Tipo) => Tipo
- type Func = (fn: (arg: Tipo) => Tipo) => Tipo

¿Qué hace el tipo `ThisType<T>`?
- Define el tipo de `this` en el contexto de un objeto
- Define el tipo de retorno de una función
- Define el tipo de los parámetros de una función

¿Cómo se declara un tipo que es una función que acepta un número variable de parámetros opcionales?
- (...args?: Tipo[]) => Tipo
- (args?: Tipo[]) => Tipo
- (...args: [Tipo?]) => Tipo

¿Qué hace el tipo `Awaited<T>`?
- Extrae el tipo de valor que una promesa `T` resolverá
- Extrae el tipo de una función que retorna una promesa
- Extrae el tipo de un parámetro de una función asíncrona

¿Cómo se define un tipo que es un subconjunto de un objeto?
- type Subtipo = Pick<Tipo, 'propiedad'>
- type Subtipo = Omit<Tipo, 'propiedad'>
- type Subtipo = Exclude<Tipo, 'propiedad'>

¿Qué es un "conditional type" y cómo se usa?
- Un tipo que selecciona entre dos tipos basándose en una condición
- Un tipo que permite la combinación de varios tipos
- Un tipo que se usa para definir valores opcionales

¿Cómo se define un tipo que es una función que acepta un argumento y retorna un tipo de función diferente?
- type Func = (param: Tipo) => (arg: OtroTipo) => RetornoTipo
- type Func = (param: Tipo) => RetornoTipo
- type Func = (param: Tipo) => (arg: Tipo) => OtroTipo

¿Qué significa `Extract<T, U>`?
- Un tipo que extrae de `T` los tipos que están en `U`
- Un tipo que excluye de `T` los tipos que están en `U`
- Un tipo que combina `T` y `U` en un nuevo tipo

¿Cómo se declara un tipo que es un objeto con propiedades opcionales y predeterminadas?
- type Obj = { prop?: Tipo } & { propDefault?: Tipo }
- type Obj = { prop?: Tipo, propDefault: Tipo }
- type Obj = { prop: Tipo? } & { propDefault: Tipo }

¿Qué es un tipo de "template literal"?
- Un tipo que se construye a partir de una cadena de texto con interpolaciones
- Un tipo que define una cadena de texto fija
- Un tipo que combina cadenas de texto y números

¿Cómo se define un tipo que representa una función que puede aceptar diferentes cantidades de parámetros con diferentes tipos?
- type Func = (...args: [Tipo1, Tipo2, ...]) => Tipo
- type Func = (args: [Tipo1, Tipo2, ...]) => Tipo
- type Func = (args: Tipo[]) => Tipo

¿Qué hace el tipo `Constructable`?
- Representa un tipo que puede ser instanciado usando `new`
- Representa un tipo que solo puede ser llamado como una función
- Representa un tipo que puede ser extendido por clases

¿Cómo se usa el tipo `ThisType<T>` para definir el tipo de `this` en un contexto específico?
- type MyType = ThisType<T>
- type MyType = T
- type MyType = T & ThisType

¿Qué significa `Extract<T, U>` y cuándo se usaría?
- Un tipo que extrae de `T` los tipos que están en `U`
- Un tipo que combina `T` y `U` en uno solo
- Un tipo que elimina de `T` los tipos que están en `U`

¿Cómo se define un tipo que representa una función que acepta un objeto con propiedades específicas y retorna un tipo?
- type Func = (obj: { prop1: Tipo1; prop2: Tipo2 }) => Tipo
- type Func = (obj: { prop1: Tipo1 }) => Tipo
- type Func = (obj: Tipo[]) => Tipo

¿Qué es un tipo "discriminado" y cómo se utiliza?
- Un tipo que usa una propiedad común para distinguir entre diferentes variantes de un tipo
- Un tipo que combina varios tipos en uno solo
- Un tipo que excluye ciertos valores de un conjunto

¿Cómo se define un tipo que es una función de alto orden que recibe una función y retorna un tipo diferente?
- type HigherOrderFunc = (fn: (param: Tipo) => Tipo) => OtroTipo
- type HigherOrderFunc = (fn: Tipo) => (param: Tipo) => OtroTipo
- type HigherOrderFunc = (fn: (param: Tipo) => Tipo) => Tipo

¿Cómo se utiliza el tipo `InstanceType<T>`?
- Para obtener el tipo de instancia que una clase `T` crea
- Para obtener el tipo de retorno de una función
- Para obtener el tipo de un parámetro de función

¿Qué hace el tipo `Parameters<T>`?
- Obtiene un tipo de tupla que representa los parámetros de una función tipo `T`
- Obtiene el tipo de retorno de una función tipo `T`
- Obtiene el tipo de un parámetro específico en una función tipo `T`

¿Cómo se define un tipo que es una función que acepta un número variable de argumentos opcionales?
- (...args?: Tipo[]) => Tipo
- (args?: Tipo[]) => Tipo
- (...args: [Tipo?]) => Tipo

¿Qué es un tipo "literal de plantilla" y cómo se usa?
- Un tipo que se define a partir de cadenas de texto con interpolaciones
- Un tipo que se usa para representar valores fijos
- Un tipo que se combina con otros tipos para formar un nuevo tipo

¿Cómo se define un tipo de datos que es una intersección de un tipo literal y una clase?
- type Combined = { prop: Tipo } & Clase
- type Combined = Clase & { prop: Tipo }
- type Combined = { prop: Tipo }

¿Qué es un "mapped type" y cómo se usa?
- Un tipo que transforma cada propiedad de otro tipo usando una función
- Un tipo que se usa para definir tipos genéricos
- Un tipo que combina múltiples tipos en uno solo

¿Cómo se usa el tipo `ReadonlyArray<T>` y qué lo diferencia de `Array<T>`?
- Define un array donde los elementos no pueden ser modificados
- Define un array donde los elementos pueden ser modificados
- Define un array de tamaño fijo

¿Qué hace el tipo `ReturnType<T>` y cómo se utiliza?
- Obtiene el tipo de retorno de una función tipo `T`
- Obtiene el tipo del primer parámetro de una función tipo `T`
- Obtiene el tipo de una propiedad específica en un objeto tipo `T`

¿Cómo se define un tipo que es una función que acepta un argumento que es una tupla y retorna un tipo?
- type TupleFunc = (args: [Tipo1, Tipo2]) => Tipo
- type TupleFunc = (args: [Tipo1, Tipo2]) => Tipo[]
- type TupleFunc = (args: Tipo[]) => Tipo

¿Qué es un tipo "literal de plantilla" y cómo se usa para construir tipos dinámicos?
- Un tipo que usa literales de cadena para construir nuevos tipos combinando valores
- Un tipo que define valores estáticos en el código
- Un tipo que se usa para representar números y cadenas

¿Cómo se define un tipo que representa una función que acepta un número variable de argumentos de diferentes tipos?
- type VarArgsFunc = (...args: [Tipo1, Tipo2, ...]) => Tipo
- type VarArgsFunc = (args: [Tipo1, Tipo2]) => Tipo
- type VarArgsFunc = (args: Tipo[]) => Tipo

¿Qué hace la utilidad `Required<T>`?
- Convierte todas las propiedades de `T` en obligatorias
- Convierte todas las propiedades de `T` en opcionales
- Convierte algunas propiedades de `T` en obligatorias

¿Cómo se usa el tipo `ConstructorParameters<T>`?
- Obtiene un tipo de tupla que representa los parámetros del constructor de una clase tipo `T`
- Obtiene el tipo de retorno del constructor de una clase tipo `T`
- Obtiene el tipo de una propiedad específica en una clase tipo `T`

¿Qué es un tipo "lookup" y cómo se usa?
- Un tipo que accede a los tipos de propiedades de otro tipo usando su clave
- Un tipo que combina múltiples tipos en uno solo
- Un tipo que excluye ciertos valores de un conjunto

¿Cómo se define un tipo que representa una función que acepta un objeto con propiedades opcionales?
- type OptionalPropsFunc = (obj: { prop1?: Tipo1; prop2?: Tipo2 }) => Tipo
- type OptionalPropsFunc = (obj: { prop1: Tipo1; prop2: Tipo2 }) => Tipo
- type OptionalPropsFunc = (obj: { prop1?: Tipo1 }) => Tipo

¿Qué significa `keyof` y cómo se usa para obtener un tipo de clave de un objeto?
- Obtiene un tipo que representa todas las claves de un objeto tipo `T`
- Obtiene un tipo que representa todos los valores de un objeto tipo `T`
- Obtiene un tipo que representa todas las propiedades de un objeto tipo `T`

¿Cómo se define un tipo que es una función que retorna otra función con un tipo diferente?
- type OuterFunc = () => (param: Tipo) => OtroTipo
- type OuterFunc = (param: Tipo) => (param: Tipo) => OtroTipo
- type OuterFunc = (param: Tipo) => OtroTipo

¿Qué hace el tipo `InstanceType<T>` y cómo se utiliza?
- Obtiene el tipo de la instancia creada por una clase `T`
- Obtiene el tipo del constructor de una clase `T`
- Obtiene el tipo del primer parámetro de una clase `T`

¿Cómo se define un tipo que representa una función que acepta un número variable de parámetros opcionales y retorna un tipo?
- type Func = (...args?: Tipo[]) => Tipo
- type Func = (args?: Tipo[]) => Tipo
- type Func = (...args: Tipo[]) => Tipo

¿Qué hace el tipo `Omit<T, K>`?
- Excluye las propiedades `K` del tipo `T`
- Incluye las propiedades `K` en el tipo `T`
- Combina `T` con las propiedades `K`

¿Cómo se usa el tipo `typeof` para obtener el tipo de una variable o expresión?
- Obtiene el tipo de la variable o expresión
- Declara una nueva variable del mismo tipo
- Define un tipo genérico basado en una variable