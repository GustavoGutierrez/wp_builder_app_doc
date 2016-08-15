# Aplicación
[Como agregar acciones](add-action.md) |
[Como agregar metabox](add-metabox.md)


La carpeta **app** contiene todo el codigo de su aplicación en este puede crear los plugins que en conjunto conforman su aplicación tenga en cuenta que el pligin esta pensado cuando requiere desarrollar funcionalidades complejas que requieran de multiples de darrollo personalizado de plugins y funcionalidades que deden desarrollarse totalmente; solo en este caso wp builder app le sera de utilidad.

La carpeta **Plugins** dendro de app contiene todas las funcionalidades que conforman su aplicasión entre ellas se encuntra la creación de posttype, taxonomias, metaboxes, etc. ademas de permitirle autoguardar los metadatos que cree sin escribir ninguna sola linea de codigo.

La carpeta **Views** contiene las plantillas en formato .html que contiene código que se renderiza con [Mustache PHP](https://github.com/bobthecow/mustache.php/wiki "Documentación") de esta manera se le permitira crear plantillas html más limpias en formato mustache que se renderizaran en donde usted lo decida ademas de poder separar sus plantillas en partials reutilizables en multiples templates tambien es posible desarrollar layout para optimizar de esta forma el trabajo y reutilizar marcos html comunes dentro de su aplicasión.

La carpeta **Resources** contiene los estilos css en formato sass ademas de los **scripts** en typescript para el desarrollo javascript que seran compilados y generados en la carpeta assets a sus respectivas carpetas **css** y **js**.

La carpeta **Lang** contiene el los archivos .po de lenguages utilizados en su aplicación es posible organizar sus lenguajes separados por plugins o crear solo un archivo de lenguaje que contenga todas las traduciones de su aplicación.

app

├── assets

│   ├── css

│   │   ├── app.css

│   │   └── app.css.map

│   ├── images

│   └── js

│       └── app.js

├── Config


│   ├── app.php


│   └── view.php


├── Lang


├── Plugins


│   ├── Dummies.php


│   └── Plugin.php


├── Resources


│   └── assets


│       ├── scripts


│       │   ├── app.ts


│       │   └── modules


│       └── styles


│           ├── app.css


│           └── modules


│               ├── \_foo.css


│               └── \_foo.less


└── Views


    ├── dummies.html


    ├── index.html


    └── partials


        └── dummy.html

