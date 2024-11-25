# ¿Qué es Git?

Git es un sistema de control de versiones que permite rastrear cambios en proyectos de software. Es distribuido, rápido y facilita la colaboración en equipo.

## Comandos básicos:

- `git init`: Crea un repositorio.
- `git add`: Añade archivos al área de preparación.
- `git commit`: Guarda cambios localmente.
- `git push/pull`: Envía o recibe cambios con un repositorio remoto.

---

# ¿Qué es Git Flow?

Git Flow es una estrategia de trabajo con ramas en Git, ideal para gestionar versiones y colaboraciones.

## Ramas principales:

- **main**: Código listo para producción.
- **develop**: Código en desarrollo.

## Ramas de soporte:

- **Feature**: Nuevas funcionalidades.
- **Release**: Preparación para producción.
- **Hotfix**: Correcciones urgentes en producción.

### Flujo:
Trabajas en `feature`, fusionas en `develop`, y pasas a `main` mediante una `release`. **Hotfix** se usa para bugs críticos.
