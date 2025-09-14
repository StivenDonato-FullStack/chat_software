# 💬 Full Stack Chat App con React + Node.js + Stream Chat

![Banner](https://user-images.githubusercontent.com/placeholder/banner-chat.png)

Aplicación **de mensajería en tiempo real** que integra **frontend en React** y **backend en Node.js/Express** con la API de **Stream Chat**.  
Incluye registro de usuarios, login seguro con contraseñas encriptadas, persistencia con cookies, y un sistema de canales en vivo similar a Slack o Discord.  

✨ **Lo más cool**: notificaciones en vivo, conexión instantánea con usuarios y un diseño moderno gracias a `stream-chat-react`.

---

## 📑 Tabla de Contenidos

1. [🚀 Tecnologías](#-tecnologías)
2. [📂 Estructura](#-estructura-del-proyecto)
3. [⚙️ Configuración](#️-configuración)
4. [▶️ Ejecución](#️-ejecución-en-desarrollo)
5. [🔑 Flujo de Autenticación](#-flujo-de-autenticación)
6. [🐞 Problemas Comunes Resueltos](#-problemas-comunes-resueltos)
7. [🎬 Vista Previa en Acción](#-vista-previa-en-acción)
8. [👨‍💻 Autor](#-autor)

---

## 🚀 Tecnologías

### 🔧 Backend
- Node.js + Express ⚡
- `stream-chat` (SDK server)
- `bcrypt` para encriptar contraseñas
- `crypto` para generar IDs únicos
- `dotenv` para manejar variables de entorno

### 🎨 Frontend
- React 18 ⚛️
- `stream-chat-react` (componentes preconstruidos)
- `universal-cookie` 🍪 para manejo de sesiones
- `axios` para peticiones HTTP
- Estilos importados:  
  ```js
  import 'stream-chat-react/css/v2/index.css';
