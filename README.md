# 🍔 PizzaMia - Frontend

Este repositorio contiene el **frontend** de **PizzaMia**, una plataforma web de pedidos y gestión para un local de comida rápida. Está dividido en dos aplicaciones:

- 🧑‍💻 cliente/ – Aplicación para el **usuario final** (clientes)
- 🛠️ admin/ – Aplicación para el **personal interno** (administradores, empleados, cocineros, repartidores)

Ambas aplicaciones se comunican con un backend común desarrollado en Java + Spring Boot.

---
## 📦 Tecnologías utilizadas

### Admin

- React + Vite
- TypeScript
- Zustand
- React Router DOM
- Axios
- WebSockets
- Cloudinary

### Cliente

- React + Vite
- TypeScript
- Zustand
- Axios
- MercadoPago SDK
- Cloudinary

---

## Instalación

###  1. Clonar el repositorio

```bash
git clone https://github.com/GeronimoCrescitelli/PizzaMia-Front
cd PizzaMia-Front
```

### 2. Ejecutar Frontend Admin

```bash
cd admin
```

- Instrucciones en el archivo admin/README.md para instalar dependencias y levantar el panel de administración.

### 3. Ejecutar Frontend Cliente (En una terminal paralela)

```bash
cd cliente
```

- Instrucciones en el Seguí las instrucciones del archivo cliente/README.md para instalar dependencias y levantar el servidor.

---

## 📌 Requisitos

- Node.js 18 o superior
- Backend en funcionamiento en: http://localhost:8080
- Variables de entorno configuradas con la siguiente estructura dentro del cliente, como archivo `.env`: 

```
VITE_AUTH0_DOMAIN=ejemplo
VITE_AUTH0_CLIENT_ID=example
VITE_AUTH0_CALLBACK_URL=http://localhost:5173/callback
VITE_AUTH0_AUDIENCE=https://pruebaApi
VITE_API_SERVER_URL=http://localhost:8080
```

## Integrantes
Castillo, Franco
Chavez, Lucas
Crescitelli, Geronimo
Rezinovsky, Matias
Silva, Nicolas
