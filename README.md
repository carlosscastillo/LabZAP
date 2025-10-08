# LabZAP
LabZAP - Laboratorio de Seguridad Web
Repositorio para una práctica de seguridad que consiste en escanear una aplicación web vulnerable utilizando OWASP ZAP.
La aplicación está construida con Node.js, Express y SQLite, y contiene vulnerabilidades intencionales de Inyección SQL y Cross-Site Scripting (XSS) para fines educativos.


Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente en tu sistema:

Node.js (versión 14 o superior)

npm (Normalmente se instala junto con Node.js)

Instrucciones de Ejecución

Sigue estos pasos para poner en marcha la aplicación en tu máquina local.

1. Clonar el Repositorio (Opcional)
Si estás descargando el proyecto, clónalo en tu máquina.
git clone https://github.com/carlosscastillo/LabZAP.git
cd zap-lab


2. Instalar Dependencias
Abre una terminal en la carpeta raíz del proyecto y ejecuta el siguiente comando para instalar todas las librerías necesarias (express, helmet, ejs, etc.).
npm install


3. Iniciar la Aplicación
Una vez que las dependencias se hayan instalado, inicia el servidor con el siguiente comando:
node app.js


4. Acceder a la Aplicación
Si todo ha ido bien, verás un mensaje en la terminal indicando que el servidor está en funcionamiento:
App en http://localhost:3000


Ahora puedes abrir tu navegador web y visitar http://localhost:3000 para interactuar con la aplicación vulnerable y comenzar tu escaneo con ZAP.
