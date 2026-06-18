# Sistema de Gestión de Incidencias Distribuido

## Descripción

Sistema distribuido de gestión de incidencias (tickets) desarrollado en Java que permite a múltiples clientes registrar incidencias y a varios técnicos gestionarlas de forma concurrente mediante una arquitectura cliente-servidor.

El proyecto implementa conceptos de programación concurrente, comunicación en red, sincronización de recursos compartidos e interfaces gráficas con Swing.

## Características Principales

* Creación de tickets de incidencia.
* Registro y gestión de técnicos.
* Asignación manual y automática de incidencias.
* Atención de tickets de forma concurrente mediante múltiples hilos.
* Resolución y actualización del estado de incidencias.
* Consulta de tickets desde clientes conectados.
* Interfaz gráfica desarrollada con Java Swing.
* Comunicación cliente-servidor mediante sockets TCP.
* Acceso sincronizado a estructuras compartidas para garantizar la integridad de los datos.

## Información de los Tickets

Cada ticket contiene:

* ID único
* Cliente
* Descripción
* Prioridad
* Estado
* Técnico asignado

## Arquitectura

El sistema sigue una arquitectura distribuida compuesta por:

### Servidor

* Gestión centralizada de tickets.
* Control de técnicos registrados.
* Sincronización de accesos concurrentes.
* Procesamiento de solicitudes de los clientes.

### Clientes

* Creación y consulta de incidencias.
* Comunicación con el servidor.
* Interfaz gráfica para interacción con el sistema.

### Técnicos

* Ejecución mediante hilos independientes.
* Atención simultánea de incidencias.
* Actualización del estado de los tickets.

## Tecnologías Utilizadas

* Java
* Java Swing
* Programación Concurrente (Threads)
* Sockets TCP
* Colecciones sincronizadas
* Arquitectura Cliente-Servidor

## Funcionalidades Implementadas

### Entrega 1

* Comunicación cliente-servidor.
* Gestión completa del ciclo de vida de un ticket.
* Concurrencia mediante múltiples hilos.
* Sincronización de recursos compartidos.
* Interfaz gráfica funcional.
* Listado y actualización de incidencias.

### Entrega 2

* Historial de tickets.
* Persistencia de datos.
* Estadísticas del sistema.
* Exportación de información.
* Actualización en tiempo real.

## Ejecución

### Iniciar el servidor

```bash
java Servidor
```

### Iniciar un cliente

```bash
java Cliente
```

## Objetivos del Proyecto

Este proyecto fue desarrollado con el objetivo de aplicar conocimientos de:

* Programación orientada a objetos.
* Programación concurrente.
* Comunicación en red.
* Sistemas distribuidos.
* Interfaces gráficas.
* Diseño de software cliente-servidor.

## Autor

Brian Desposorio

Proyecto académico desarrollado durante el ciclo formativo de Desarrollo de Aplicaciones Multiplataforma (DAM).
