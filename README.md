# 🏢 Sistema de Gestión de Clientes Empresariales - API CRM

![Diagrama de la Base de Datos](https://i.imgur.com/hB5WPDD.png)

## 📘 Descripción

El *Sistema de Gestión de Clientes Empresariales (CRM API)* es una solución backend desarrollada con *Node.js, TypeScript y Prisma, orientada a automatizar y optimizar la administración de relaciones con clientes, tareas, oportunidades, contactos y más. Este sistema expone una **API RESTful segura, documentada con **Swagger, y con validaciones robustas implementadas mediante **Joi*.

El objetivo principal es permitir a las empresas llevar el control integral de sus clientes corporativos y los procesos comerciales asociados de manera eficiente y escalable.

---

## 🎉 Principales Características

### 🏢 Módulos del Sistema CRM

* ✅ CRUD completo para los siguientes módulos:

  * *Tipo de Documento*
  * *Usuario*
  * *Cliente*
  * *Contacto*
  * *Interacción*
  * *Oportunidad*
  * *Tarea*

* 🔐 Módulo usuariojwt:

  * Registro de usuario (/auth/register)
  * Inicio de sesión (/auth/login)
  * Eliminación lógica (campo estado_auditoria)

* ✅ Autenticación con *JWT*

* 🧪 Validaciones con *Joi*

* 🗒 Documentación con *Swagger*

* 🛡 Seguridad con express, cors, y control de IP

* 📦 ORM: *Prisma*

* 🗄 Base de Datos: *PostgreSQL*

---

## 🛠 Tecnologías Utilizadas

| Tecnología | Descripción                                         |
| ---------- | --------------------------------------------------- |
| Node.js    | Entorno de ejecución JavaScript en servidor         |
| TypeScript | Superset de JavaScript con tipado estático          |
| Express    | Framework minimalista para crear APIs REST          |
| Prisma     | ORM moderno y tipado para trabajar con PostgreSQL   |
| PostgreSQL | Sistema de gestión de bases de datos relacional     |
| JWT        | Mecanismo seguro de autenticación por tokens        |
| Swagger    | Documentación interactiva de la API                 |
| Joi        | Librería para validación de datos                   |
| CORS       | Middleware para habilitar peticiones entre dominios |
| Dotenv     | Manejo de variables de entorno                      |

---

## 📂 Instalación del Proyecto

1. Clonar el repositorio:

bash
git clone https://github.com/CarlosRuiz2025/gestion-clientes-crm.git
cd gestion-clientes-crm


2. Instalar dependencias:

bash
npm install


3. Crear y configurar el archivo .env:

env
DATABASE_URL=postgresql://postgres:tu_contraseña@localhost:5432/BdCRM
PORT=3000
JWT_SECRET=clave_super_secreta


4. Ejecutar las migraciones de la base de datos:

bash
npx prisma migrate dev


---

## 🔧 Scripts para Desarrollo

* Levantar el servidor backend:

bash
npm run dev


* Ver la documentación Swagger:


http://localhost:3000/api/CRM/api-docs


---

## 🧪 Configuración de Base de Datos

1. Asegúrate de que PostgreSQL esté en ejecución.
2. Crea una base de datos llamada BdCRM.
3. Ajusta las credenciales en el .env.

---

## 📀 Estructura del Proyecto


src/
├── controllers/
├── routes/
├── services/
├── models/
├── middlewares/
├── prisma/
├── docs/ (Swagger)
├── auth/
└── ...


---

## 💼 Curso

*Taller de Programación Web*

## 👨‍🎓 Docente

*Diego Fernando Baes Vásquez*

---

## 👥 Integrantes

* Carlos Andrés Ruiz Miranda
* Eber Anderson Cárdenas Ramírez
* Juan Dennis Herrera Lurita
* Mendieta Jimene Jeremy Aldair
* Aurora Isabel Matta Collantes
* Giomar Alexander Osorio Tapia

---

## ✨ Proyecto en desarrollo con entusiasmo y compromiso profesional 
