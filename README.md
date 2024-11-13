# Sistema de Gestión de Casos Fiscales - Frontend para Colmenares & Asociados

Este proyecto corresponde al **Frontend del Sistema de Gestión de Casos Fiscales** desarrollado para [Colmenares & Asociados](https://www.colmenaresasociados.com/), una firma de abogados en Bogotá, Colombia, especializada en Derecho Tributario, Corporativo y otras áreas clave del derecho. El sistema facilita la gestión centralizada de casos fiscales, proporcionando una plataforma intuitiva donde clientes, abogados y administradores pueden gestionar y consultar casos en tiempo real.

**Desarrollador**: Jean Rúa  
**Sitio Web**: [jeanrua.com](https://jeanrua.com)  
**LinkedIn**: [Jean Rúa](https://www.linkedin.com/in/jean-rua/)

---

## 📖 Descripción del Proyecto

El frontend, desarrollado en **Angular**, permite a **Colmenares & Asociados** gestionar y actualizar los detalles de cada caso fiscal mediante tres módulos o secciones dedicadas:

1. **Administrador**: Para la administración de usuarios, permisos y configuración general del sistema.
2. **Abogados**: Un espacio para los abogados de la firma donde pueden revisar, actualizar y gestionar los casos que se encuentran en proceso.
3. **Clientes**: Una sección dedicada para que los clientes suban nuevos casos, consulten el estado de sus procesos y reciban actualizaciones en tiempo real sobre sus casos fiscales.

Este frontend consume las APIs proporcionadas por el backend del sistema, facilitando la comunicación segura entre el cliente y el servidor y asegurando que toda la información esté protegida y accesible.

## 🚀 Características Principales

1. **Módulo de Administración**: Herramientas para gestionar los usuarios, establecer permisos y configurar los aspectos generales del sistema.
2. **Portal de Abogados**: Permite a los abogados gestionar casos en curso, actualizar el estado de los casos, añadir comentarios y ver la documentación.
3. **Portal de Clientes**: Los clientes pueden subir casos, ver actualizaciones en tiempo real, revisar la documentación y comunicarse con el equipo de Colmenares & Asociados.
4. **Autenticación y Seguridad**: Uso de JWT para autenticación segura, asegurando que cada usuario tenga acceso sólo a la información que le corresponde.
5. **Interfaz Intuitiva y Adaptable**: Diseño responsivo y orientado a la facilidad de uso para mejorar la experiencia tanto de clientes como de abogados y administradores.

## 🛠️ Stack Tecnológico

- **Frontend**: Angular
- **Estilo y Diseño**: Bootstrap y SCSS
- **Interacción con el Backend**: Consumo de APIs RESTful desarrolladas en Node.js
- **Autenticación**: JWT para gestionar sesiones y permisos de usuario
- **Control de Versiones**: Git y GitHub

## 📂 Estructura del Proyecto

colmenares-frontend/ │ ├── src/ │ ├── app/ │ │ ├── admin/ # Módulo de Administración │ │ ├── abogados/ # Módulo para Abogados │ │ ├── clientes/ # Módulo para Clientes │ │ ├── services/ # Servicios para APIs y autenticación │ │ ├── guards/ # Guards para protección de rutas │ │ └── shared/ # Componentes y utilidades compartidas │ │ │ ├── assets/ │ ├── environments/ │ └── styles/ │ ├── angular.json ├── package.json └── README.md

 
 

## 🚀 Instalación

1. Clona el repositorio y navega a la carpeta del proyecto:
   ``` 
   git clone https://github.com/jeanrua/colmenares-frontend.git
   cd colmenares-frontend
Instala las dependencias:

 
 
npm install
Configura las variables de entorno en el archivo src/environments/environment.ts.

Inicia el servidor de desarrollo:
 
ng serve
Abre el navegador y navega a http://localhost:4200 para ver la aplicación en funcionamiento.

Desarrollado por Jean Rúa para Colmenares & Asociados. Para más detalles, visita jeanrua.com o conecta en LinkedIn.

Gracias por explorar el Sistema de Gestión de Casos Fiscales 🚀