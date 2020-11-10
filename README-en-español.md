pacman
======

Agrega alias para el administrador de paquetes pacman.

También incluye ayudante(s) opcional(es).

Ajustes
--------
<!-- Set `wrapper_here` to a wrapper if applicable (powerpill, pacmatic, etc): TODO: buscar mejores terminos paea wrapper -->
Establece `wrapper_aquí` a un wrapper si aplica (powerpill, pacmatic, etc):

    zstyle ':zim:pacman' frontend 'wrapper_aquí'

Agrega cualquier script de ayudante para ser cargado.

    zstyle ':zim:pacman' helpers 'aur'


Ayudantes
-------

### aur

Provee alias simples para el ayudante del AUR.

  * `aurb nombre_del_paquete` clona el paquete del AUR, lo compila e instala.
  * `aurd nombre_del_paquete` clona el paquete del AUR, pero no lo compila.
  * `auru` ejecuta dentro de un directorio creado con `aurb`, esto actualizar, compilara e instalara un paquete.

Alias
-------

### Compilación

  * `pacb` compila un paquete en la carpeta/directorio actual, limpia, e instala.

### Instalación

  * `paci` instala, sincroniza y actualiza los paquete(s).
  * `pacu` instala, sincroniza y actualiza los paquete(s) (actualiza la lista de paquetes forzosamente).
  * `pacU` instala paquetes desde un archivo pkg.
  * `pacd` instala todos los paquetes presentes en la carpeta actual.

### Eliminación

  * `pacr`  elimina el/los paquetes y las dependencias innecesarias.
  * `pacrm` elimina el/los paquete(s), dependencias innecesarias y archivos de configuración.

### Consultas

  * `pacq` consulta información del paquete(s) desde el repositorio remoto.
  * `pacQ` consulta información del paquete(s) desde el repositorio local.

### Búsqueda

  * `pacs` busca el/los paquete(s) en el repositorio remoto.
  * `pacS` busca el/los paquete(s) en el repositorio local.

### Huérfanos

  * `pacol` muesta una lista de todos los paquetes huérfanos.
  * `pacor` elimina todos los paquetes huérfanos.

### Base de datos
  * `pacpexp` marca el/los paquete(s) como instalados explícitamente.
  * `pacpdep` marca el/los paquete(s) como instalados inexplicablemente o dependencias.

### Propiedad

  * `pacown`   lista todos los archivos proporcionados por un(os) paquete(s) dado(s)
  * `pacblame` muestra el/los paquete(s) que son propietario(s) del archivo especificado.

---
---
yay alias
======

Agrega alias para el ayudante de AUR yay.

Alias
-------

### General

  * `yconf` muestra(imprime) en pantalla la configuración actual de yay.

### Instalación

  * `yi` instala, sincroniza y actualiza los paquetes.
  * `yu` instala, sincroniza y actualiza los paquete(s) (actualiza la lista de paquetes forzosamente).
  * `yU` instala paquetes desde un archivo pkg.
  * `yd` instala todos los paquetes presentes en la carpeta actual.

### Eliminación

  * `yr`  elimina el/los paquetes y las dependencias innecesarias.
  * `yrm` elimina el/los paquete(s), dependencias innecesarias y archivos de configuración.

### Consultas

  * `yq` consulta información del paquete(s) desde el repositorio remoto.
  * `yQ` consulta información del paquete(s) desde el repositorio local.

### Búsqueda

  * `ys` busca el/los paquete(s) en el repositorio remoto.
  * `yS` busca el/los paquete(s) en el repositorio local.

### Huérfanos

  * `yol` muesta una lista de todos los paquetes huérfanos.
  * `yor` elimina todos los paquetes huérfanos.

### Propiedad

  * `yown`   lista todos los archivos proporcionados por un(os) paquete(s) dado(s).
  * `yblame` muestra el/los paquete(s) que son propietario(s) del archivo especificado.
  
  
----
----

## Ayuda y retroalimentacion

Si gustan hacer comentarios sobre la traduccion son libres de abrir un issue y/o hacer pull request. Tambien si se les ocurre algun otro alias o funcionalidad.  
El README.md original en ingles se encuentra [aquí](README-original.md).  
Espero que les sea de utilidad la traducción.
