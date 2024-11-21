# Gestor de Pacientes de Veterinaria - CRUD con Zustand

Este proyecto es una aplicación web para gestionar pacientes de una veterinaria. Permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para mantener un registro de los pacientes, utilizando React, TypeScript, Tailwind CSS y Zustand como gestor de estado.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Funcionalidades](#funcionalidades)
- [Aprendizaje Clave: Integración de Zustand](#aprendizaje-clave-integración-de-zustand)
- [Conclusión](#conclusión)

---

## Descripción del Proyecto

La aplicación permite a los usuarios:
- Registrar pacientes con información como nombre, propietario, teléfono, y descripción del caso.
- Visualizar una lista de pacientes registrados.
- Editar la información de los pacientes.
- Eliminar pacientes del registro.

Todo esto se logra utilizando **Zustand** como gestor de estado, lo que facilita una administración más sencilla y eficaz de los datos a través de toda la aplicación.

---

## Tecnologías Utilizadas

- **React**: Biblioteca para la creación de interfaces de usuario.
- **TypeScript**: Tipado estático para mejorar la robustez del código.
- **Tailwind CSS**: Framework CSS para diseño responsivo y rápido.
- **Zustand**: Librería para gestionar el estado de forma simple y flexible.

---

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/LozanoCH2/React--Pacientes-Veterinaria--Zustand.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd React--Pacientes-Veterinaria--Zustand
    ```

3. Instala las dependencias:
    ```bash
    npm install
    ```

4. Inicia el servidor de desarrollo:
    ```bash
    npm run dev
    ```

---

## Funcionalidades

- **Crear Pacientes**: Registra nuevos pacientes con todos sus detalles.
- **Leer Pacientes**: Visualiza una lista de pacientes registrados.
- **Actualizar Pacientes**: Modifica la información de un paciente existente.
- **Eliminar Pacientes**: Borra pacientes del registro.

---

## Aprendizaje Clave: Integración de Zustand

El uso de **Zustand** en este proyecto ha sido un punto clave para mejorar la gestión del estado. A diferencia de otros gestores de estado como Redux, Zustand proporciona una API minimalista y muy intuitiva que facilita:

- **Estructura Sencilla**: La configuración del estado global no requiere una estructura compleja de reducers o actions.
- **Actualizaciones Rápidas**: Las actualizaciones de estado son más eficientes y directas gracias a su enfoque basado en hooks.
- **Menor Sobrecarga**: Al no depender de un sistema de boilerplate, se reduce considerablemente la cantidad de código necesaria.
- **Escalabilidad**: Ideal para proyectos pequeños y medianos, permitiendo un crecimiento sencillo en caso de añadir nuevas funcionalidades.

Este proyecto me permitió aprender a integrar Zustand en un flujo de trabajo real y comprender cómo utilizarlo para manejar el estado de manera eficiente y escalable en aplicaciones modernas.

---

## Conclusión

El **Gestor de Pacientes de Veterinaria** no solo es una herramienta útil para administrar pacientes, sino que también representa un gran paso en mi aprendizaje del ecosistema de React y de herramientas modernas como Zustand. Esta experiencia refuerza la importancia de elegir el gestor de estado adecuado según las necesidades del proyecto, lo que contribuye a la creación de aplicaciones más optimizadas y mantenibles.
