# TP4 — Módulos de Kernel

### Grupo: Apache Tevez

### Profesores:

- Miguel Angel Solinas

- Javier Jorge

## Integrantes

| Nombre                            | Correo Electrónico                |
| --------------------------------- | --------------------------------- |
| Facundo Emanuel Avila Diaz Moreno | facundo.avila.027@mi.unc.edu.ar   |
| Candela Abigail Vergara           | candela.vergara@mi.unc.edu.ar     |
| Joaquín Alejandro Salinas         | joaquin.salinas.874@mi.unc.edu.ar |

## Desafío #2

### ¿ Qué funciones tiene disponible un programa y un módulo ?

Funciones disponibles para un Programa

Un programa en ejecución tiene acceso a cuatro grandes grupos de funciones:

1. Funciones propias: Las que el programador definió directamente en el código fuente (por ejemplo main(), funciones auxiliares, etc.).
2. Funciones de biblioteca estándar: Se enlazan durante la compilación o en tiempo de ejecución. Son funciones ya implementadas que el sistema provee (printf, malloc, strlen, etc.).
3. Funciones de módulos importados: Cualquier función pública que se haya importado de otro módulo o librería externa. Solo se accede a las que el módulo exporta.
4. Llamadas al sistema (syscalls): Interfaz directa con el sistema operativo. Son los servicios que el SO expone para manejo de archivos (open, read, write), procesos (fork, exec), redes (socket), memoria, etc.

### Espacio de usuario o espacio del kernel.

### Espacio de datos.

### Drivers. Investigar contenido de /dev.
