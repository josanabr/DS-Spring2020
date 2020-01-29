# Introducción a los Sistemas Distribuidos

* Al comienzo los sistemas de cómputo operaban de forma independiente
* Aparecen luego las tecnologías de redes LAN(en un mismo edificio) y WAN(alrededor del planeta)
* Desarrollo de los microprocesadores -> múltiples núcleos (*hyperthreading*), *many core* (General Purpose GPU)

# ¿Qué es un sistema distribuido?

Un sistema distribuido es una colección de elementos autónomos de computo que parecen al usuario como un solo **sistema coherente**.

Características del sistema distribuido:

* Cada elemento es denominado nodo y actua de forma autonoma.
* Sistema debe mostrar una vista coherente al usuario final.

## ¿Qué es un *middleware*?
El middleware es el administrador de recursos en un sistema distribuido, para compartir y ejecutar los recursos que están 
disponibles a través de la red de una manera eficiente.
Middleware es a un sistema distribuido lo que un servicio del sistema operativo es a un equipo.

# Metas de diseño de los sistemas distribuidos

* Soporte para compartir recursos. Hoy en día fundamentalmente recursos de almacenamiento y/o procesamiento
* Abierto permite que el sistema sea extensible y desplegable en casi cualquier plataforma
