# smart_wardrobe_api
Backend en Kotlin (Ktor) del curso “Desarrollo Full Stack con Kotlin: API, Mongo e IA Aplicada”.

# smart_wardrobe_api

Backend desarrollado en **Kotlin + Ktor** para el curso:

**Desarrollo Full Stack con Kotlin: API, Mongo e IA Aplicada**

---

## 📌 Descripción

`smart_wardrobe_api` es el servicio backend encargado de:

- Gestionar prendas (garments)
- Procesar imágenes
- Integrarse con OpenAI para extracción de atributos
- Persistir datos en MongoDB Atlas
- Generar sugerencias de outfit mediante un sistema de ranking determinístico

Este proyecto forma parte de una arquitectura full stack compuesta por:

- 📱 App móvil Android (Kotlin nativo)
- ⚙️ API backend (Ktor)
- 🗄️ Base de datos MongoDB Atlas
- 🤖 Integración con OpenAI

---

## 🧱 Stack Tecnológico

- Kotlin
- Ktor (Netty)
- MongoDB Atlas
- KMongo / MongoDB Driver
- kotlinx.serialization
- Docker (para despliegue)

---

## 🏗️ Arquitectura

Estructura base del proyecto:

```
src/main/kotlin/
 ├── routes/
 ├── services/
 ├── repositories/
 ├── models/
 └── config/
```

Separación de responsabilidades:

- **routes** → definición de endpoints
- **services** → lógica de negocio
- **repositories** → acceso a datos
- **models** → data classes
- **config** → configuración y variables de entorno

---

## 🚀 Cómo ejecutar el proyecto

### 1️⃣ Requisitos

- JDK 17+
- Gradle
- MongoDB Atlas (connection string)

### 2️⃣ Ejecutar localmente

```bash
./gradlew run
```

El servidor iniciará en:

```
http://localhost:8080
```

---

## 📚 Objetivo Académico

Este repositorio será construido progresivamente durante el curso, incorporando:

- CRUD completo de garments
- Integración con OpenAI
- Sistema de recomendación con scoring
- Dockerización
- Despliegue en cloud

Cada commit representa una etapa de evolución del backend.

---

## 📄 Licencia

Uso académico.