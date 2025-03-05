
# 🛠️ Manual de Instalación de Entorno de Desarrollo Web

## ✅ Descripción general
Este manual tiene como objetivo guiar paso a paso la instalación de un entorno de desarrollo completo, ideal para computadoras recién formateadas o nuevas. Aquí encontrarás las herramientas necesarias para proyectos frontend, backend, mobile y DevOps, organizadas por etapas y priorizadas según dependencias.

---

## 📑 Índice
1. Dependencias Base
2. IDEs y Editores de Código
3. Frameworks y Librerías Frontend
4. Frameworks y Tecnologías Backend
5. Bases de Datos
6. Cloud y Hosting
7. Herramientas de Desarrollo
8. Mobile
9. Configuración Final
10. Orden de Instalación Recomendado

---

## 1️⃣ Dependencias Base
> Instalación inicial de herramientas fundamentales, necesarias para ejecutar lenguajes, gestores de paquetes y terminales.

- **Git**  
  Control de versiones para gestionar cualquier tipo de proyecto.  
  https://git-scm.com/

- **Python**  
  Desarrollo de scripts, automatización y APIs. Requerido por algunos entornos.  
  https://www.python.org/downloads/

- **Java (JDK/JRE)**  
  Necesario para desarrollo backend con Java y Spring Boot, y para entornos móviles.  
  https://www.oracle.com/java/technologies/downloads/

- **Node.js (con npm)**  
  Ejecuta JavaScript/TypeScript en backend y frontend.  
  https://nodejs.org/

- **Bash/WSL**  
  Consola avanzada para scripts y administración del entorno (Instalado por defecto en Linux/macOS, para Windows usar Git Bash o WSL).

---

## 2️⃣ IDEs y Editores de Código
> Aplicaciones donde desarrollarás tus proyectos según el lenguaje y tecnología.

- **Visual Studio Code**  
  Ideal para proyectos web fullstack, backend con Node/Nest y frontend con Angular/React.  
  https://code.visualstudio.com/

- **Para JAVA:** 
  - **IntelliJ IDEA**  
    Recomendado para backend con Java, Spring Boot y Hibernate.  
    https://www.jetbrains.com/idea/
  
  - **Eclipse IDE**  
    Alternativa para desarrollo en Java y Spring Boot.  
    https://www.eclipse.org/downloads/
  
  - **Spring Tool Suite (STS)**  
    Optimizado para proyectos Spring Boot.  
    https://spring.io/tools

- **Visual Studio**  
  Desarrollo de aplicaciones en C# y .NET.  
  https://visualstudio.microsoft.com/

- **Android Studio**  
  Entorno para desarrollo móvil con Flutter y React Native.  
  https://developer.android.com/studio

---

## 3️⃣ Frameworks y Librerías Frontend
> Herramientas para desarrollar interfaces de usuario y experiencias web.

- **Angular CLI** – SPA escalables.  
  `npm install -g @angular/cli`

- **React y Next.js** – Aplicaciones interactivas y SSR.  
Se instalan por proyecto:
```bash
npx create-react-app my-app
npx create-next-app my-app
```

- **Redux** – Gestión global del estado en aplicaciones React.  
`npm install redux react-redux`

- **Bootstrap / TailwindCSS / Materialize** – Frameworks de diseño responsivo.

- **Sass** – Preprocesador CSS.  
`npm install -g sass`

- **Flutter** – Desarrollo de interfaces móviles y web.  
[https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)

---

## 4️⃣ Frameworks y Tecnologías Backend
> Para la lógica del servidor, APIs y servicios.

- **Express.js** – Framework minimalista para APIs REST con Node.js.
`npm install express`

- **NestJS** – Backend modular y escalable con TypeScript.
`npm install -g @nestjs/cli`

- **Spring Boot** – Backend empresarial con Java.
[https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot)

- **Hibernate** – ORM para Java.
Dependiendo del proyecto Maven/Gradle.

- **.NET (C#)** – Desarrollo de APIs, aplicaciones web y desktop con Visual Studio.
Con Visual Studio, instalar carga de trabajo “Desarrollo de ASP.NET”.

---

## 5️⃣ Bases de Datos
> Sistemas para almacenar y consultar información.

- **PostgreSQL** – Base de datos relacional potente.  
[https://www.postgresql.org/download/](https://www.postgresql.org/download/)

- **MongoDB** – Base de datos NoSQL para proyectos flexibles.  
[https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)

- **Firebase** – Backend as a Service con autenticación y base de datos en tiempo real.  
[https://firebase.google.com/](https://firebase.google.com/)

---

## 6️⃣ Cloud y Hosting
> Plataformas para desplegar tus proyectos online.

- **AWS CLI**
[https://aws.amazon.com/cli/](https://aws.amazon.com/cli/)

- **Google Cloud SDK**
[https://cloud.google.com/sdk/docs/install](https://cloud.google.com/sdk/docs/install)

- **Firebase CLI**
`npm install -g firebase-tools`

- **Heroku CLI**
[https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli)

- **Vercel CLI**
`npm install -g vercel`

- **Cloudflare**
[https://dash.cloudflare.com/](https://dash.cloudflare.com/)

---

## 7️⃣ Herramientas de Desarrollo
> Utilidades para trabajar APIs, contenedores y diseño.

- **Docker**
[https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

- **Kubernetes (kubectl)**
[https://kubernetes.io/docs/tasks/tools/](https://kubernetes.io/docs/tasks/tools/)

- **Postman**
[https://www.postman.com/downloads/](https://www.postman.com/downloads/)

- **Figma**
[https://www.figma.com/](https://www.figma.com/)

- **Webpack**
`npm install --save-dev webpack webpack-cli`

---

## 8️⃣ Mobile
> Tecnologías para aplicaciones móviles.

- **Flutter** (ya mencionado)
[https://docs.flutter.dev/get-started/install](https://docs.flutter.dev/get-started/install)

- **React Native**
```bash
npm install -g react-native-cli
```

- **Android Studio**(para emuladores y build tools - ya mencionado)

---

## 9️⃣ Configuración Final
> Ajustes necesarios para el correcto funcionamiento del entorno.

- Configurar variables de entorno (**JAVA_HOME**, **ANDROID_HOME**, etc.).
- Configurar Git con usuario y correo.
- Verificar instalación con comandos (`node -v`, `java -version`, etc.).
- Crear carpeta para proyectos (`C:\Projects` o `~/Projects`).

---

## 🔄 Orden de Instalación Recomendado:
1. Dependencias Base
2. IDEs y Editores de Código
3. Frameworks y Librerías
4. Herramientas de Desarrollo
5. Bases de Datos
6. Cloud y Hosting
7. Mobile
8. Configuración Final
