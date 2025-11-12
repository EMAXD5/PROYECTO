# 📇 Gestor de Agenda de Contactos en C++

## 🧩 Descripción del Proyecto
El **Gestor de Agenda de Contactos** es un sistema desarrollado en **C++** que permite registrar, buscar, mostrar y eliminar contactos desde memoria.  
El programa integra diversas **estructuras de datos** (arreglos dinámicos, pilas, colas, listas enlazadas y árboles binarios de búsqueda) para aplicar los conceptos vistos en el curso **Organización de Archivos y Estructuras de Datos**.

---

## 🎯 Objetivos
- Aplicar estructuras de datos lineales y no lineales en un problema real.  
- Implementar funciones de búsqueda y ordenamiento.  
- Reforzar buenas prácticas de programación y documentación.  
- Utilizar **GitHub** como herramienta de control de versiones.

---

## ⚙️ Requisitos Técnicos
- **Lenguaje:** C++17 o superior  
- **Compilador recomendado:**  
  - MinGW / g++ (Windows)  
  - g++ (Linux)  
  - Clang (macOS)  
- **IDE recomendado:** Visual Studio Code o Dev-C++  

---

## 🧱 Estructuras Utilizadas
- `ArrayList` → almacenamiento principal  
- `Lista enlazada` → eliminación de contactos  
- `Pila` → historial de operaciones (agregar/eliminar)  
- `Cola` → manejo de contactos pendientes  
- `Árbol binario (BST)` → recorrido ordenado de contactos  
- **Búsqueda:** secuencial y binaria  
- **Ordenamiento:** por nombre o teléfono  

---

🧰 Instrucciones de instalación

Para ejecutar el sistema Gestor de Agenda de Contactos en C++, se deben seguir los siguientes pasos:

Clonar o descargar el repositorio

Opción 1: Clonar el repositorio desde GitHub usando el siguiente comando:

git clone https://github.com/EMAXD5/PROYECTO.git


Opción 2: Descargar el proyecto en formato ZIP desde la página del repositorio
(Code → Download ZIP) y extraerlo en el equipo local.

Abrir el proyecto

Si se utiliza Visual Studio, abrir el archivo:

proyecto.sln


Este archivo contiene la configuración completa del entorno de desarrollo.

Alternativamente, se puede abrir directamente el archivo:

proyecto.cpp


desde cualquier editor compatible con C++ (por ejemplo, Visual Studio Code o Dev-C++).

Compilar el código

En Visual Studio:

Seleccionar el modo Release o Debug.

Presionar Ctrl + F5 para compilar y ejecutar el programa.

En otros entornos (como MinGW o VS Code con terminal):

g++ -std=c++17 proyecto.cpp -o agenda
./agenda


Ejecutar el programa

Al ejecutarlo, aparecerá el menú principal en consola con las opciones para:

Agregar, buscar, listar o eliminar contactos.

Visualizar el historial (pila) y los recorridos del árbol binario.

Requisitos

Sistema operativo: Windows 10 o superior

Compilador compatible con C++17 (Visual Studio, MinGW, Clang)

Git (opcional, para clonar el repositorio)


Este proyecto se distribuye bajo la licencia MIT, lo que permite su uso, modificación y distribución con fines educativos o personales.
