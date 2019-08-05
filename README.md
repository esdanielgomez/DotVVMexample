# Códigos de ejemplo del Framework DotVVM con ASP.NET en .NET Core 

Para el desarrollo de aplicaciones web empleando el Framework DotVVM se puede emplear Visual Studio 2019, con la version Community sera suficiente:

https://visualstudio.microsoft.com/es/downloads/

## Modelo Vista Vista Modelo (VMMV)

<img src="https://shirivo.files.wordpress.com/2015/06/mvvm.png">

Model: El modelo, dentro de MVVM es el encargado de representar el modelo del negocio, proveyendo de esta manera la base necesaria para la manipulación de los datos de la aplicación.

View: La vista es la parte encargada de la parte visual de nuestra aplicación.

ViewModel: El ViewModel (modelo de vista en español) es el encargado de ser la capa intermedia entre el modelo y la vista, procesando todas las peticiones que tenga la vista hacia el modelo, además de tener que ocuparse de manejar las reglas del negocio, la comunicación con aplicaciones externas o consumir datos desde alguna fuente (Bases de Datos, Web Services, Sensores, etc.).

## Instalacion de .NET Core

Con .NET Core podemos trabajar de forma multiplatadorma a traves de Windows, Linux, macOS y a traves de Microsoft Azure tambien. Para ello es necesario instalar .NET Core, en este caso los ejemplos se encuentran sobre la version 2.2:

https://dotnet.microsoft.com/download/visual-studio-sdks

Importante: es necesario tener en cuenta la arquitectura del computador para la instalacion de .NET Core: x86 o x64. 

## Complemento de DotVVM para Visual Studio 2019

Para crear un proyecto de DotVVM es necesario instalar el complemento para la creacion del proyecto dentro de Visual Studio: 

https://www.dotvvm.com/landing/dotvvm-for-visual-studio-extension

## Autor

Daniel Gomez Jaramillo.

daniel.gomez@studentpartner.com
