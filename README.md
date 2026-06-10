# 🕊️ Programadores para la Paz - Isabella López

Repositorio de actividades prácticas y desarrollo del programa **Programadores para la Paz**. Todo el código ha sido gestionado mediante control de versiones y estructurado por semanas, integrando conceptos de terminal, Git, Node.js, Express, APIs, JSON y comunicación digital responsable.

---

## 🛠️ Herramientas y Comandos Dominados

Durante el desarrollo del programa se han utilizado diferentes herramientas y comandos para crear, organizar, ejecutar y publicar los proyectos.

* **Navegación por Terminal:** Uso de la consola para moverse entre directorios (`cd`), listar archivos (`ls`), crear carpetas (`mkdir`), crear archivos (`touch`) y eliminar elementos cuando es necesario (`rm`).
* **Control de Versiones con Git:** Registro y publicación de cambios mediante comandos como:

  * `git status`
  * `git add .`
  * `git commit -m ""`
  * `git push`
* **GitHub Codespaces:** Entorno de trabajo en la nube utilizado para desarrollar, probar y subir las actividades al repositorio.
* **Node.js y npm:** Uso de Node.js para ejecutar JavaScript en el servidor y npm para inicializar proyectos e instalar dependencias.
* **Express:** Framework utilizado para construir servidores, crear rutas y procesar información enviada por los usuarios.
* **JSON:** Formato utilizado para organizar e intercambiar datos entre cliente y servidor.

---

## 📁 Estructura del repositorio

El repositorio está organizado por semanas, de acuerdo con las actividades prácticas desarrolladas en el programa:

* `Semana 1`
* `Semana 2`
* `Semana 3`
* `Semana 4`
* `Semana 5`
* `Semana 6`

Cada carpeta contiene los archivos correspondientes a las actividades solicitadas.

---

## 🚀 Proyecto Desarrollado: Semana 4 - Backend Básico

En la Semana 4 se trabajó la estructura inicial de un servidor backend utilizando Node.js.

### Archivos principales

* **`Semana 4/server.js`:** Servidor base configurado con JavaScript y Node.js, escuchando peticiones en el puerto 3000.
* **`Semana 4/package.json`:** Archivo de configuración inicial del proyecto y sus dependencias.

Esta semana permitió comprender cómo se ejecuta un servidor básico y cómo Node.js puede utilizarse para crear aplicaciones del lado del servidor.

---

## ⚡ Proyecto Desarrollado: Semana 5 - Servidor con Múltiples Rutas

En la Semana 5 se avanzó en la construcción del backend, escalando el servidor inicial para gestionar diferentes puntos de acceso y procesar datos entrantes. El proyecto está ubicado en la carpeta `Semana 5`.

### Archivos creados

* **`server.js`:** Servidor HTTP desarrollado con Express que implementa múltiples rutas de acceso. Incluye rutas `GET` para consultar información estructurada y rutas `POST` para recibir y procesar datos de formularios.
* **`package.json` y `package-lock.json`:** Configuración del entorno de Node.js y registro de la instalación de Express como dependencia del proyecto.
* **`.gitignore`:** Archivo de exclusión utilizado para evitar que la carpeta `node_modules/` sea cargada a GitHub.
* **`conceptos-api.txt` y `pruebas.txt`:** Documentación técnica con respuestas del cuestionario y registro de pruebas de las rutas implementadas.
* **`reflexion-semana5.txt`:** Reflexión sobre el impacto de las APIs en la organización, claridad y transmisión responsable de la información comunitaria.

Esta actividad permitió comprender la importancia de organizar rutas, manejar información enviada por los usuarios y relacionar la tecnología con necesidades de comunicación comunitaria.

---

## 🌐 Proyecto Desarrollado: Semana 6 - JSON, req.body y Peticiones POST

En la Semana 6 se trabajó el uso de **JSON**, **Express**, **req.body** y peticiones **POST** para recibir información enviada por los usuarios desde un cliente hacia el servidor. El proyecto está ubicado en la carpeta `Semana 6`.

### Archivos creados

* **`server.js`:** Servidor desarrollado con Express. Incluye la configuración `express.json()` para leer datos enviados en formato JSON y dos rutas principales:

  * **`POST /registro`:** Recibe un nombre y un mensaje enviados por el usuario.
  * **`POST /incidencia`:** Simula el registro de una incidencia comunitaria mediante el envío de un tipo y una descripción.
* **`preguntas-semana6.txt`:** Archivo con las respuestas de selección múltiple sobre JSON, Express, `express.json()` y `req.body`.
* **`prueba-api.txt`:** Explicación de la prueba realizada a la ruta `/registro`, incluyendo el JSON enviado y la respuesta generada por el servidor.
* **`ejemplo-incidencia.txt`:** Ejemplo de JSON que podría enviar un ciudadano para reportar una incidencia comunitaria.
* **`reflexion-semana6.txt`:** Reflexión sobre la importancia de recibir reportes ciudadanos de forma estructurada para mejorar la organización, la claridad y el seguimiento de la información.
* **`package.json` y `package-lock.json`:** Archivos de configuración del proyecto y dependencias instaladas.

### Rutas implementadas

#### Ruta `/registro`

Permite recibir información básica enviada por el usuario:

```json
{
  "nombre": "Maria",
  "mensaje": "Hola comunidad"
}
```

Respuesta esperada del servidor:

```json
{
  "estado": "Datos recibidos",
  "nombre": "Maria",
  "mensaje": "Hola comunidad"
}
```

#### Ruta `/incidencia`

Permite simular el reporte de una incidencia comunitaria:

```json
{
  "tipo": "Iluminación pública",
  "descripcion": "La comunidad reporta que una lámpara del parque no funciona desde hace varios días."
}
```

Respuesta esperada del servidor:

```json
{
  "mensaje": "Incidencia registrada",
  "tipo": "Iluminación pública",
  "descripcion": "La comunidad reporta que una lámpara del parque no funciona desde hace varios días."
}
```

Esta semana permitió comprender cómo una plataforma puede recibir datos enviados por la ciudadanía, procesarlos de manera organizada y responder con información clara. Además, se relacionó la programación con la participación comunitaria, la documentación de reportes y el uso responsable de la información.

---

## 🧩 Aprendizajes principales

A lo largo de las actividades se fortalecieron los siguientes aprendizajes:

* Crear y organizar carpetas y archivos desde la terminal.
* Usar Git y GitHub para guardar evidencia del proceso.
* Ejecutar proyectos con Node.js.
* Instalar y utilizar Express.
* Crear rutas básicas en un servidor.
* Diferenciar entre peticiones `GET` y `POST`.
* Utilizar JSON como formato de intercambio de datos.
* Comprender el uso de `req.body` para recibir información enviada por el usuario.
* Relacionar la tecnología con la comunicación clara, segura y responsable.
* Reconocer la importancia de estructurar la información para fortalecer la participación ciudadana.

---

## ✅ Estado del proyecto

El repositorio contiene las actividades desarrolladas y organizadas por semanas. Cada carpeta evidencia el avance práctico en programación, construcción de servidores, manejo de rutas, uso de JSON y aplicación de herramientas digitales para fortalecer procesos comunitarios.

---
