# 🐕 DogApp - Administrador de Citas Veterinarias

Una aplicación Android para gestionar citas veterinarias con autenticación biométrica y integración con APIs externas.

## 📱 Características Principales

- **Autenticación Biométrica**: Login seguro con huella dactilar
- **Gestión de Citas**: Crear, editar, eliminar y visualizar citas veterinarias
- **Base de Datos Local**: Almacenamiento persistente con Room Database
- **Integración API**: Obtención de razas de perros e imágenes desde Dog CEO API
- **UI/UX Moderna**: Diseño intuitivo con Material Design

## 🏗️ Arquitectura

- **Patrón MVVM**: Model-View-ViewModel
- **Room Database**: Persistencia de datos local
- **Retrofit**: Cliente HTTP para APIs REST
- **Navigation Component**: Navegación entre fragmentos
- **Glide**: Carga y caché de imágenes
- **Lottie**: Animaciones

## 🛠️ Tecnologías Utilizadas

- **Kotlin**: Lenguaje principal
- **Android Jetpack**: Componentes modernos de Android
- **Room Database**: Base de datos local
- **Retrofit + Gson**: Cliente HTTP y serialización JSON
- **Glide**: Gestión de imágenes
- **Lottie**: Animaciones
- **Material Design**: Componentes de UI
- **Biometric API**: Autenticación biométrica

## 🌐 APIs Utilizadas

- **Dog CEO API**: https://dog.ceo/api/
  - Lista de razas: `breeds/list`
  - Imágenes aleatorias: `breed/{breed}/images/random`

## 📦 Dependencias Principales

```kotlin
// Room Database
implementation("androidx.room:room-runtime:2.5.0")
implementation("androidx.room:room-ktx:2.5.0")

// Retrofit
implementation("com.squareup.retrofit2:retrofit:2.9.0")
implementation("com.squareup.retrofit2:converter-gson:2.9.0")

// Glide
implementation("com.github.bumptech.glide:glide:4.15.1")

// Lottie
implementation("com.airbnb.android:lottie:6.1.0")

// Biometric
implementation("androidx.biometric:biometric:1.1.0")
```

## 🚀 Instalación y Uso

1. Clona el repositorio
2. Abre el proyecto en Android Studio
3. Sincroniza las dependencias
4. Ejecuta la aplicación en un dispositivo con sensor biométrico

## 🎯 Funcionalidades Destacadas

- **Autenticación Segura**: Uso de biometría para acceso
- **Gestión Completa**: CRUD completo de citas veterinarias
- **Offline First**: Funcionamiento sin conexión para datos locales
- **Imágenes Dinámicas**: Carga automática de imágenes por raza
- **UX Intuitiva**: Navegación fluida y diseño responsivo
