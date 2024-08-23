¿Qué hace la función `EEPROM.put()`?
- Escribe un valor en la memoria EEPROM
- Lee un valor de un pin analógico
- Configura un pin como salida

¿Cuál es el propósito de un resistor pull-up en un circuito Arduino?
- Mantener el pin en un estado alto cuando no está conectado
- Limitar la corriente a un LED
- Aumentar la velocidad de comunicación serial

¿Qué librería de Arduino se usa para gestionar comunicación SPI?
- SPI
- LiquidCrystal
- Servo

¿Cómo se denomina el proceso de sincronización entre un microcontrolador y un reloj externo?
- Generación de reloj externo
- Configuración de reloj interno
- Calibración de temporizador

¿Qué tipo de módulo se usa para recibir señales de GPS?
- Módulo GPS
- Módulo GSM
- Módulo Bluetooth

¿Qué es un watchdog timer y cómo se utiliza?
- Un temporizador que reinicia el microcontrolador si no se reinicia a tiempo
- Un temporizador que controla la velocidad del motor
- Un temporizador para medir la duración de eventos

¿Cuál es la diferencia principal entre el protocolo I2C y SPI en términos de comunicación?
- I2C usa dos cables mientras que SPI usa cuatro cables
- I2C tiene una mayor velocidad que SPI
- SPI es más fácil de usar que I2C

¿Qué librería de Arduino se usa para controlar pantallas LCD con interfaz I2C?
- Wire
- LiquidCrystal
- Servo

¿Cómo se denomina la técnica de comunicación donde un microcontrolador genera una señal de reloj para sincronizar datos?
- Master-slave
- Asíncrona
- Secuencial

¿Qué es un "interrupt vector" en el contexto de Arduino?
- Una tabla que define cómo manejar interrupciones específicas
- Un componente que amplifica señales
- Una función que controla la temporización de eventos

¿Cómo se puede reducir el consumo de energía de un microcontrolador en un proyecto Arduino?
- Utilizando modos de bajo consumo como el modo de suspensión
- Aumentando la frecuencia del reloj
- Incrementando la resistencia en el circuito

¿Qué librería se usa para implementar comunicación entre Arduino y un módulo de radio de 433 MHz?
- RadioHead
- Servo
- SPI

¿Cuál es el propósito del pin AREF en una placa Arduino?
- Proporcionar una referencia de voltaje para la conversión analógica a digital
- Controlar el encendido del LED
- Ajustar la velocidad del motor

¿Cómo se realiza una lectura de alta precisión en un sensor analógico usando Arduino?
- Usando una referencia de voltaje externa estable
- Usando un filtro de paso bajo
- Aumentando la frecuencia del reloj del ADC

¿Qué librería de Arduino se usa para implementar el protocolo de comunicación UART?
- SoftwareSerial
- Wire
- EEPROM

¿Qué hace la función `pulseIn()` en un programa de Arduino?
- Mide la duración de un pulso en un pin
- Envía un pulso de salida a un pin
- Configura un pin como entrada o salida

¿Cómo se puede mejorar la resolución de un ADC en un Arduino?
- Usando un ADC externo con mayor resolución
- Aumentando la velocidad del reloj del microcontrolador
- Usando un filtro RC en la entrada analógica

¿Qué es un "bootloader" en el contexto de Arduino?
- Un pequeño programa que permite cargar el código en el microcontrolador
- Un módulo que expande la memoria del microcontrolador
- Un componente que amplifica las señales de comunicación

¿Qué técnica se usa para sincronizar múltiples dispositivos I2C en un mismo bus?
- Dirección única para cada dispositivo
- Uso de diferentes frecuencias de reloj
- Conexión en paralelo

¿Cómo se puede implementar una comunicación segura en un proyecto Arduino que usa módulos Wi-Fi?
- Utilizando cifrado SSL/TLS para las comunicaciones
- Configurando una red privada
- Aumentando la potencia de transmisión

¿Qué función tiene el pin de reset en una placa Arduino?
- Reiniciar el microcontrolador
- Ajustar el voltaje de referencia
- Cambiar el modo de comunicación

¿Cuál es la ventaja principal de usar un temporizador?
- Permite realizar tareas periódicas de manera precisa
- Aumenta la velocidad del microcontrolador
- Mejora la calidad de la señal analógica

¿Cómo se puede debugear un programa para identificar errores?
- Usando la comunicación serial para imprimir mensajes de depuración
- Aumentando el tamaño de la memoria RAM
- Ajustando la frecuencia del reloj

¿Qué es un "RTC" en el contexto de Arduino y para qué se usa?
- Un reloj en tiempo real que mantiene la hora y la fecha
- Un componente para medir la resistencia
- Un sensor de temperatura

¿Qué hace la función `attachInterrupt()` y cuáles son sus parámetros más comunes?
- Permite ejecutar una función en respuesta a una señal externa, con parámetros como el pin y el modo de activación
- Establece la velocidad de comunicación serial
- Configura la resolución del ADC

¿Qué función se utiliza para establecer una resolución de 10 bits en el ADC del Arduino Mega?
- `analogReference(EXTERNAL)`
- `analogReadResolution(10)`
- `setADCResolution(10)`

¿Cómo se calcula la frecuencia de una señal generada por un temporizador?
- `F = F_CPU / (Prescaler * (1 + OCRn))`
- `F = F_CPU * (Prescaler + OCRn)`
- `F = F_CPU / (OCRn * Prescaler)`

¿Qué librería de Arduino se recomienda para gestionar tareas en tiempo real?
- `FreeRTOS`
- `TaskScheduler`
- `Time`

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

¿Qué librería de Arduino permite la comunicación con módulos basados en el protocolo LoRa?
- `LoRa`
- `RadioHead`
- `WiFi`

¿Cómo se puede optimizar el uso de memoria en un programa que usa arrays grandes?
- Usando la memoria flash para almacenar datos constantes
- Incrementando la memoria RAM
- Reduciendo la frecuencia del reloj del microcontrolador

¿Qué es un "bootloader" y qué rol juega en la programación de un microcontrolador?
- Un programa que permite cargar código en la memoria flash del microcontrolador
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
- Utilizando un ADC externo con mayor resolución como el MCP3208
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

¿Qué es un "módulo de expansión I2C" y cómo se usa con Arduino?
- Un dispositivo que permite conectar múltiples componentes I2C a un solo bus
- Un módulo que amplifica las señales de comunicación
- Un componente para aumentar la capacidad de procesamiento

¿Cómo se realiza una conversión de datos de un sensor analógico de alta precisión en un Arduino?
- Usando un convertidor analógico-digital externo con alta resolución
- Configurando el ADC del Arduino para alta precisión
- Aplicando un filtro digital a las lecturas del sensor

¿Qué librería de Arduino permite la implementación de comunicaciones de red mediante TCP/IP?
- `Ethernet`
- `WiFi101`
- `HttpClient`

¿Cuál es el propósito de la función `eeprom_update_byte()`?
- Actualizar un byte en la memoria EEPROM solo si el valor ha cambiado
- Leer un byte de la memoria EEPROM
- Escribir un bloque de datos en la memoria EEPROM

¿Cuál es la frecuencia de PWM estándar en un pin digital de Arduino?
- 490 Hz
- 450 Hz
- 510 kHz

¿Qué es un filtro RC en un circuito Arduino?
- Un filtro pasivo que usa un resistor y un capacitor
- Un regulador de corriente
- Un sensor de temperatura

¿Qué hace un conversor DAC en un circuito Arduino?
- Convierte señales digitales a analógicas
- Convierte señales analógicas a digitales
- Amplifica señales de voltaje

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
- Un sensor de tiempo
- Un conversor de señal

¿Qué significa duty cycle en una señal PWM?
- El porcentaje del tiempo que la señal está en estado alto durante un ciclo
- La frecuencia de la señal
- La amplitud máxima de la señal

¿Qué es un filtro paso-bajo en un circuito?
- Un filtro que permite el paso de señales de baja frecuencia
- Un componente que almacena energía
- Un circuito que amplifica señales de alta frecuencia

¿Qué es una resistencia de pull-up interna en un Arduino?
- Una resistencia que puede ser habilitada por software
- Una resistencia que se conecta externamente
- Una resistencia variable

¿Qué tipo de memoria es la EEPROM?
- Una memoria no volátil que puede ser leída y escrita
- Una memoria volátil que se borra al apagar la placa
- Una memoria solo de lectura

¿Qué hace la función `millis()`?
- Devuelve el número de milisegundos desde que la placa comenzó a ejecutar el programa
- Pausa la ejecución por un número específico de milisegundos
- Devuelve el tiempo total de ejecución del programa

¿Qué es un divisor de voltaje?
- Un circuito que reduce la tensión de entrada a un nivel más bajo
- Un componente que aumenta la tensión
- Un convertidor analógico a digital

¿Qué función se utiliza para escribir en la memoria EEPROM?
- EEPROMwrite()
- writeMemory()
- analogWrite()

¿Qué es un PID (Proporcional-Integral-Derivativo) en controladores de Arduino?
- Un tipo de controlador para ajustar una variable a un valor deseado
- Un tipo de sensor de proximidad
- Un protocolo de comunicación

¿Qué es una resistencia pull-down?
- Una resistencia que conecta un pin a tierra
- Una resistencia que conecta un pin a la fuente de voltaje
- Un tipo de regulador de voltaje

¿Qué componente se usa para medir la temperatura ambiente?
- Un sensor LM35
- Un LDR
- Un potenciómetro

¿Qué es un protocolo UART?
- Un protocolo de comunicación serial
- Un sensor ultrasónico
- Un convertidor analógico a digital

¿Qué es un sensor de corriente?
- Un componente que mide la cantidad de corriente en un circuito
- Un componente que mide la temperatura
- Un tipo de resistor

¿Qué hace la función `SerialparseInt()`?
- Lee un número entero de la entrada serial
- Escribe un número entero en el puerto serial
- Lee una cadena de caracteres de la entrada serial

¿Qué es un sensor de proximidad basado en infrarrojos?
- Un sensor que detecta la presencia de objetos mediante infrarrojos
- Un sensor de temperatura
- Un sensor de presión