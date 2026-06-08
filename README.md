# T2U2 DWI — EcoVerde

Landing page de conciencia ambiental desarrollada como proyecto individual/equipo para la materia de **Desarrollo Web Integral (DWI)**.

**Repositorio público:** https://github.com/JaimeP-0/T2U2-DWI

---

## Objetivo del proyecto

Desarrollar una página web estática con **HTML y CSS** que promueva la conciencia ambiental bajo la marca ficticia **EcoVerde**. El sitio presenta servicios de reforestación, reciclaje y conservación del agua, incluye información del equipo de trabajo y un formulario de contacto.

Además del producto web, el proyecto demuestra el uso de **Git y GitHub** con flujo de ramas, pull requests, revisión de código y resolución de conflictos.

---

## Integrantes y roles

| Integrante    | Rol           | Responsabilidades                                      |
|---------------|---------------|--------------------------------------------------------|
| Jaime Pérez   | **Líder**     | Coordinación, planificación y decisiones del proyecto  |
| María López   | **Documentador** | README, presentación y documentación del flujo     |
| Carlos Ruiz   | **Integrador**   | Merge de ramas, PRs y resolución de conflictos     |
| Ana García    | **Diseñador**    | Estilos visuales, paleta de colores y UX          |

---

## Flujo de trabajo usado

Seguimos un flujo basado en **Git Flow simplificado**:

```
main ─────────────────────────────────────────► (producción)
  │
  ├── dev ────────► desarrollo de estructura HTML y CSS base
  │
  └── diseño ─────► mejoras visuales y estilos adicionales
```

### Ramas

| Rama     | Propósito                                              |
|----------|--------------------------------------------------------|
| `main`   | Rama principal con código estable y listo para entrega |
| `dev`    | Desarrollo de estructura, contenido y estilos base     |
| `diseño` | Mejoras visuales, animaciones y refinamiento de UI     |

### Commits

Se utilizaron mensajes descriptivos siguiendo convenciones:

- `feat:` — nueva funcionalidad o contenido
- `style:` — cambios visuales o de diseño
- `docs:` — documentación
- `fix:` — correcciones
- `merge:` — integración de ramas

### Pull Request y revisión

1. Se creó un **Pull Request** desde `dev` hacia `main`.
2. Un integrante del equipo (**Carlos Ruiz**) revisó el código y aprobó los cambios.
3. Se resolvió un **conflicto de merge** en el archivo `index.html` (modificación simultánea del título en ramas `dev` y `diseño`).

### Resolución de conflictos

El conflicto se produjo al modificar la etiqueta `<title>` en dos ramas distintas. La resolución combinó ambas versiones manteniendo coherencia con la marca EcoVerde.

---

## Estructura del proyecto

```
T2U2-DWI/
├── index.html          # Página principal
├── css/
│   ├── estilos.css     # Estilos base (rama dev)
│   └── diseño.css      # Estilos visuales (rama diseño)
├── docs/
│   └── presentacion.html
└── README.md
```

---

## Cómo ver el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/JaimeP-0/T2U2-DWI.git
   ```
2. Abre `index.html` en tu navegador.

---

## Presentación

La presentación del proyecto y del flujo de trabajo está en:

- [docs/presentacion.html](docs/presentacion.html)

---

## Tecnologías

- HTML5
- CSS3 (variables, Grid, Flexbox, media queries)
- Git & GitHub

---

*Proyecto académico — T2U2 DWI — Desarrollo Web Integral — 2026*
