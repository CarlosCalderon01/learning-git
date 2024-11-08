# Linux Guide and Cheat Sheet

## Table of Contents
- [Introduction to Linux](#introduction-to-linux)
- [Tips and Best Practices](#tips-and-best-practices)
- [Essential Commands](#essential-commands)
- [Additional Resources](#additional-resources)

---

## Introduction to Linux
Linux es un sistema operativo de código abierto que ofrece una gran flexibilidad y control sobre el sistema. Es utilizado por desarrolladores, administradores de sistemas y entusiastas de la tecnología debido a su estabilidad, seguridad, y capacidad de personalización.

---

## Tips and Best Practices
Aquí algunos consejos para aprovechar al máximo Linux:

1. **Familiarízate con la terminal:** Gran parte del poder de Linux reside en su línea de comandos. Practicar los comandos básicos puede mejorar tu eficiencia.
2. **Organiza tus archivos:** Mantén una estructura organizada en tu directorio `home` para que sea más fácil localizar y manejar archivos.
3. **Usa permisos de archivos con precaución:** Usa `chmod` y `chown` para establecer permisos de archivos de manera segura. Evita dar permisos de ejecución innecesarios.
4. **Automatiza tareas con cron:** Usa cron para programar tareas automáticas, como copias de seguridad o limpieza de archivos temporales.
5. **Mantén el sistema actualizado:** Regularmente ejecuta actualizaciones del sistema usando el gestor de paquetes de tu distribución (`apt`, `yum`, `dnf`, etc.).
6. **Aprende a usar `man` y `--help`:** Muchos comandos tienen documentación integrada, que puedes consultar con `man [comando]` o `[comando] --help`.
7. **Usa alias para comandos frecuentes:** Crea atajos de comandos usando alias. Por ejemplo, `alias ll='ls -la'`.

---

## Essential Commands

| Command                   | Description                                                                                     |
|---------------------------|-------------------------------------------------------------------------------------------------|
| `ls`                      | Lista archivos y directorios en el directorio actual.                                           |
| `pwd`                     | Muestra el directorio de trabajo actual.                                                        |
| `cd [directory]`          | Cambia al directorio especificado.                                                              |
| `mkdir [directory]`       | Crea un nuevo directorio.                                                                       |
| `rmdir [directory]`       | Elimina un directorio vacío.                                                                    |
| `rm [file]`               | Elimina un archivo.                                                                             |
| `rm -r [directory]`       | Elimina un directorio y su contenido de forma recursiva.                                        |
| `cp [source] [destination]` | Copia archivos o directorios.                                                               |
| `mv [source] [destination]` | Mueve o renombra archivos y directorios.                                                    |
| `find [path] -name "[pattern]"` | Busca archivos y directorios que coincidan con un patrón en una ruta específica.    |
| `grep "[pattern]" [file]` | Busca un patrón de texto dentro de un archivo.                                                 |
| `chmod [permissions] [file]` | Cambia los permisos de un archivo o directorio.                                         |
| `chown [user]:[group] [file]` | Cambia el propietario y el grupo de un archivo o directorio.                             |
| `ps aux`                  | Muestra una lista de todos los procesos en ejecución.                                           |
| `kill [PID]`              | Termina un proceso específico usando su ID de proceso (PID).                                    |
| `top`                     | Muestra los procesos en ejecución en tiempo real y el uso de recursos del sistema.              |
| `df -h`                   | Muestra el uso del disco de forma legible para humanos.                                         |
| `du -sh [directory]`      | Muestra el tamaño de un directorio específico.                                                  |
| `tar -czvf [archivo.tar.gz] [directory]` | Crea un archivo comprimido en formato tar.gz.                           |
| `unzip [archivo.zip]`     | Descomprime un archivo zip.                                                                     |
| `wget [URL]`              | Descarga archivos desde la web.                                                                 |
| `curl [URL]`              | Realiza solicitudes web y muestra el resultado en la terminal.                                  |
| `man [command]`           | Muestra el manual de un comando.                                                                |
| `history`                 | Muestra el historial de comandos ejecutados.                                                    |
| `alias ll='ls -la'`       | Crea un alias para un comando. En este caso, `ll` ejecutará `ls -la`.                          |
| `crontab -e`              | Abre el archivo de configuración de cron para programar tareas automáticas.                     |
| `sudo [command]`          | Ejecuta un comando como superusuario o administrador.                                           |
| `apt update && apt upgrade` | Actualiza los paquetes en distribuciones basadas en Debian.                                |
| `yum update`              | Actualiza los paquetes en distribuciones basadas en Red Hat.                                    |

---

## Additional Resources
- [Linux Documentation Project](https://www.tldp.org/)

- [Linux Command Cheat Sheet](https://cheatography.com/davechild/cheat-sheets/linux-command-line/)

- [The Linux Foundation - Training and Certification](https://training.linuxfoundation.org/)
