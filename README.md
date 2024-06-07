# PracticaJSON
# Tabla de contenidos
- [JSON](#json)
  - [¿Qué es JSON?](#qué-es-json)
  - [¿Para qué sirve un archivo JSON?](#para-qué-sirve-un-archivo-json)
  - [¿Dónde se utiliza JSON?](#dónde-se-utiliza-json)
  - [Ejemplos de archivos JSON](#ejemplos-de-archivos-json)
    - [Strings](#strings)
    - [Objetos](#objetos)
    - [Arreglos](#arreglos)
    - [Booleanos](#booleanos)
    - [Null](#null)
  - [¿Cómo abrir un archivo JSON?](#cómo-abrir-un-archivo-json)
 
> [!CAUTION]
> Leer este documento puede producir un aumento masivo de intelecto.

# JSON
![JSON](https://static.vecteezy.com/system/resources/previews/015/426/183/non_2x/json-file-format-icon-json-extension-line-icon-free-vector.jpg)

## ¿Qué es JSON?
JSON (JavaScript Object Notation) es un formato de texto ligero para el intercambio de datos. Es fácil de leer y escribir para los humanos, y fácil de analizar y generar para las máquinas. JSON se basa en una subconjunto del lenguaje de programación JavaScript, pero es independiente de cualquier lenguaje de programación específico. Es ampliamente utilizado en la transmisión de datos entre un servidor y una aplicación web, sirviendo como una alternativa más sencilla a XML.

## ¿Para qué sirve un archivo JSON?
Un archivo JSON se utiliza para almacenar y transportar datos estructurados. Los archivos JSON son comunes en aplicaciones web, donde se intercambian datos entre un servidor y un cliente. Gracias a su formato legible, JSON es ideal para configuraciones, almacenamiento de datos, y transmisión de información entre servicios.

## ¿Dónde se utiliza JSON?
JSON se utiliza en diversas áreas, incluyendo:
- Aplicaciones web para enviar y recibir datos desde servidores.
- APIs RESTful para la transmisión de datos entre sistemas.
- Configuración de software, donde los archivos JSON almacenan parámetros de configuración.
- Archivos de datos que requieren ser importados o exportados en diferentes aplicaciones y plataformas.

## Ejemplos de archivos JSON
### Strings
```
{
  "nombre": "Juan",
  "ciudad": "Madrid"
}
```

### Objetos
```
{
  "coche": {
    "marca": "Seat",
    "Matrícula": 4567GRF,
    "ciudad": "Sueca"
  }
}
```
### Arreglos
```
{
  "jugadores": ["Messi", "Neymar", "Gabi"]
}
```
### Booleanos
```
{
  "esCorrecto": true,
  "esImagen": false
}
```
### Null
```
{
  "fotografia": null
}
```
## ¿Cómo abrir un archivo JSON?
Para abrir un archivo JSON, se pueden usar diversos programas y métodos:

- Editores de texto como Visual Studio Code, Sublime Text, o Notepad++.
- - Lenguajes de programación como Python, JavaScript, y otros, que tienen bibliotecas para manipular JSON.
- Navegadores web que pueden mostrar la estructura JSON.


# YAML
![YAML](https://media.licdn.com/dms/image/D4D12AQGtHSb18Dvh1Q/article-cover_image-shrink_720_1280/0/1695637064391?e=2147483647&v=beta&t=wRiEJFQmw12BL5FA65i2yn18DdsYkfR3Xo4V6Kn7uuY)

## ¿Qué es YAML?
YAML (YAML Ain't Markup Language) formato de serialización de datos legible para los humanos, utilizado para archivos de configuración.Fácil de leer y escribir, con sintaxis más simple y limpia, fácil uso para los desarrolladores y administradores de sistemas.

## Sintaxis de YAML
YAML utiliza una sintaxis basada en indentación para definir la estructura de los datos, sin corchetes o comas. Ejemplo básico de un archivo YAML:
```
persona:
  nombre: Jose
  edad: 46
  ciudad: Sueca

Equipos:
  - Valencia
  - Barcelona
  - Madrid

esActivo: true
apellido: null
```

# Diferencias entre JSON y YAML
- Comentarios: YAML permite comentarios usando #, mientras que JSON no soporta comentarios.
- Legibilidad: YAML es generalmente más legible y fácil de escribir para los humanos debido a su sintaxis minimalista, mientras que JSON es más verboso.
- Uso de espacios: YAML depende de la indentación para definir la estructura, mientras que JSON utiliza llaves y corchetes.
- Compatibilidad: JSON es un subconjunto de JavaScript y es ampliamente soportado en aplicaciones web, mientras que YAML es más común en archivos de configuración.

# Bibliografía
- [JSON](https://blog.hubspot.es/website/que-es-json).
- [YAML](https://www.redhat.com/es/topics/automation/what-is-yaml).
- [Diferencias entre JSON y YAML](https://aws.amazon.com/es/compare/the-difference-between-yaml-and-json/).
