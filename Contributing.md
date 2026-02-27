🧾 Guía de Contribución a Oficial Bizzus

¡Gracias por tu interés en contribuir a Oficial Bizzus! 🚀
Este documento describe el proceso y las convenciones que seguimos para mantener un flujo de trabajo ordenado, claro y colaborativo.

📑 Índice

🧾 Guía de Contribución

📌 Convenciones de Commits

📝 Ejemplo

📦 Versionamiento Semántico

🔐 Cierre de Issues y Co-Autores

📚 Recursos Adicionales

📌 Convenciones de Commits

En Oficial Bizzus usamos una convención basada en Conventional Commits, adaptada a nuestro proyecto.

🏗 Estructura del commit
<type>(<scope>): <resumen breve>

<cuerpo del mensaje>

<footer>
🔤 type (tipo de cambio)

Debe escribirse en minúsculas.

✨ feat → Nueva funcionalidad.

🐛 fix → Corrección de errores.

📖 docs → Cambios en documentación.

🎨 style → Cambios de formato (sin lógica).

♻️ refactor → Reestructuración sin añadir funciones.

🧪 test → Pruebas nuevas o actualizadas.

🛠 chore → Mantenimiento o configuración.

🔀 merge → Fusión de ramas.

🚀 release → Nueva versión del proyecto.

📂 scope (área afectada)

Opcional si el cambio es general.

Ejemplos:

auth

users

products

dashboard

database

frontend

backend

✍️ resumen breve

Debe ser:

Claro y conciso

Máximo 70 caracteres

En tiempo presente

En minúsculas

Sin punto final

📄 cuerpo del mensaje

Explica el por qué del cambio.

Reglas:

Dejar una línea en blanco entre resumen y cuerpo

Máximo 80 caracteres por línea

Evitar detalles innecesarios

🏷 footer

Se usa para información adicional:

Cierre de issues → Closes #número

Co-autores → co-authored-by: Nombre <correo>

Cambios importantes → BREAKING CHANGE:

📝 Ejemplo
feat(products): agregar módulo de gestión de inventario

Se implementa el módulo para administrar productos
desde el panel administrativo, permitiendo registrar,
editar y eliminar artículos del sistema.

Closes #12
co-authored-by: Dairon Salazar <correo@oficialbizzus.com>
📦 Versionamiento Semántico

El proyecto sigue el estándar SemVer 2.0.0.

Formato:

vX.Y.Z

🔴 X (major) → Cambios incompatibles.

🟡 Y (minor) → Nuevas funcionalidades compatibles.

🟢 Z (patch) → Correcciones y mejoras menores.

Ejemplo:

v1.0.0
v1.1.0
v1.1.1
🔐 Cierre de Issues y Co-Autores

Para cerrar un issue automáticamente:

Closes #número

Para agregar un co-autor:

co-authored-by: Nombre <correo>
📚 Recursos Adicionales

Conventional Commits

Semantic Versioning

Guía de Git Commit Messages
