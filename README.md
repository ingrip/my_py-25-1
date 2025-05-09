# Proyecto del Primer Parcial

El propósito de este proyecto es crear una aplicación interactiva desarrollada en Bash, cuyo objetivo principal es facilitar el aprendizaje de distintas metodologías de desarrollo de software, abarcando tanto enfoques ágiles como tradicionales. La aplicación debe cumplir con una serie de especificaciones funcionales que aseguren una experiencia completa para el usuario.

## Getting Started

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local y/o dentro de un contenedor Docker.

### Prerequisites

Qué necesitas instalar para ejecutar el software:

```

Bash Shell

```
```

Docker (opcional, para la versión empaquetada)

```

### Installing

#### Opción 1: Usando Bash Shell directamente

```

chmod +x script.sh  # Dar permisos de ejecución
./script.sh -a      # Para metodologías ágiles
./script.sh -t      # Para metodologías tradicionales

```

#### Opción 2: Usando Docker

```

# Construir la imagen

docker build -t metodologias .

# Ejecutar el contenedor

docker run -it metodologias -a  # Puede ser -a o -t según lo que se desee usar

```

Una vez ejecutado, podrás navegar por las metodologías disponibles y utilizar el submenú para agregar, buscar, eliminar o leer información.

## Running the tests

*Esta aplicación no incluye pruebas automatizadas, pero puedes verificar su funcionalidad ejecutando comandos en la terminal y validando que se modifiquen correctamente los archivos `.inf` según las operaciones realizadas.*

### Break down into end to end tests

Simulación manual de pruebas de principio a fin:

```

Agregar concepto -> Verificar que aparece en archivo .inf
Buscar concepto -> Verificar salida en pantalla
Eliminar concepto -> Confirmar que ya no aparece en archivo .inf
Leer base -> Verificar contenido desplegado

```

### And coding style tests

No aplica en este caso, ya que es un script en Bash sin linters configurados. Se recomienda mantener una indentación coherente y uso claro de variables.

## Deployment

Para desplegar la aplicación en un entorno real, basta con ejecutar la imagen Docker en cualquier servidor con Docker instalado. Esto facilita su portabilidad y ejecución sin configuración adicional.

## Built With

* **Bash** – Lenguaje utilizado para desarrollar la aplicación
* **Docker** – Usado para empaquetar y distribuir la app

## Contributing

Todos los miembros del equipo deben contribuir activamente vía Git. Por favor revisa [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) para más detalles sobre cómo contribuir al proyecto.

## Versioning

Se utiliza [SemVer](http://semver.org/) para el control de versiones. Para ver las versiones disponibles, consulta los [tags en este repositorio](https://github.com/your/project/tags).

## Authors

* **Juan Pérez** – *Trabajo inicial*
* **María López**
* **Pedro Ruiz**

Ver también la lista de [contribuyentes](https://github.com/your/project/contributors) que participaron en este proyecto.

## License

Este proyecto está licenciado bajo la Licencia MIT – consulta el archivo [LICENSE.md](LICENSE.md) para más detalles.

## Acknowledgments

* A nuestro profesor(a) por la guía durante el curso
* A los compañeros por sus aportaciones
* A la documentación oficial de Docker y Bash por la referencia
