# 📚 LibroCloud

Sistema full stack de gestión de venta de libros con autenticación, roles de usuario y control de inventario.

---

## 🚀 Demo

-- Backend API: https://libroclouds.onrender.com/  
-- Frontend: https://portfolio-10926.web.app/

---

## 🧱 Tecnologías

## Backend
-- Java 21  
-- Spring Boot 3  
-- Spring Security + JWT  
-- BCrypt  
-- Spring Data JPA  
-- MySQL  
-- Maven  

## Frontend
-- React  
-- JavaScript  
-- HTML5  
-- CSS3  
-- Bootstrap  

## Deploy
-- Render (backend)  
-- Firebase Hosting (frontend)  

---

## 🔐 Acceso de administrador (demo)

⚠️ Solo para pruebas del sistema

-- Email: admin@ventaslibros.com  
-- Password: Admin12345  

---

## ⚙️ Funcionalidades

## 📘 Gestión de libros
-- Crear, listar, actualizar y eliminar libros  
-- Eliminación lógica (soft delete)  
-- Validación de ISBN único  
-- Validación de stock no negativo  

## 🗂 Categorías
-- Gestión de categorías de libros  
-- Validación de categorías activas  

## 👤 Clientes
-- Registro de clientes  
-- Consulta de clientes  

## 💰 Ventas
-- Registro de ventas  
-- Descuento automático de stock  
-- Anulación de ventas con restauración de stock  

---

## 🔐 Seguridad

-- Autenticación con JWT  
-- Encriptación de contraseñas con BCrypt  
-- Control de acceso por roles (admin / usuario)  

---

## 🧠 Reglas de negocio

-- Un libro no puede tener ISBN duplicado  
-- No se permite stock negativo  
-- Las ventas afectan el stock automáticamente  
-- Las ventas anuladas restauran el stock  
-- Eliminación lógica de libros (no borrado físico)  

---

## 🧩 Arquitectura

-- API REST separada del frontend  
-- Comunicación mediante HTTP/JSON  
-- Backend desplegado en cloud (Render)  
-- Frontend independiente en Firebase Hosting  


## 📱 Flujo del sistema

-- El usuario accede al frontend  
-- Se conecta a la API REST  
-- Autenticación mediante JWT  
-- Gestión de libros, ventas y clientes según rol  

---

## 🧪 Notas

-- El backend puede tardar unos segundos en iniciar (Render free tier)  
-- El sistema está en entorno de demostración  

