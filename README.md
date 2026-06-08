## Objetivo del proyecto

Desarrollar una página web estática con **HTML y CSS** para **CineSpot**, un catálogo ficticio de películas y series. El sitio permite explorar estrenos, recomendaciones por género y una sección de favoritos, además de un formulario para sugerir títulos.

El proyecto también demuestra el uso de **Git y GitHub** con flujo de ramas, pull requests, revisión de código y resolución de conflictos.

## Integrantes y roles

| Integrante   | Roles                                                                 | Responsabilidades                                                                 |
|--------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| Jaime Puente | **Líder**, **Documentador**, **Integrador** y **Diseñador**          | Coordinación, documentación, integración de ramas, diseño visual y desarrollo web |

> Proyecto individual: un solo integrante asumió los cuatro roles requeridos.

## Flujo de trabajo usado

Se utilizó un flujo basado en **Git Flow simplificado**:

```
main ----------------------------------------> (producción)
  |
  +-- dev --------> desarrollo de estructura HTML y CSS base
  |
  +-- diseno -----> mejoras visuales y estilos adicionales
```

1. **Rama `main`:** código estable listo para entrega.
2. **Rama `dev`:** desarrollo de contenido, estructura HTML y estilos base.
3. **Rama `diseno`:** refinamiento visual con `css/diseno.css`.
4. **Merge con conflicto:** al integrar `diseno` en `dev`, hubo conflicto en el `<title>` de `index.html`; se resolvió manteniendo `CineSpot | T2U2 DWI`.
5. **Pull Request:** se abrió un PR de `dev` hacia `main`, se revisó el código (rol integrador) y se hizo merge.
6. **Commits:** mensajes descriptivos con prefijos `feat:`, `style:`, `docs:`, `fix:` y `merge:`.

**Repositorio:** https://github.com/JaimeP-0/T2U2-DWI
