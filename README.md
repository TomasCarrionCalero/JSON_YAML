## JSON_YAML
### INTRODUCCIÓN
YAML y JSON son dos formatos de serialización de datos que proporcionan un mecanismo de intercambio de datos legible por humanos. Dan formato a los datos de manera estandarizada para su intercambio entre aplicaciones de software, y su texto también es legible por humanos.

### YAML
#### ¿Qué es YAML?
YAML es un lenguaje de serialización de datos que se usa para escribir archivos de configuración para la implementación de infraestructura. Por ejemplo, si quiere implementar una aplicación de Docker en Kubernetes, tendrá que usar un archivo YAML para configurar la instancia
#### Características
- *Legible por humanos*: Diseñado para ser fácil de leer y escribir.
- *Formato de datos*: Utiliza sangrías para representar la estructura de los datos.

#### Ejemplo de YAML
```YAML
{
nombre: Pepe
edad: 12  
ciudad: Bocairent
curso: Sexto de primaria
  - un crack
}

### JSON
#### ¿Qué es JSON?
Qué es JSON? JSON es un formato de texto que forma parte del sistema de JavaScript y que se deriva de su sintaxis, pero no tiene como objetivo la creación de programas, sino el acceso, almacenamiento e intercambio de datos. Usualmente es conocido como una alternativa al lenguaje XML

#### Características Principales
- **Ligero**: Formato compacto y eficiente.
- **Independiente del lenguaje**: Compatible con la mayoría de los lenguajes de programación.
- **Estructura de datos simple**: Utiliza objetos (mapas) y arreglos (listas).

#### Ejemplo de JSON
```json
{
  "nombre": "Pepe",
  "edad": 12,
  "ciudad": "Bocairent",
}

