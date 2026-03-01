# 👕🔥 Guía de Contribución a Oficial Bizz8uz

¡Gracias por tu interés en contribuir a Oficial Bizzus!  
Este documento describe el proceso y las convenciones que seguimos para mantener un flujo de trabajo ordenado, profesional y colaborativo.

---

## 📑 Índice

- 📌 Convenciones de Commits  
- 📝 Ejemplo  
- 🔢 Versionamiento Semántico  
- 🤝 Cierre de Issues y Co-Autores  
- 📚 Recursos adicionales  

---

## 📌 Convenciones de Commits

Utilizamos una convención basada en Conventional Commits, adaptada para Oficial Bizzus.

### 🧱 Estructura del mensaje

<type>(<scope>): <resumen breve>

<cuerpo del mensaje>

<footer>

---

### 🏷️ type: Tipo de cambio. Usa minúsculas.

- ✨ feat → Nueva funcionalidad para el usuario.  
- 🐛 fix → Corrección de errores.  
- 📚 docs → Cambios en la documentación.  
- 🎨 style → Formateo sin cambios en la lógica.  
- ♻️ refactor → Refactorización sin añadir funcionalidad.  
- 🧪 test → Añadir o actualizar pruebas.  
- 🔧 chore → Tareas de mantenimiento.  
- 🔀 merge → Fusión de ramas.  
- 🚀 release → Creación de una nueva versión.  

---

### 🧩 scope

Módulo o área afectada (opcional si el cambio es global).

Ejemplos:
- auth  
- frontend  
- backend  
- inventory  
- orders  
- ui  

---

### 📝 resumen breve

- Máximo 70 caracteres.  
- Claro y conciso.  
- En tiempo presente.  
- En minúsculas.  
- Sin punto final.  

Debe explicar de forma rápida qué se hizo.

---

### 📖 cuerpo del mensaje

- Explica el motivo del cambio.  
- Agrega contexto si es necesario.  
- Deja una línea en blanco entre el resumen y el cuerpo.  
- Máximo 80 caracteres por línea.  

Evita detalles técnicos innecesarios.

---

### 📎 footer

Información adicional como:

- Cierre de issues → Closes #número  
- Co-autores → co-authored-by: Nombre <correo>  
- Breaking changes →  
  BREAKING CHANGE: descripción del cambio incompatible  

---

## 📝 Ejemplo

feat(inventory): agregar gestión de stock por tallas

Se implementa control de inventario por talla y color
para mejorar la administración de productos en la tienda.

Closes #12
co-authored-by: Sharick Mateus <correo@bizzuz.com>

---

## 🔢 Versionamiento Semántico

El proyecto sigue SemVer 2.0.0:

- 🔴 X (major) → Cambios incompatibles importantes.  
- 🟡 Y (minor) → Nuevas funcionalidades compatibles.  
- 🟢 Z (patch) → Correcciones y mejoras menores.  

### 📌 Formato de versión

vX.Y.Z

Ejemplo:

v1.2.3

---

## 🤝 Cierre de Issues y Co-Autores

Para cerrar issues:
Closes #número  

Para agregar co-autores:
co-authored-by: Nombre <correo>  

---

## 📚 Recursos adicionales

- Conventional Commits  
- Semantic Versioning  
- Guía de Git Commit Messages  
