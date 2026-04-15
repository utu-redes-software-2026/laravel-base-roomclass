# Programación Avanzada (PHP)

Carrera: Redes y Software  
Docente: Martin Roman  

---

## 🎯 Objetivo del curso

Desarrollar una aplicación web completa utilizando Laravel, aplicando arquitectura MVC, base de datos, formularios, autenticación y buenas prácticas.

---

## ⚙️ Requisitos

- PHP 8+
- Composer
- MySQL
- Git

---

## 🚀 Instalación

Clonar repositorio:

git clone URL

Entrar a la carpeta:

cd proyecto

Instalar dependencias:

composer install

Configurar entorno:

cp .env.example .env

Generar key:

php artisan key:generate

Ejecutar servidor:

php artisan serve

---

## 📌 Forma de trabajo

- Cada estudiante trabaja en su repositorio individual
- Se evaluará el progreso mediante commits
- Se debe trabajar clase a clase

---

## 📊 Evaluación

- Funcionamiento del sistema
- Uso de MVC
- Base de datos
- Seguridad
- Commits (cantidad y calidad)

---

# 📚 PLAN DE TRABAJO POR CLASES

---

## 🧩 Clase 1 – Instalación y estructura

### Objetivo
Comprender qué es Laravel y su estructura.

### Tareas

- Instalar proyecto Laravel
- Ejecutar el servidor
- Explorar carpetas principales

### Commit esperado
"Clase 1 - instalación y primer proyecto funcionando"

---

## 🧩 Clase 2 – Rutas

### Objetivo
Comprender el manejo de rutas.

### Tareas

- Crear rutas:
  - /inicio
  - /saludo/{nombre}
  - /suma/{a}/{b}

### Commit esperado
"Clase 2 - rutas básicas y parámetros"

---

## 🧩 Clase 3 – Controladores

### Objetivo
Separar lógica en controladores.

### Tareas

- Crear controlador EventoController
- Crear rutas usando controlador
- Crear páginas:
  - /eventos
  - /contacto

### Commit esperado
"Clase 3 - uso de controladores"

---

## 🧩 Clase 4 – Vistas (Blade)

### Objetivo
Mostrar contenido dinámico.

### Tareas

- Crear vistas:
  - inicio.blade.php
  - eventos.blade.php
- Enviar datos desde controlador

### Commit esperado
"Clase 4 - vistas blade"

---

## 🧩 Clase 5 – CRUD básico

### Objetivo
Implementar CRUD sin base de datos.

### Tareas

- Crear ProductoController
- Listar productos (array)
- Crear formulario

### Commit esperado
"Clase 5 - CRUD básico sin BD"

---

## 🧩 Clase 6 – Base de datos

### Objetivo
Trabajar con persistencia.

### Tareas

- Crear migración productos
- Ejecutar migrate
- Conectar modelo

### Commit esperado
"Clase 6 - base de datos y migraciones"

---

## 🧩 Clase 7 – CRUD completo

### Objetivo
CRUD con base de datos.

### Tareas

- Crear productos
- Editar productos
- Eliminar productos

### Commit esperado
"Clase 7 - CRUD completo con BD"

---

## 🧩 Clase 8 – Formularios y validación

### Objetivo
Validar datos del usuario.

### Tareas

- Validar campos:
  - nombre obligatorio
  - precio numérico

### Commit esperado
"Clase 8 - validaciones"

---

## 🧩 Clase 9 – Relaciones

### Objetivo
Relacionar modelos.

### Tareas

- Crear relación Usuario → Productos

### Commit esperado
"Clase 9 - relaciones ORM"

---

## 🧩 Clase 10 – Autenticación

### Objetivo
Sistema de login.

### Tareas

- Instalar auth (Breeze)
- Proteger rutas

### Commit esperado
"Clase 10 - autenticación"

---

## 🧩 Clase 11 – Seguridad

### Objetivo
Buenas prácticas.

### Tareas

- Uso de CSRF
- Protección de formularios

### Commit esperado
"Clase 11 - seguridad"

---

## 🧩 Clase 12 – API

### Objetivo
Crear endpoints.

### Tareas

- Crear ruta API
- Devolver JSON

### Commit esperado
"Clase 12 - API REST"

---

## 🧩 Clase 13 – Git

### Objetivo
Trabajo colaborativo.

### Tareas

- Uso de ramas
- Pull requests

### Commit esperado
"Clase 13 - uso de Git"

---

## 🧩 Clase 14 – Deploy

### Objetivo
Publicar proyecto.

### Tareas

- Subir a servidor
- Configurar entorno

### Commit esperado
"Clase 14 - deploy"

---

## 🧩 Clase 15 – Proyecto final

### Objetivo
Integrar todo.

### Tareas

- Aplicación completa funcionando

### Commit esperado
"Entrega final"

---

## ⚠️ Reglas importantes

- No copiar código
- Trabajar clase a clase
- Hacer commits frecuentes
- Probar antes de subir

---

## 💡 Recomendación

Si algo no funciona:
- Revisar errores
- Consultar documentación
- Preguntar en clase

---
