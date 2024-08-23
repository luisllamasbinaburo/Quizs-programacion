¿Cómo se define un `indexer` en una clase?
- public T this[int index] { get; set; }
- public T Get(int index) { }
- public void Set(int index, T value) { }

¿Cuál es la diferencia entre `Task.Run` y `Task.Factory.StartNew`?
- `Task.Run` es una forma simplificada de iniciar una tarea en el hilo del pool de hilos, mientras que `Task.Factory.StartNew` ofrece más opciones de configuración
- `Task.Run` proporciona más opciones de configuración que `Task.Factory.StartNew`
- `Task.Run` y `Task.Factory.StartNew` son equivalentes en todas las circunstancias

¿Qué es el patrón de diseño `Repository` y cómo se aplica?
- Un patrón que abstrae la lógica de acceso a datos en una interfaz para simplificar la gestión de datos
- Un patrón que implementa directamente la lógica de acceso a datos en las clases de entidad
- Un patrón que usa directamente los métodos SQL en las clases de entidad

¿Cómo se implementa el patrón de diseño `Mediator`?
- Usando una clase `Mediator` que coordina la comunicación entre objetos sin que estos se refieran directamente entre sí
- Usando una interfaz para definir la comunicación directa entre objetos
- Usando un servicio que realiza llamadas directas a los objetos involucrados

¿Qué es un `lambda expression` en C# y cómo se usa?
- Una forma concisa de definir funciones anónimas que se pueden pasar como argumentos a otros métodos
- Una función que se declara con un nombre específico para su uso en toda la aplicación
- Un método que se define dentro de una clase para realizar una operación específica

¿Cómo se usa el modificador `readonly` en una clase?
- Se usa para declarar campos que solo pueden ser asignados en el constructor o en la declaración de la variable
- Se usa para definir métodos que no pueden ser sobrescritos en clases derivadas
- Se usa para declarar propiedades que solo se pueden leer

¿Qué es un `dynamic` type y cómo afecta el rendimiento?
- `dynamic` permite la resolución de tipos en tiempo de ejecución, lo que puede afectar negativamente al rendimiento debido a la falta de comprobación en tiempo de compilación
- `dynamic` permite que los tipos sean verificados en tiempo de compilación para mejorar el rendimiento
- `dynamic` optimiza el rendimiento al realizar todas las comprobaciones en tiempo de compilación

¿Cómo se implementa una operación atómica?
- Usando la clase `Interlocked` para realizar operaciones de forma atómica y evitar problemas de concurrencia
- Usando bloques de código `lock` para sincronizar el acceso a recursos compartidos
- Usando la palabra clave `volatile` para indicar que un campo puede ser cambiado en cualquier momento

¿Qué es un `dynamic proxy` en C# y cuándo se utiliza?
- Un proxy que se genera dinámicamente en tiempo de ejecución para interceptar y modificar llamadas a métodos
- Un tipo de proxy que se define estáticamente para la comunicación entre componentes
- Un proxy que solo se utiliza para la comunicación de red

¿Cómo se maneja el `memory management`?
- A través del `garbage collector`, que se encarga de liberar automáticamente la memoria no utilizada
- Mediante la gestión manual de la memoria a través de punteros
- Usando directivas especiales para la asignación y liberación de memoria

¿Cómo se utiliza el patrón de diseño `Chain of Responsibility`?
- Definiendo una cadena de manejadores que procesan una solicitud y pasan la solicitud a lo largo de la cadena hasta que un manejador la procesa
- Definiendo un solo manejador que procesa todas las solicitudes directamente
- Usando una clase estática para manejar todas las solicitudes

¿Qué es un `volatile` field y cuándo se usa?
- Un campo marcado como `volatile` se asegura de que las lecturas y escrituras sean siempre visibles para todos los hilos
- Un campo `volatile` se usa para mejorar el rendimiento de las operaciones en hilos
- Un campo `volatile` se utiliza para definir constantes globales

¿Cómo se define un `custom attribute` en C# y cómo se aplica?
- Se define como una clase que hereda de `System.Attribute` y se aplica usando corchetes en el código
- Se define como un método que debe ser invocado explícitamente
- Se define como una interfaz que debe ser implementada en las clases

¿Qué es un `ValueTuple` y cómo se diferencia de un `Tuple`?
- `ValueTuple` es un tipo de valor que permite una desestructuración más eficiente y no es inmutable, mientras que `Tuple` es un tipo de referencia inmutable
- `ValueTuple` es un tipo de referencia que permite la inmutabilidad, mientras que `Tuple` es un tipo de valor
- No hay diferencias significativas entre `ValueTuple` y `Tuple`

¿Cómo se usa la palabra clave `lock` para la sincronización?
- Para asegurar que solo un hilo pueda ejecutar un bloque de código a la vez, evitando problemas de concurrencia
- Para permitir que múltiples hilos accedan a un bloque de código simultáneamente
- Para definir una región de código que se ejecutará en el orden de llegada de los hilos

¿Qué es un `memory leak` y cómo se evita?
- Un `memory leak` ocurre cuando la memoria se reserva pero no se libera, y se puede evitar usando el `garbage collector` y gestionando adecuadamente los recursos
- Un `memory leak` ocurre cuando se libera memoria prematuramente, y se puede evitar usando la palabra clave `static`
- Un `memory leak` ocurre cuando se usa el `finalize` incorrectamente

¿Cómo se utiliza la clase `ConcurrentDictionary`?
- Para manejar un diccionario que admite accesos concurrentes sin necesidad de bloqueos explícitos
- Para implementar un diccionario que no permite accesos concurrentes
- Para almacenar datos de forma secuencial en un diccionario

¿Qué es la `composición` frente a la `herencia`?
- La composición implica construir clases a partir de otras clases a través de la inclusión de instancias, mientras que la herencia implica derivar clases de otras clases
- La herencia se usa para incluir instancias dentro de una clase, mientras que la composición se usa para derivar clases
- No hay diferencia entre composición y herencia en C#

¿Cómo se realiza la `deserialización`?
- Convirtiendo datos en formato JSON, XML u otro en objetos de C# usando métodos como `JsonConvert.DeserializeObject`
- Transformando objetos en cadenas de texto usando `ToString()`
- Usando la palabra clave `convert` para convertir datos

¿Qué es una `deadlock` y cómo se evita?
- Un `deadlock` ocurre cuando dos o más hilos esperan indefinidamente por recursos que están bloqueados entre sí, y se evita mediante la gestión adecuada de bloqueos y la utilización de técnicas como la ordenación de recursos
- Un `deadlock` ocurre cuando un hilo se ejecuta indefinidamente sin liberarse, y se evita mediante la liberación de recursos
- Un `deadlock` ocurre cuando un hilo se bloquea sin razón y se evita con la palabra clave `unlock`

¿Cómo se implementa la `dependency injection` en C# usando `Microsoft.Extensions.DependencyInjection`?
- Registrando servicios en el contenedor de servicios y resolviendo dependencias a través del contenedor
- Usando el patrón singleton directamente para todas las dependencias
- Implementando manualmente la inyección de dependencias en cada clase

¿Qué es un `futures` en C# y cómo se diferencia de un `Task`?
- Un `future` es un objeto que representa el resultado de una operación que puede no estar completa aún, mientras que `Task` es una representación de una operación asíncrona en C#
- Un `future` y `Task` son conceptos sinónimos en C#
- Un `future` es una operación que se ejecuta en el hilo principal, mientras que un `Task` se ejecuta en un hilo separado

¿Qué es un `Proxy` y cómo se utiliza?
- Un patrón de diseño que proporciona un sustituto o representante de otro objeto para controlar el acceso a él
- Una clase que almacena datos en caché para mejorar el rendimiento
- Un tipo de colección que se usa para manejar objetos complejos

¿Cómo se implementa la serialización de un objeto?
- Usando atributos de serialización y métodos como `BinaryFormatter.Serialize` o `JsonConvert.SerializeObject` para convertir un objeto en un formato de almacenamiento
- Almacenar un objeto en un archivo directamente usando `File.WriteAllBytes`
- Usando el método `ToString()` para convertir un objeto a texto

¿Cómo se usa el patrón de diseño `Observer`?
- Definiendo una relación uno-a-muchos entre objetos de modo que cuando uno cambia de estado, todos los dependientes son notificados y actualizados automáticamente
- Definiendo un solo objeto que observa todos los cambios en otros objetos
- Usando un objeto que realiza todas las actualizaciones de estado directamente