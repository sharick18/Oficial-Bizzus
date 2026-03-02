# Guía de Contribución a Oficial Bizzus

¡Gracias por tu interés en contribuir! Este documento describe el proceso y las convenciones que seguimos para mantener un flujo de trabajo ordenado y colaborativo.

---

## Índice

- [Guía de Contribución a Oficial Bizzus](#guía-de-contribución-a-oficial-bizzus)
  - [Índice](#índice)
  - [Convenciones de Commits](#convenciones-de-commits)
    - [Ejemplo](#ejemplo)
  - [Versionamiento Semántico](#versionamiento-semántico)
  - [Cierre de Issues y Co-Autores](#cierre-de-issues-y-co-autores)
  - [Recursos adicionales](#recursos-adicionales)

---

## Convenciones de Commits

Utilizamos una convención basada en Conventional Commits, adaptada para Oficial Bizzus.  
La estructura del mensaje es:

```
<type>(<scope>): <resumen breve>

<cuerpo del mensaje>

<footer>
```

- **type** : Tipo de cambio. Usa minúsculas.

  - `feat`: Nueva funcionalidad para el usuario.
  - `fix`: Corrección de errores para el usuario.
  - `docs`: Cambios en la documentación.
  - `style`: Formateo, sin cambios en la lógica.
  - `refactor`: Refactorización, sin añadir funcionalidad.
  - `test`: Añadir o actualizar pruebas.
  - `chore`: Tareas de mantenimiento.
  - `merge`: Fusión de ramas.
  - `release`: Creación de una nueva versión.

- **scope** : Módulo o área afectada (opcional si el cambio es global).

- **resumen breve** : Primera línea del mensaje, clara y concisa (máximo 70 caracteres), que explica de forma rápida y entendible qué se hizo.  
  Es obligatorio y debe estar en tiempo presente, en minúsculas y sin punto final.

- **cuerpo del mensaje** : Descripción más detallada del cambio, explicando el motivo y contexto si es relevante.  
  Debe ayudar a entender el "por qué" del cambio, pero evita detalles innecesarios o técnicos muy profundos.  
  Deja una línea en blanco entre el resumen y el cuerpo.  
  Cada línea debe tener máximo 80 caracteres.

- **footer** : Información adicional, como cierre de issues (`Closes #número`),  
  co-autores (`co-authored-by: Nombre <correo>`),  
  notas de breaking change (`BREAKING CHANGE: descripción`),  
  referencias a tareas relacionadas o cualquier metadato relevante.

---

### Ejemplo

```
feat(inventory): agregar gestión de stock por tallas

Se implementa control de inventario por talla y color,
permitiendo mejorar la administración de productos.

Closes #12
co-authored-by: Sharick Mateus <oficial@bizzus.com>
```

---

## Versionamiento Semántico

El proyecto sigue **SemVer 2.0.0**:

- **X (major)** – Cambios incompatibles a nivel de API o funcionalidades principales.
- **Y (minor)** – Nuevas funcionalidades compatibles con versiones anteriores.
- **Z (patch)** – Correcciones de errores y mejoras menores.

### Recomendación

Etiqueta las versiones siguiendo el formato estándar:

```
vX.Y.Z
```

Por ejemplo:

```
v1.2.3
```

---

## Cierre de Issues y Co-Autores

- Para cerrar issues, usa `Closes #número` en el footer.
- Para co-autores, agrega `co-authored-by: Nombre <correo>` en el footer.

---

## Recursos adicionales

- Conventional Commits  
- Semantic Versioning  
- Guía de Git Commit Messages  
---

## 📚 Recursos adicionales

- Conventional Commits  
- Semantic Versioning  
- Guía de Git Commit Messages  
