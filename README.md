# Aplicación de Lista de Tareas en Android

Esta es una aplicación Android que permite gestionar tus tareas diarias de manera sencilla y eficiente. Los usuarios pueden agregar tareas, eliminarlas, marcarlas como completadas y mucho más. Además, la aplicación utiliza **Firebase** para el registro e inicio de sesión, asegurando que cada usuario solo pueda ver sus propias tareas.

## Características

- **Inicio de sesión y registro**: Los usuarios pueden registrarse e iniciar sesión utilizando su correo electrónico y contraseña. Firebase maneja la autenticación de usuarios.
- **Gestión de tareas**:
  - Agregar tareas.
  - Marcar tareas como completadas.
  - Eliminar tareas.
- **Visibilidad privada**: Cada usuario solo puede ver y gestionar las tareas que ha creado.
- **Interfaz intuitiva**: Diseño sencillo y fácil de usar para gestionar las tareas.

## Tecnologías utilizadas

- **Android**: Android Studio (Java/Kotlin)
- **Firebase**:
  - **Firebase Authentication**: Para manejar el registro e inicio de sesión.
  - **Firebase Firestore**: Para almacenar las tareas de cada usuario.
- **Gradle**: Para gestionar las dependencias del proyecto.

## Requisitos previos

- **Android Studio**: Asegúrate de tener **Android Studio** instalado. Si no lo tienes, puedes descargarlo desde [aquí](https://developer.android.com/studio).
- **Cuenta de Firebase**: Necesitarás una cuenta en Firebase. Si no tienes una, puedes crearla [aquí](https://firebase.google.com/).
- **SDK de Firebase**: Para integrar Firebase en tu aplicación Android.

## Instalación

### 1. Clonar el repositorio

Primero, clona este repositorio en tu máquina local:

```bash
git clone https://github.com/tu-usuario/tareas-app-android.git
