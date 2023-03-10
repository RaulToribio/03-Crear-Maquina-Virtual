# Introducción

Una máquina virtual es un software que simula un sistema informático completo, incluyendo hardware, como procesador, memoria y dispositivos de entrada y salida. Esto permite ejecutar diferentes sistemas operativos y aplicaciones en una sola máquina física, aislándolos entre sí. Esto es útil para probar aplicaciones en diferentes entornos, ejecutar sistemas operativos antiguos o incluso ejecutar aplicaciones que no son compatibles con el sistema operativo del host. Algunos ejemplos de software de máquina virtual son VirtualBox, VMware y Hyper-V.

# Material Necesario

- [VirtualBox](https://github.com/RaulToribio/01-Instalar-VirtualBox)
- [Ubuntu 22.04.1 LTS](https://github.com/RaulToribio/02-Descargar-Ubuntu)

# Material de Referencia

- [Instalación de Ubuntu 20.04 en VirtualBox Windows (Codigo IoT)](https://edu.codigoiot.com/course/view.php?id=812)

# Instrucciones

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(1).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(1).png?raw=true)

Clic en “Nueva”.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(2).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(2).png?raw=true)

Se mostrará la siguiente ventana.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(3).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(3).png?raw=true)

Escribir un nombre que identifique a la máquina virtual, si el nombre de nuestra máquina virtual está relacionado con “Ubuntu”, VirtualBox asignará valores por defecto para el *tipo* y la *versión* de sistema operativo como *Linux - Ubuntu (64-bit)*.

Seleccionar el folder donde se guardarán los datos de la máquina virtual.

La ubicación predeterminada es *C:\Users\Raul Toribio\VirtualBox VMs.*

Seleccionar “Otro” en el apartado “ISO Image”.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(4).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(4).png?raw=true)

Ubicar la Imagen ISO de Ubuntu 22.04.1 descargada previamente.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(5).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(5).png?raw=true)

Check en “Skip Unattended installation”.

Esto permitirá configurar manualmente la instalación de Ubuntu 22.04.1.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(6).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(6).png?raw=true)

Clic en “Next".

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(7).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(7).png?raw=true)

Los recursos de RAM y Procesador se dividirán a la mitad.

$RAM\ Máquina\ Virtual=\frac{RAM\ Total}{2}\ *\ 1,024\ \frac{MB}{GB}.$

$RAM\ Máquina\ Virtual=\frac{32\ GB}{2}\ *\ 1,024\ \frac{MB}{GB}.$

$RAM\ Máquina\ Virtual=16,384\ MB.$

$Procesadores\ Máquina\ Virtual=\frac{Procesadores\ Totales}{2}.$

$Procesadores\ Máquina\ Virtual=\frac{8}{2}.$

$Procesadores\ Máquina\ Virtual=4.$

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(8).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(8).png?raw=true)

Asignar 50 GB de almacenamiento en la opción “Create a Virtual Hard Disk Now”.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(9).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(9).png?raw=true)

Se mostrará el resumen de las configuraciones realizadas.

![https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(10).png?raw=true](https://github.com/RaulToribio/03-Crear-Maquina-Virtual/blob/main/Im%C3%A1genes/Crear%20M%C3%A1quina%20Virtual%20(10).png?raw=true)

Así se verá la máquina virtual ya configurada.

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>
