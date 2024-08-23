¿Cuál es el nombre del entorno gráfico predeterminado en Raspberry Pi OS?
- LXDE
- GNOME
- KDE

¿Qué utilidad permite crear y gestionar particiones de disco en Linux?
- fdisk
- mkfs
- mount

¿Qué archivo en Linux contiene las configuraciones del sistema para el arranque?
- /boot/grub/grub.cfg
- /etc/fstab
- /var/log/syslog

¿Cómo se puede verificar la consistencia del sistema de archivos en una Raspberry Pi sin desmontar el sistema?
- Usando el comando `fsck -n`
- Usando el comando `df -h`
- Usando el comando `lsblk`

¿Cuál es la función del parámetro `initramfs` en el arranque de Linux?
- Proporcionar un sistema de archivos temporal para el arranque del sistema antes de montar el sistema raíz
- Configurar la red durante el arranque
- Administrar el espacio de intercambio en el sistema

¿Cómo se puede habilitar la ejecución de scripts en el arranque del sistema en una Raspberry Pi?
- Colocando el script en el directorio `/etc/init.d/` y creando un enlace simbólico en `/etc/rc.d/`
- Editando el archivo `/etc/rc.local` para ejecutar el script al final del proceso de arranque
- Usando el comando `update-rc.d` para agregar el script a los runlevels

¿Qué archivo en Linux contiene las definiciones de los dispositivos de hardware disponibles?
- `/proc/devices`
- `/etc/devices`
- `/var/log/dmesg`

¿Qué comando se utiliza para verificar la integridad de los paquetes instalados en una distribución basada en Debian?
- `debsums`
- `dpkg`
- `apt-get`

¿Qué archivo de configuración se usa para especificar las opciones de red para los interfaces en Linux, usando `systemd-networkd`?
- `/etc/systemd/network/*.network`
- `/etc/network/interfaces`
- `/etc/sysconfig/network-scripts/ifcfg-*`

¿Qué es el "Loadable Kernel Module" (LKM) y cómo se usa en Linux?
- Un módulo que puede ser cargado o descargado dinámicamente en el kernel de Linux
- Un tipo de archivo de configuración del sistema
- Un servicio de red para la gestión de tráfico de datos

¿Cómo se puede listar todos los módulos del kernel actualmente cargados en un sistema Linux?
- Usando el comando `lsmod`
- Usando el comando `modprobe`
- Usando el comando `dmesg`

¿Cuál es el propósito del comando `mknod` en Linux?
- Crear archivos de dispositivo especiales (nodos de dispositivo) en el sistema de archivos
- Crear directorios y archivos normales
- Modificar la configuración del sistema

¿Qué herramienta de Linux se usa para ajustar la configuración de red en sistemas con `NetworkManager`?
- `nmcli`
- `ifconfig`
- `netstat`

¿Qué es el "Zswap" en Linux y cómo afecta el rendimiento del sistema?
- Un mecanismo de compresión de intercambio (swap) que mejora el rendimiento reduciendo el acceso a disco
- Un tipo de archivo para almacenar copias de seguridad
- Un módulo de red para gestionar la calidad del servicio

¿Cuál es el propósito de la herramienta `udevadm` en Linux?
- Administrar eventos y reglas de `udev` para el manejo de dispositivos de hardware
- Monitorear el uso de CPU en tiempo real
- Configurar el sistema de archivos

¿Cómo se puede obtener información detallada sobre las interrupciones y el manejo de IRQs en un sistema Linux?
- Usando el comando `cat /proc/interrupts`
- Usando el comando `top`
- Usando el comando `lsmod`

¿Qué archivo en una Raspberry Pi define el comportamiento del `GPU` y otras configuraciones relacionadas con el hardware?
- `/boot/config.txt`
- `/etc/raspberrypi-config.txt`
- `/etc/gpu.conf`

¿Qué comando se utiliza para cambiar la prioridad de los procesos en Linux?
- `renice`
- `nice`
- `ps`

¿Cuál es la diferencia entre `apt-get` y `apt` en el manejo de paquetes en Debian y sus derivados?
- `apt` es una interfaz más moderna de `apt-get`
- `apt-get` maneja solo actualizaciones de paquetes, mientras que `apt` maneja instalación y eliminación
- `apt` se usa solo para paquetes de seguridad, mientras que `apt-get` es para todos los paquetes

¿Cómo se puede configurar el enrutamiento estático en una Raspberry Pi para que el tráfico a una red específica pase por una puerta de enlace específica?
- Editando el archivo `/etc/network/interfaces` o configurando reglas en `/etc/iproute2/rt_tables`
- Usando `route add` en el archivo `/etc/rc.local`
- Configurando la puerta de enlace en `/etc/resolv.conf`

¿Qué es el "journalctl" en sistemas que utilizan `systemd` y cómo se usa?
- Una herramienta para visualizar y analizar los registros del sistema
- Una utilidad para crear archivos de registro personalizados
- Un comando para verificar la integridad del sistema de archivos

¿Cómo se puede monitorizar el tráfico de red en tiempo real?
- Ejecutando `tcpdump` seguido de los parámetros adecuados
- Usando `netstat` con opciones de monitoreo en tiempo real
- Configurando el archivo de configuración de `iptables`

¿Qué es `eBPF` (Extended Berkeley Packet Filter) y cómo se usa en Linux?
- Un mecanismo para ejecutar programas de filtrado y análisis de paquetes
- Una herramienta para compresión de datos en red
- Un módulo de hardware para mejorar la red

¿Qué significa el término `cgroups` en Linux y cuál es su función?
- Un mecanismo para controlar y limitar el uso de recursos
- Un archivo de configuración para establecer permisos de usuarios
- Una herramienta para compresión de archivos

¿Cómo se puede crear un punto de montaje en un sistema Linux usando `mount`?
- Usando el comando `mount` seguido del dispositivo y el punto de montaje deseado
- Editando el archivo `/etc/fstab` y usando `mount -a`
- Ejecutando `mkfs` para crear un sistema de archivos en el dispositivo

¿Qué comando se utiliza para revisar el estado de las conexiones de red y las tablas de enrutamiento en Linux?
- `ip route show`
- `ss -tuln`
- `traceroute`

¿Qué es `tmpfs` en Linux y cómo se utiliza?
- Un sistema de archivos en memoria que proporciona almacenamiento temporal
- Un tipo de dispositivo de almacenamiento de disco duro
- Un formato de archivo comprimido

¿Cuál es el propósito del archivo `/etc/sudoers` y cómo se edita correctamente?
- Definir las reglas para el uso del comando `sudo` y se edita usando `visudo`
- Configurar las opciones de red del sistema
- Almacenar configuraciones de servicios de sistema

¿Cómo se puede configurar la política de control de acceso en Linux usando `SELinux`?
- Definiendo políticas de seguridad en archivos de configuración específicos y aplicándolas con el comando `semanage`
- Usando el comando `iptables` para establecer reglas de acceso
- Modificando el archivo `/etc/security/limits.conf`

¿Qué comando se usa para crear una imagen de disco comprimida en Linux?
- `dd if=/dev/sda | gzip > disk.img.gz`
- `tar -cvzf disk.tar.gz /dev/sda`
- `cp -a /dev/sda disk.img`

¿Qué es el "Btrfs" y cuáles son sus características principales en comparación con otros sistemas de archivos?
- Un sistema de archivos avanzado con soporte para instantáneas
- Un sistema de archivos solo para almacenamiento de grandes cantidades de datos
- Un tipo de partición para sistemas de archivos en red

¿Qué herramienta en Linux se usa para realizar una auditoría de seguridad de archivos y directorios?
- `auditd` (Audit Daemon) y `ausearch`
- `chkrootkit`
- `rkhunter`

¿Cómo se puede configurar un entorno de red privada virtual (VPN) en una Raspberry Pi usando `OpenVPN`?
- Instalando el paquete `openvpn` y configurando archivos de configuración `.ovpn` y `server.conf`
- Configurando la red a través de `/etc/network/interfaces`
- Usando `iptables` para crear reglas de VPN

¿Qué es el "OverlayFS" en el contexto de sistemas Linux y cómo se utiliza en Raspberry Pi?
- Un sistema de archivos que combina dos directorios en uno solo
- Un protocolo de red para la transmisión de archivos grandes
- Una herramienta para la recuperación de datos de discos duros dañados

¿Cuál es la diferencia entre el comando `systemctl` y `service` en la administración de servicios en Linux?
- `systemctl` es para sistemas con `systemd`, mientras que `service` es para sistemas que usan `SysVinit` o `Upstart`
- `systemctl` se usa solo para servicios de red, mientras que `service` se usa para servicios locales
- `systemctl` maneja servicios de hardware, mientras que `service` maneja servicios de software

¿Qué es el "Device Tree" en el contexto de Raspberry Pi?
- Un mecanismo para describir el hardware del dispositivo a la capa del kernel de Linux
- Un archivo de configuración para el sistema de archivos en red
- Un módulo de kernel para la gestión de procesos en segundo plano

¿Cuál es el propósito del parámetro `noatime` en el archivo `/etc/fstab` en Linux?
- Desactivar la actualización del tiempo de acceso de archivos
- Hacer que el sistema realice una verificación de archivos al inicio
- Asegurar la sincronización en tiempo real entre el servidor y el cliente

¿Qué comando permite depurar un módulo del kernel de Linux en tiempo real?
- `dmesg`
- `strace`
- `gdb`

¿Cómo se puede compilar un módulo del kernel para Raspberry Pi desde el código fuente?
- Usando el comando `make modules` después de configurar el entorno de compilación con `make bcmrpi_defconfig`
- Ejecutando `gcc -o module.c`
- Usando el comando `make install` en el directorio del módulo

¿Qué archivo de configuración se utiliza para ajustar el "GPU Memory Split" en Raspberry Pi?
- `/boot/config.txt`
- `/etc/gpu/overlay.conf`
- `/etc/raspberrypi-config.txt`

¿Qué comando se utiliza para generar un archivo de imagen del sistema completo en una Raspberry Pi para clonación o copia de seguridad?
- `dd if=/dev/mmcblk0 of=backup.img bs=4M`
- `tar -cvzf backup.tar.gz /`
- `cp -a / /backup`

¿Qué opción del comando `rsync` permite preservar los permisos y propietarios de los archivos al sincronizar?
- `-a` (archive mode)
- `-p` (preserve permissions)
- `-o` (overwrite existing files)

¿Cuál es la función del archivo `/etc/modprobe.d/raspi-blacklist.conf` en Raspberry Pi?
- Listar módulos del kernel que deben ser bloqueados durante el arranque
- Configurar opciones de red para módulos del kernel
- Definir parámetros de compilación para módulos del kernel

¿Qué comando se usa para actualizar el archivo de intercambio (swap) en una Raspberry Pi?
- `sudo swapon -a`
- `sudo swapoff -a`
- `sudo fdisk -l`

¿Cómo se habilita el "Watchdog Timer" en una Raspberry Pi para reiniciar el sistema automáticamente en caso de fallo?
- Instalando el paquete ` watchdog` y configurando `/etc/watchdog.conf`
- Usando el comando `watchdogctl start`
- Configurando el parámetro `watchdog=1` en `/boot/config.txt`

¿Qué es `systemd-analyze` y para qué se usa en un sistema Linux?
- Una herramienta para analizar el tiempo de arranque
- Un comando para analizar el uso de disco en tiempo real
- Una utilidad para verificar la integridad del sistema de archivos

¿Qué función cumple el archivo `/etc/systemd/system/raspberrypi.service`?
- Configurar servicios personalizados para `systemd` en Raspberry Pi
- Almacenar configuraciones de hardware para `systemd`
- Definir el perfil de red para el servicio `systemd`

¿Cómo puedes ver la tabla de particiones y el esquema de particionamiento actual de un dispositivo en Linux?
- Usando `fdisk -l`
- Usando `lsblk`
- Usando `parted -s`

¿Cuál es la función de `ucm` en la configuración de audio en Linux?
- Proporcionar configuraciones de audio específicas
- Unificar los comandos de audio para todos los usuarios
- Crear perfiles de audio para aplicaciones multimedia

¿Qué es `openbox` y cómo se utiliza en Raspberry Pi OS?
- Un gestor de ventanas ligero
- Un servicio de red para la transferencia de datos
- Una herramienta de análisis de seguridad de red

¿Qué significa `RT` en `RTOS` y qué implica en el contexto de sistemas operativos?
- `Real-Time`, indicando que está diseñado para operaciones con tiempos de respuesta predictivos
- `Resource Time`, relacionado con la asignación de recursos en el sistema
- `Reliable Timing`, que asegura la precisión del reloj del sistema

¿Cómo se realiza la configuración avanzada de red en Raspberry Pi utilizando `netplan`?
- Editando archivos YAML en `/etc/netplan/` y aplicando los cambios con `netplan apply`
- Modificando el archivo `/etc/network/interfaces` y reiniciando el servicio `networking`
- Usando el comando `ifconfig` para ajustar la configuración de IP

¿Qué comando se usa para depurar problemas de red y mostrar las rutas de red en Linux?
- `traceroute`
- `ping`
- `netstat`

¿Qué es `ZRAM` y cómo mejora el rendimiento de una Raspberry Pi?
- Un dispositivo de bloque de compresión en memoria que actúa como un espacio de intercambio
- Un controlador de dispositivos para mejorar la velocidad de transferencia de datos
- Una herramienta para administrar los recursos del sistema en tiempo real

¿Qué comando de Linux te permite revisar y analizar las actividades del sistema en cuanto a los procesos de kernel?
- `perf`
- `htop`
- `sysctl`

¿Cómo se puede ajustar la configuración del reloj de tiempo real (RTC) en una Raspberry Pi?
- Configurando el módulo del kernel `rtc-ds3231` y ajustando el tiempo con `hwclock`
- Modificando el archivo `/etc/rtc.conf`
- Usando el comando `date` para establecer la hora del RTC

¿Qué es `cgroups` en Linux y cómo se utiliza para administrar recursos?
- Un mecanismo para limitar, contabilizar y aislar recursos
- Un comando para comprobar el estado de los discos duros
- Una utilidad para compresión de archivos en sistemas de archivos

¿Cómo se puede verificar el estado de la caché de memoria de disco en Linux?
- Usando el comando `cat /proc/meminfo` para observar la caché de disco
- Usando el comando `free -m`
- Usando el comando `iostat`

¿Cuál es la función de `udev` en un sistema Linux?
- Administrar eventos y dispositivos de hardware
- Configurar la red y los permisos de archivos
- Administrar usuarios y grupos en el sistema

¿Qué comando se usa para modificar la configuración de un perfil de red en Linux basado en `NetworkManager`?
- `nmcli`
- `ifconfig`
- `ip route`

¿Qué hace el comando `tune2fs` en el contexto de sistemas de archivos ext4 en Linux?
- Permite ajustar y optimizar parámetros del sistema de archivos ext4
- Crear una nueva partición en el disco
- Modificar permisos de archivo y directorio

¿Cómo se utiliza el comando `kmod` en Linux?
- Para gestionar módulos del kernel
- Para monitorear el uso de disco en tiempo real
- Para compilar código fuente
