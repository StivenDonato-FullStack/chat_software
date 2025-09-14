# 💬 Proyecto Full Stack Chat App – Caso de Estudio Profesional

## 📌 Introducción

Este proyecto fue desarrollado como un **ejercicio práctico de integración full stack**, con el objetivo de construir una aplicación de chat en tiempo real utilizando **React en el frontend**, **Node.js/Express en el backend** y la API de **Stream Chat**.  

El proceso me permitió trabajar en:
- Configuración de servidor y cliente.
- Manejo de autenticación con cookies y tokens.
- Creación de usuarios y login con contraseñas seguras (bcrypt).
- Corrección de errores comunes en proyectos reales (mismatch de tokens, problemas de importación, ESLint, etc.).
- Buenas prácticas de documentación y despliegue.

---

## 🎯 Objetivos del Proyecto

- Implementar un **chat en tiempo real** con canales y mensajes instantáneos.  
- Crear un **backend seguro** con registro e inicio de sesión.  
- Integrar la librería **stream-chat-react** para aprovechar componentes listos y responsivos.  
- Resolver errores de compatibilidad, imports y autenticación.  
- Documentar todo el proceso como parte de mi portafolio.

---

## 🛠️ Desarrollo y Aprendizajes

### 🔧 Backend
- Configuración de **Express** para exponer endpoints `/auth/signup` y `/auth/login`.
- Uso de **bcrypt** para hashear contraseñas antes de guardarlas en Stream Chat.
- Generación de IDs únicos con **crypto**.
- Integración con **Stream Chat Server SDK**:
  - Creación de tokens con `createToken(userId)`.
  - Creación y consulta de usuarios con `upsertUser` y `queryUsers`.

 ---

### ⚛️ Frontend
- Creación de aplicación con **React**.
- Manejo de sesiones con **universal-cookie** (guardar token, userId, username).
- Integración de `stream-chat-react` para renderizar:
  - Lista de canales.
  - Contenedor de chat.
  - Autenticación personalizada.
- Importación de estilos modernos con:
  ```js
  import 'stream-chat-react/css/v2/index.css';

  ---

📈 Conclusiones

El proyecto me permitió reforzar conceptos clave de autenticación, manejo de sesiones y integración de librerías externas.

Aprendí a leer logs de error, interpretar warnings de ESLint y a aplicar buenas prácticas en naming y consistencia de datos.

Se logró un flujo completo: signup ➝ login ➝ conexión al chat ➝ mensajería en vivo.

---

🌐 Conéctate conmigo

👨‍💻 Autor: Stiven Donato – Full Stack Developer

💼 LinkedIn: www.linkedin.com/in/huber-stiven-donato-bohorquez

🐙 GitHub: StivenDonato-FullStack

📧 Email: huberdonato22@gmail.com
