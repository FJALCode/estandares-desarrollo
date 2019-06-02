## Estructura Base
La estructura base de un proyecto de NodeJS es la siguiente:

```
.
├── db                      //Carpeta donde se encuentran los scripts de base de datos a correr.
├── docs                    //Carpeta que servira para guardar la documentación del api desarrollado.
├── src                     //Carpeta donde se guardara el source code del api
│   ├── config              //Carpeta que contiene el archivo de configuración del api. 
│   ├── controllers         //Carpeta donde se hara el desarrollo de los servicios, contiene todos los controladores.
│   ├── cron                //Carpeta destinada para guardar las tarea programadas en caso de ser necesario.
│   ├── libraries           //Carpeta destinada para crear todas la bibliotecas/modulos o librerias necesarias para la logica de negocio del api a construir.
│   ├── locales             //Carpeta donde se encuentra la internacionalización.
│   ├── middlewares         //Carpeta donde se guardaran funciones y clases utilitarias que podran ser ejecutadas previa a la ejecución de un servicio.
│   ├── models              //Carpeta donde se guardaran los modelos mapeados de la base de datos.
│   ├── test                //Carpeta destinada para guardar las pruebas.
│   │   ├── unit            //Carpeta destinada para guardar las pruebas unitarias.
│   │   │   ├── modulos     //Módulo acorde a la aplicación 
│   │   │   │   ├── Prueba1Test.js 
│   │   ├── integration     //Carpeta destinada para guardar las pruebas de integración.
│   │   │   │   ├── modulos //Módulo acorde a la aplicación 
│   │   │   │       ├── Prueba2Test.js
│   │   ├── functional      //Carpeta destinada para guardar las pruebas funcionales.
│   │   │   │   ├── modulos //Módulo acorde a la aplicación
│   │   │   │   │   ├── Prueba3Test.js
│   │   ├── test            //Carpeta destinada para guardar las pruebas unitarias.
│   │   ├── test            //Carpeta destinada para guardar las pruebas unitarias.
│   ├── utils               //Carpeta con las clases utilitarias y librerias externas.
│   ├── app.js              //Punto de entrada del servicio.
│   ├── package.jason       //Archivo para manejar dependencias npm
│   └── routes.js           //Archivo que contiene todas las rutas de los servicios desarrollados.
└── README.md               //Información general del proyecto
```


## Documentación
Todo código fuente debe estar perfectamente documentado 

```
├── src             //Código fuente
│   ├── Gruntfile   //Archivo que contiene las rutinas para generar la documentación automaticamente.
│   ├── _apidoc.js  //Archivo que contiene la documentación de versiones viejas del api.
│   ├── apidoc.json //Archivo de configuración de la herramienta apiDoc para generar documentación de apis. 
```                



