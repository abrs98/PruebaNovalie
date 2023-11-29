# PruebaReact
Pasos para ejecutar los programas:

1. Abrir una nueva terminal en Visual Studio Code.
2. Situarse desde la terminal en la carpeta "api-rest-backend".
3. Ejecutar el comando "node service.js" para inicializar el servicio.
4. Abrir una nueva terminal en Visual Studio Code.
5. Situarse desde la terminal en la carpeta "frontend".
6. Ejecutar el comando "npm install" para instalar las dependencias de React.
7. Ejecutar el comando "npm run dev" para inicializar la aplicación de React.

Descripción:

Ésta aplicación consiste en la implementación de la arquitectura cliente-servidor en un sistema.

Servidor (Backend).

 Mediante un servcio api-rest(backend) se expone un catálogo de cobros de primas. Un cobro de prima es un objeto que contiene la información básica de una prima, por ejemplo, el monto, el cliente al que se le fía, la moneda en la que se le cobra, entre otros datos. El catálogo de cobros de primas es un objeto que contiene una lista de cobros de primas y la lógica para hacer los cálculos de toda la información necesaria que se demanda desde el cliente, como por ejemplo, el total que se debe cobrar en dólares, ó el porcentage de las primas vencidas, sólo por mencionar algunas funciones.

Cliente (Frontend).

 La aplicación que consume las apis del servicio api-rest  está construida en ReactJS y utliza Vite que es una herramienta que preconfigura un óptimo ambiente de desarrollo. Consta de un componente principal que funge como un dashboard, y que a su vez contiene dos tipos de componentes hijos. Una tabla, que carga los datos de los filtros de selección y tres tarjetas de información que contienen el resumen de los cobros en sus tres distintas monedas. 



Version de NodeJS : 20.9.0
