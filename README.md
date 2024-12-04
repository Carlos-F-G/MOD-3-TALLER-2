# Proyecto: Hospital Web - Evaluación M3 - Taller 2

Este proyecto corresponde a la implementación de funcionalidades en un sitio web de un hospital privado utilizando JavaScript, HTML, CSS (SASS) y conceptos como ciclos, validaciones, y manejo de eventos.

---

## **Requisitos Implementados**

### **1. Configuración y Entorno**
- **Configuración del entorno de trabajo:**
  - El entorno fue configurado con Node.js para ejecutar SASS.
  - Se implementó un sistema modular utilizando SASS y la metodología BEM para la estructura de los estilos.

### **2. Solicitar y Validar Información del Usuario**
- **Uso de `prompt`:**
  - Se solicitó información básica al usuario, incluyendo su nombre, correo electrónico y número de teléfono.
  - Los datos fueron validados para asegurar que el correo contuviera un `@` y que el número de teléfono fuera numérico.

- **Mostrar datos:**
  - Los datos ingresados fueron mostrados tanto en la consola como en un `alert` para retroalimentar al usuario.

### **3. Lista Dinámica de Servicios Médicos**
- **Cuadro de búsqueda para servicios médicos:**
  - Se implementó un cuadro de búsqueda que permite filtrar servicios médicos de forma dinámica a medida que el usuario escribe.
  - Los servicios fueron mostrados de manera atractiva utilizando un diseño con efectos de `hover`.

### **4. Estilos Modulares con SASS y BEM**
- **Estructura de los estilos:**
  - Los estilos fueron organizados en módulos utilizando SASS. Cada sección del proyecto (como el header, footer y servicios) tiene su propio archivo de estilo.
  - La estructura BEM fue aplicada para mantener un código limpio y escalable.

### **5. Validaciones y Manejo de Errores**
- **Manejo de errores con `try/catch`:**
  - Se utilizó `try/catch` para manejar errores en la validación de datos del usuario.
  - Los errores fueron mostrados en la consola y también a través de alertas para retroalimentar al usuario.
