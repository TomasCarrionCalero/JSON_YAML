## JSON_YAML

## TABLA DE CONTENIDOS
- [JSON_YAML](#JSON_YAML)
- [INTRODUCCIÓN](#INTRODUCCIÓN)
- [YAML](#YAML)
- [¿Qué_es_YAML?](#¿Qué_es_YAML?)
- [Características](#Características)
- [Cuándo_usaR_YAML_en_lugar_de_JSON](#Cuándo_usar_YAML_en_lugar_de_JSON)
- [Ejemplo_de_YAML](#Ejemplo_De_YAML)


### INTRODUCCIÓN
YAML y JSON son dos formatos de serialización de datos que proporcionan un mecanismo de intercambio de datos legible por humanos. Dan formato a los datos de manera estandarizada para su intercambio entre aplicaciones de software, y su texto también es legible por humanos.

### YAML
### ¿Qué es YAML?
YAML es un lenguaje de serialización de datos que se usa para escribir archivos de configuración para la implementación de infraestructura. Por ejemplo, si quiere implementar una aplicación de Docker en Kubernetes, tendrá que usar un archivo YAML para configurar la instancia
### Características
- *Legible por humanos*: Diseñado para ser fácil de leer y escribir.
- *Formato de datos*: Utiliza sangrías para representar la estructura de los datos.

### Cuándo usar YAML en lugar de JSON

Gracias al soporte generalizado y la integración con JavaScript, JSON es un formato de serialización de datos más popular que YAML para la mayoría de los casos de uso. JSON se usa ampliamente en comunicaciones de software distribuidas, aplicaciones web, archivos de configuración y API.

Aunque YAML pueda parecer una mejor opción en función de la tipificación de datos y su formato legible por humanos, normalmente se prefiere JSON por motivos de compatibilidad cruzada. Esto se debe a que muchas aplicaciones y servicios ya analizan el formato de datos JSON.

Por otro lado, YAML ha ganado una fuerte presencia en determinados ámbitos de la computación debido a su legibilidad y soporte de comentarios. En particular, YAML es el principal formato de serialización de datos para archivos de configuración en muchas herramientas y servicios de automatización, DevOps e infraestructura como código (IaC). Por ejemplo, YAML se usa a menudo en archivos de Docker y Kubernetes.


### Ejemplo de YAML
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
