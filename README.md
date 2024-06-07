# PracticaJSON
{
  "Tabla de contenidos": [
    "JSON",
    {
      "Subsecciones": [
        "¿Qué es JSON?",
        "Usos de un archivo JSON",
        "Aplicaciones de JSON",
        "Ejemplos de archivos JSON",
        {
          "Tipos de datos": [
            "Cadenas de texto",
            "Objetos",
            "Listas",
            "Valores booleanos",
            "Null"
          ]
        },
        "Cómo abrir un archivo JSON"
      ]
    },
    "YAML",
    {
      "Subsecciones": [
        "¿Qué es YAML?",
        "Sintaxis de YAML",
        "Diferencias entre JSON y YAML",
        "Bibliografía"
      ]
    }
  ],
  "Aviso": "Leer este documento puede aumentar significativamente tu conocimiento.",
  "JSON": {
    "Descripción": "JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos. Es fácil de leer y escribir para los humanos, y fácil de interpretar y generar para las máquinas. JSON se basa en un subconjunto del lenguaje de programación JavaScript, pero es independiente de cualquier lenguaje de programación específico. Es ampliamente utilizado para la transmisión de datos entre un servidor y una aplicación web, ofreciendo una alternativa más sencilla a XML.",
    "Usos": "Un archivo JSON se utiliza para almacenar y transmitir datos estructurados. Es común en aplicaciones web, donde se intercambian datos entre un servidor y un cliente. Gracias a su formato legible, JSON es ideal para configuraciones, almacenamiento de datos y transmisión de información entre servicios.",
    "Aplicaciones": [
      "Aplicaciones móviles para sincronizar datos entre dispositivos.",
      "APIs GraphQL para la consulta eficiente de datos.",
      "Configuración de aplicaciones, donde los archivos JSON definen parámetros y opciones.",
      "Archivos de exportación e importación para herramientas de software."
    ],
    "Ejemplos": {
      "Cadenas de texto": {
        "libro": "Cien años de soledad",
        "autor": "Gabriel García Márquez"
      },
      "Objetos": {
        "curso": {
          "titulo": "Introducción a la programación",
          "duracion": 10,
          "nivel": "Principiante"
        }
      },
      "Listas": {
        "ciudades": ["Bogotá", "Medellín", "Cali"]
      },
      "Valores booleanos": {
        "estaDisponible": true,
        "esGratuito": false
      },
      "Null": {
        "codigoPromocional": null
      }
    },
    "Cómo abrir un archivo JSON": [
      "Editores de texto como Atom, Brackets o Visual Studio Code.",
      "Navegadores web con extensiones JSON viewer.",
      "Lenguajes de programación como Ruby, PHP y otros, que tienen bibliotecas para manipular JSON."
    ]
  },
  "YAML": {
    "Descripción": "YAML (YAML Ain't Markup Language) es un formato de serialización de datos legible para los humanos, comúnmente utilizado para archivos de configuración. Al igual que JSON, es fácil de leer y escribir, pero tiene una sintaxis más simple y limpia, lo que facilita su uso para desarrolladores y administradores de sistemas.",
    "Sintaxis": {
      "curso": {
        "titulo": "Introducción a la programación",
        "duracion": 10,
        "nivel": "Principiante"
      },
      "ciudades": ["Bogotá", "Medellín", "Cali"],
      "estaDisponible": true,
      "codigoPromocional": null
    },
    "Diferencias": {
      "Legibilidad": "YAML es generalmente más legible y fácil de escribir para los humanos debido a su sintaxis minimalista, mientras que JSON es más verboso.",
      "Uso de espacios": "YAML depende de la indentación para definir la estructura, mientras que JSON utiliza llaves y corchetes.",
      "Comentarios": "YAML permite comentarios usando `#`, mientras que JSON no soporta comentarios.",
      "Compatibilidad": "JSON es un subconjunto de JavaScript y es ampliamente soportado en aplicaciones web, mientras que YAML es más común en archivos de configuración."
    }
  },
  "Bibliografía": [
    "https://blog.hubspot.es/website/que-es-json",
    "https://www.redhat.com/es/topics/automation/what-is-yaml",
    "https://aws.amazon.com/es/compare/the-difference-between-yaml-and-json/"
  ]
}
