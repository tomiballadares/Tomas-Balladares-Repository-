
# 🚀🚀 Repositorio de Tomas Balladares 🚀🚀

Repositorio utilizado para los ejercicios del proceso de selección para ProContacto.

# 🚀 About Me


Buenas! Mi nombre es Tomas Julian Balladares, soy estudiante de Ingeniería en Sistemas de Información (UTNBA). Encontré esta propuesta laboral a través de la bolsa de trabajo de la universidad y me pareció muy interesante todo lo que conlleva trabajar para ProContacto.

Ante todo, les agradezco por darme la oportunidad y por contactarse.

Les dejo mi perfil de linkedin para saber mas acerca de mi experiencia tanto laboral como académica:
[![LinkedIn](https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg)](https://www.linkedin.com/in/tomas-balladares-813563225/)


# 🚀 Ejercicios

A continuación comenzaré con el desarrollo de los ejercicios del proceso de selección.


## Ejercicio 1
- Instalación del ambiente: con respecto a este ejercicio, no hay mucho que documentar debido a que, es la instalación del IDE (VsCode) y del software de control de versionado (Git). Con respecto a lo mencionado anteriormente, tengo bastante experiencia utilizandolo, ya sea en proyectos personales (PHP, HTML y demás). También, tengo experiencia acádemica ya que se utilizan bastante en las materias relacionadas a la programación.

## Ejercicio 2

> ¿Qué es un servidor HTTP?

    Un servidor HTTP (o web server, en ambitos academicos lo vi de esta manera), es software
    que comprende URLs y HTTP (Protocolo de transferencia de hipertexto) el cual, 
    es utilizado para responder peticiones de los usuarios. También, un servidor web tiene
    muchas partes que controlan cómo los usuarios de la web obtienen acceso a los archivos alojados 
    en el servidor

> ¿Qué son los verbos HTTP? Mencionar los más conocidos

    Los verbos son utilizados para poder hacerle solicitudes HTTP al servidor.
    Los mas conocidos son los siguientes:
        - GET
        - POST
        - DELETE
        - PATCH
        - PUT
        - HEAD

 > ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

    Un request, es la petición del usuario hacia el servidor. (Por ejemplo el usuario
    hace un GET a paginafalsa/autos, para obtener una lista de autos).
    Un response, es aquella respuesta del servidor para el usuario, lo cual, en el ejemplo
    anterior, sería la lista de autos.
    Los headers, son campos adicionales, los cuales sirven para dar mas información acerca de la
    calidad del envío o respuesta y demás.

> ¿Qué es un queryString? (En el contexto de una url)

    Un queryString es una cadena de texto que se agrega a la URL, que contiene parametros
    para que sean utilizados en el servidor web. Ejemplo: Si hacemos un GET
    paginafalsa/autos?id=1 nos devuelve el auto con ID = 1.

> ¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

    El responseCode (o statusCode), son codigos de estado que nos indican el resultado
    de la solicitud HTTP.
    Los posibles valores son:
        - Respuestas informativas (100–199)
        - Respuestas satisfactorias (200–299)
        - Redirecciones (300–399)
        - Errores de los clientes (400–499)
        - Errores de los servidores (500–599) 

> ¿Cómo se envía la data en un Get y cómo en un POST?

    En el GET, se envía data por queryString (EJ: paginafalsa/autos?id=1).

    En el POST, se envía data por el body de la solicitud HTTP, utilizando el formato JSON.
    
    
> ¿Qué verbo http utiliza el navegador cuando accedemos a una página?

    El navegador usa GET para acceder a una página.

> Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de
estructuras posibles.
    
    Explicación:
    
    JSON: Formato lígero de intercambio de datos, tanto para humanos como para máquinas.
    JSON es un tipo de XML, pero es utilizado JSON para el intercambio de datos debido
    a que, a nivel performance es mejor y consume menos banda ancha.
        
        Ejemplo:
        {
        "marca": "Ford"
        "color" : "Verde"
        }

    
    XML:Es un formato de marcado que define reglas para codificar documentos en un formato que es legible tanto para humanos como para máquinas.

    Ejemplo:
    
    {

    <persona>
    <nombre>Juan</nombre>
    <edad>30</edad>
    <ciudad>Madrid</ciudad>
    </persona>
        
    }

> Explicar brevemente el estándar SOAP
 
    Es un protocolo estándar que define cómo dos objetos en diferentes procesos 
    pueden comunicarse por medio de intercambio de datos XML. 

> Explicar brevemente el estándar REST Full

    REST (Representational State Transfer): Es un estilo de arquitectura para
    diseñar servicios web. Los servicios RESTful utilizan HTTP y se basan en 
    recursos, que son identificados por URLs.

> ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

    Headers en un request: Son campos adicionales que se envían junto con la solicitud HTTP, proporcionando
    información sobre la solicitud o el cliente. Pueden incluir detalles como el tipo de contenido, el método de autenticación, la 
    codificación aceptada, etc.

    Content-Type: Es un header que indica el tipo de media del recurso enviado al cliente o del recurso
    esperado del servidor. Por ejemplo, Content-Type: application/json
    indica que el cuerpo de la solicitud o respuesta está en formato JSON.