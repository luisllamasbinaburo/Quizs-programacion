¿Qué es un transistor NPN en un circuito Arduino?
- Un tipo de transistor que permite la conducción cuando la base es positiva
- Un tipo de transistor que permite la conducción cuando la base es negativa
- Un tipo de transistor que nunca permite la conducción

¿Qué es un watchdog timer y cómo se utiliza?
- Un temporizador que reinicia el microcontrolador si no se reinicia a tiempo
- Un temporizador que controla la velocidad del motor
- Un temporizador para medir la duración de eventos

¿Cuál es la diferencia principal entre el protocolo I2C y SPI en términos de comunicación?
- I2C usa dos cables mientras que SPI usa cuatro cables
- I2C tiene una mayor velocidad que SPI
- SPI es más fácil de usar que I2C

¿Cómo se denomina la técnica de comunicación donde un microcontrolador genera una señal de reloj para sincronizar datos?
- Master-slave
- Asíncrona
- Secuencial

¿Qué es un "interrupt vector" en el contexto de Arduino?
- Una tabla que define cómo manejar interrupciones
- Un componente que amplifica señales
- Una función que controla la temporización de eventos

¿Cómo se puede reducir el consumo de energía de un microcontrolador en un proyecto Arduino?
- Utilizando modos de bajo consumo
- Aumentando la frecuencia del reloj
- Incrementando la resistencia en el circuito

¿Cuál es el propósito del pin AREF en una placa Arduino?
- Proporcionar una referencia de voltaje para el ADC
- Controlar el encendido del LED
- Ajustar la velocidad del motor

¿Cómo se realiza una lectura de alta precisión en un sensor analógico usando Arduino?
- Usando una referencia de voltaje externa estable
- Usando un filtro de paso bajo
- Aumentando la frecuencia del reloj del ADC

¿Cómo se puede mejorar la resolución de un ADC en un Arduino?
- Usando un ADC externo con mayor resolución
- Aumentando la velocidad del reloj del microcontrolador
- Usando un filtro RC en la entrada analógica

¿Qué es un "bootloader" en el contexto de Arduino?
- Un pequeño programa que permite cargar el código en el microcontrolador
- Un módulo que expande la memoria del microcontrolador
- Un componente que amplifica las señales de comunicación

¿Qué técnica se usa para sincronizar múltiples dispositivos I2C?
- Dirección única para cada dispositivo
- Uso de diferentes frecuencias de reloj
- Conexión en paralelo

¿Cómo se puede implementar una comunicación segura en un proyecto Arduino que usa módulos Wi-Fi?
- Utilizando cifrado SSL/TLS
- Configurando una red privada
- Aumentando la potencia de transmisión

¿Cómo se puede debugear un programa para identificar errores?
- Usando la comunicación serial para imprimir mensajes
- Aumentando el tamaño de la memoria RAM
- Ajustando la frecuencia del reloj

¿Qué hace la función `attachInterrupt()`s?
- Permite ejecutar una función en respuesta a una señal externa
- Establece la velocidad de comunicación serial
- Configura la resolución del ADC

¿Cómo se calcula la frecuencia de una señal generada por un temporizador?
- `F = F_CPU / (Prescaler * (1 + OCRn))`
- `F = F_CPU * (Prescaler + OCRn)`
- `F = F_CPU / (OCRn * Prescaler)`

¿Qué librería de Arduino se recomienda para gestionar tareas en tiempo real?
- `FreeRTOS`
- `Corrutine`
- `TimeOS`

¿Qué técnica se usa para minimizar la interferencia en una comunicación SPI en entornos ruidosos?
- Usar una pantalla de protección o cableado blindado
- Aumentar la velocidad del reloj SPI
- Usar una mayor resistencia de pull-up

¿Cuál es el propósito del registro `TCNT` en un temporizador de Arduino?
- Contar el número de ciclos del temporizador
- Ajustar la frecuencia del reloj del microcontrolador
- Configurar el modo de comparación del temporizador

¿Cómo se realiza una transferencia de datos de 32 bits en una comunicación serial?
- Usando la función `Serial.write()` con 4 bytes
- Usando `Serial.print()` con el formato adecuado
- Usando `Serial.read()` en modo binario

¿Qué método se emplea para sincronizar un Arduino con un reloj de alta precisión?
- Utilizar un cristal oscilador externo de alta precisión
- Ajustar el reloj interno del microcontrolador
- Usar una fuente de alimentación estabilizada

¿Qué es un "core" en el contexto de las placas de Arduino y su programación?
- La parte del microcontrolador que ejecuta el código
- Una librería de funciones específicas para Arduino
- Un módulo de expansión para la placa

¿Qué función cumple el registro `UCSR0B` en la comunicación UART del Arduino?
- Configurar la habilitación de la transmisión y recepción de datos
- Ajustar la velocidad de baudios
- Establecer el formato de los datos

¿Cómo se configura un pin de interrupción externa para detectar el flanco descendente en un Arduino Uno?
- `attachInterrupt(digitalPinToInterrupt(pin), isr, FALLING)`
- `attachInterrupt(pin, isr, LOW)`
- `interruptConfig(pin, FALLING)`

¿Cómo se puede optimizar el uso de memoria en un programa que usa arrays grandes?
- Almacenando los datos constantes en la memoria FLASH
- Incrementando el contador de memoria RAM
- Reduciendo la frecuencia del reloj del microcontrolador

¿Qué es un "bootloader" y qué rol juega en la programación de un microcontrolador?
- Un programa que permite cargar código en la memoria flash
- Un módulo que amplifica señales de entrada
- Un componente que aumenta la velocidad del microcontrolador

¿Qué técnica se usa para realizar una conversión precisa de señal analógica a digital?
- Promediar múltiples lecturas para reducir el ruido
- Aumentar la velocidad del reloj del ADC
- Usar un filtro de paso alto

¿Cuál es la diferencia clave entre un temporizador de 8 bits y uno de 16 bits en un Arduino?
- El rango de valores que pueden contar y la resolución de temporización
- La cantidad de interrupciones que pueden manejar
- La velocidad máxima de operación

¿Qué método se utiliza para implementar una comunicación en serie entre múltiples Arduinos usando RS-485?
- Usar un transceptor RS-485 para convertir señales UART
- Conectar los pines TX y RX directamente entre las placas
- Implementar un protocolo de comunicación I2C

¿Cómo se configura una señal PWM para que tenga una frecuencia específica en un Arduino Mega?
- Modificando el valor del registro `TCCRn` correspondiente al temporizador
- Cambiando la resolución de la función `analogWrite()`
- Ajustando el valor de la variable `OCRn`

¿Qué librería permite la gestión de conexiones Bluetooth utilizando el protocolo AT?
- `SoftwareSerial`
- `BluetoothSerial`
- `AltSoftSerial`

¿Cómo se puede aumentar la resolución del ADC en un Arduino con un conversor externo?
- Utilizando un ADC externo
- Configurando el ADC interno del microcontrolador para alta resolución
- Usando un filtro de ruido en la entrada analógica

¿Qué técnica se utiliza para implementar una sincronización precisa en proyectos de Arduino que involucran múltiples microcontroladores?
- Usar un reloj maestro para sincronizar todas las placas
- Configurar los pines de interrupción para sincronización
- Implementar una red de comunicación serial

¿Cómo se utilizan los registros `TIMSK` y `TIFR` en el manejo de interrupciones de temporizador?
- Para habilitar y verificar las interrupciones del temporizador
- Para ajustar la velocidad del temporizador
- Para configurar la frecuencia del reloj del microcontrolador

¿Cuál es el propósito de la función `eeprom_update_byte()`?
- Actualizar un byte en la memoria EEPROM solo si el valor ha cambiado
- Leer un byte de la memoria EEPROM
- Escribir un bloque de datos en la memoria EEPROM

¿Cuál es la frecuencia de PWM estándar en un pin digital de Arduino?
- 490 Hz
- 450 Hz
- 510 kHz

¿Qué es un filtro RC en un circuito Arduino?
- Un filtro pasivo que usa un resistor y un condensador
- Un regulador de corriente
- Un sensor de temperatura

¿Qué es un registro de desplazamiento en un proyecto Arduino?
- Un componente que permite controlar múltiples salidas con pocos pines
- Un sensor de movimiento
- Un convertidor de corriente

¿Qué función tiene un optoacoplador en un circuito Arduino?
- Aislar eléctricamente dos circuitos
- Regular el voltaje de salida
- Convertir señales analógicas a digitales

¿Qué es un watchdog timer?
- Un temporizador que reinicia la placa si el software se cuelga
- Un sensor de tiempo que funciona por interrupción
- Un conversor de señal de alta impedancia

¿Qué significa duty cycle en una señal PWM?
- El porcentaje del tiempo que está en estado alto
- La frecuencia de la señal
- La amplitud máxima de la señal

¿Qué es un filtro paso-bajo en un circuito?
- Un filtro que permite el paso de señales de baja frecuencia
- Un componente que almacena energía
- Un circuito que amplifica señales de alta frecuencia

¿Qué es un PID (Proporcional-Integral-Derivativo) en controladores de Arduino?
- Un tipo de controlador para ajustar una variable a un valor deseado
- Un tipo de sensor de proximidad
- Un protocolo de comunicación

¿Qué hace la función `SerialparseInt()`?
- Lee un número entero de la entrada serial
- Escribe un número entero en el puerto serial
- Lee una cadena de caracteres de la entrada serial

¿Cuál es el máximo número de instrucciones que un Arduino puede ejecutar en un ciclo de reloj?
- Una instrucción
- Dos instrucciones
- Tres instrucciones

¿Qué técnica de comunicación utiliza el protocolo I2C?
- Comunicación bidireccional síncrona
- Comunicación unidireccional asíncrona
- Comunicación en serie simplex

¿Cuál es una ventaja de usar `millis()` en lugar de `delay()` para hacer esperar?
- Permitir la ejecución de otras tareas simultáneamente
- Aumentar la precisión del temporizador
- Reducir el consumo de energía

¿Cuál es el propósito de la función `noInterrupts()` en Arduino?
- Desactivar temporalmente las interrupciones
- Reiniciar el sistema de interrupciones
- Configurar las interrupciones a un estado predeterminado

¿Qué ocurrirá si se llama a la función `Serial.begin(9600)` sin conectar un dispositivo de comunicación serie?
- El programa seguirá ejecutándose sin problemas
- El programa se detendrá
- El Arduino se reiniciará

¿Cuál es el propósito de utilizar un condensador de desacoplo en un circuito con Arduino?
- Filtrar ruidos y estabilizar el voltaje de alimentación
- Incrementar la corriente disponible para los pines
- Almacenar energía para su uso posterior

¿Cómo se puede cambiar la frecuencia del PWM en un pin específico de Arduino?
- Modificando los registros del temporizador
- Cambiando el segundo parametro de `analogWrite`
- Usando ña funcion `setFrequency` la biblioteca `PWM.h`

¿Cuál es el propósito de la función `yield()` en un programa de Arduino?
- Permitir la ejecución de otras tareas en un entorno multitarea
- Incrementar la velocidad de ejecución
- Reducir el uso de memoria


¿Qué hace la función `cli()` en un programa de Arduino?
- Desactiva todas las interrupciones globales
- Reinicia el microcontrolador
- Habilita las interrupciones globales

¿Cómo se puede asegurar la integridad de los datos al transmitir entre dos Arduinos utilizando UART?
- Usando un protocolo de control de flujo
- Incrementando la velocidad de baudios
- Desactivando las interrupciones

¿Qué ocurre si se cambia la referencia de voltaje analógico (`analogReference`) a un valor más bajo durante una lectura analógica en Arduino?
- Aumenta la resolución de la lectura
- Disminuye la velocidad de lectura
- No tiene ningún efecto

¿Cuál es la principal función del watchdog timer en un Arduino?
- Reiniciar el sistema en caso de mal funcionamiento
- Proteger el sistema contra sobrecargas
- Regular la velocidad de ejecución del programa

¿Qué ocurre si no se conecta el pin GND de un módulo externo al GND de un Arduino?
- Se pueden producir errores en la comunicación o mal funcionamiento del módulo
- La alimentación del Arduino se verá afectada
- El Arduino funcionará correctamente pero el módulo externo no

¿Qué ocurre si se intenta acceder a una dirección de memoria fuera de los límites de un array?
- Puede causar un comportamiento inesperado o inestable
- El Arduino lanzará una excepción
- El valor retornado será siempre cero

¿Cuál es la principal ventaja de utilizar interrupciones en un programa de Arduino?
- Responder rápidamente a eventos
- Incrementar la velocidad del microcontrolador
- Reducir el uso de memoria

¿Qué ocurre si se utiliza un cristal de cuarzo con una frecuencia incorrecta en un Arduino?
- El Arduino funcionará a una velocidad diferente
- El Arduino no funcionará en absoluto
- El Arduino se recalentará

¿Cuál es el propósito del registro `TCCR1A` en un Arduino?
- Configurar el modo y la operación del temporizador 1
- Iniciar la comunicación serial
- Configurar el modo de las entradas analógicas

¿Cómo se puede reducir el consumo de energía de un Arduino cuando está en modo de espera?
- Desactivando los periféricos no utilizados
- Aumentando la velocidad del microcontrolador
- Conectando menos componentes externos

¿Qué ventaja ofrece el uso de la comunicación I2C sobre SPI en un proyecto con Arduino?
- Menor cantidad de pines necesarios
- Mayor velocidad de transmisión de datos
- Mayor inmunidad al ruido

¿Qué ocurre si se conecta un sensor capacitivo a un pin de entrada digital de un Arduino sin ningún circuito de acondicionamiento?
- El sensor puede no funcionar correctamente
- El sensor funcionará pero con baja precisión
- El Arduino dañará el sensor debido a la alta corriente

¿Cómo se puede reducir el ruido en la lectura de un sensor analógico en un Arduino?
- Usando un filtro RC en la entrada analógica
- Aumentando la frecuencia de muestreo
- Usando `digitalRead` en lugar de `analogRead`

¿Cómo se puede evitar que una interrupción en Arduino interfiera con una operación crítica?
- Desactivando temporalmente las interrupciones con `noInterrupts()`
- Aumentando la prioridad de la interrupción
- Reduciendo la velocidad de la interrupción

¿Qué ocurre si se conecta un regulador de 5V en la salida de 3.3V de un Arduino?
- El Arduino podría dañarse debido
- El regulador ajustará automáticamente el voltaje
- El regulador proporcionará de 3.3V, en lugar de 5V

¿Qué tipo de datos devuelve la función digitalRead() en Arduino?
- Un número entero
- Un valor booleano
- Un valor flotante

- ¿Qué ocurre si se configura el temporizador 1 en modo CTC pero sin ajustar el registro OCR1A?
- El temporizador nunca generará la interrupción deseada
- El temporizador se comportará como en modo normal
- Arduino entrará en un ciclo de reinicio constante

¿Qué técnica podemos usar para gestionar múltiples interrupciones en un Arduino sin que interfieran entre sí?
- Priorizar las interrupciones y utilizar banderas
- Configurar un temporizador dedicado para cada interrupción
- Desactivar las interrupciones durante el manejo de cada una

¿Cuál es el impacto de configurar incorrectamente el registro `TCCR0B` en un Arduino?
- Puede afectar la frecuencia de PWM y el temporizador asociado
- Cambia la velocidad de comunicación serial
- Desactiva la funcionalidad del pin de salida digital

¿Cómo afecta el modo de operación CTC (Clear Timer on Compare Match) en un temporizador de Arduino a la generación de señales PWM?
- Resetea el temporizador a un valor predefinido
- Incrementa la frecuencia de la señal PWM generada
- Duplica la resolución de la señal PWM

¿Qué impacto tiene la configuración de los bits de preescalado en un temporizador en la precisión del millis() y micros() en Arduino?
- Cambia la precisión y la resolución de las funciones de temporización
- Incrementa el tiempo de procesamiento en cada ciclo de reloj
- No afecta a millis() ni a micros() ya que operan independientemente