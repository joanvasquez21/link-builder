## linkbuilder
### Descripción
LinkBuilder es una aplicación web que permite a los usuarios crear, gestionar y buscar enlaces personalizados de manera dinámica. Cada enlace puede tener un nombre, un ícono representativo y una URL válida, integrándose automáticamente en el sistema de búsqueda.
### Instalación
1. Clonar el repositorio
```
git clone https://github.com/joanvasquez21/link-builder.git
cd link-builder
```
2. Configurar el frontend
```
cd search-angular/my-search-app
npm install
ng serve
```
Accede a http://localhost:4200/ en tu navegador.
3. Configurar el Backend (Spring Boot)
```
cd ../../search-backend/search-backend
mvn clean install
mvn spring-boot:run
```
### Tecnologías usadas

Frontend: Angular, TypeScript, Bootstrap

Backend: Spring Boot, Java, Maven

Base de Datos: MySQL

ORM: Hibernate / JPA
Contribuir

### Si deseas contribuir al proyecto, sigue estos pasos:

. Fork el repositorio

. Crea una rama con tu feature (git checkout -b feature-nueva)

. Realiza tus cambios y haz commit (git commit -m "feat: descripción del cambio")

. Sube los cambios (git push origin feature-nueva)
