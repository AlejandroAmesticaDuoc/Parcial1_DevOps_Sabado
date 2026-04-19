# Evaluación partial 1- DevOps

## Descripción
Este repositorio contiene Evaluación partial 1 desarrollado para la implementación de prácticas DevOps utilizando GitHub.

---

## Estrategia de ramas

Se utiliza **GitFlow**, ya que permite organizar el desarrollo colaborativo separando:

- main: versión estable
- develop: integración de cambios
- feature/*: nuevas funcionalidades
- hotfix/*: correcciones urgentes

### ¿Por qué GitFlow?
Permite:
- Mejor control de versiones
- Trabajo en paralelo
- Mayor trazabilidad

---

## Flujo de trabajo

1. Crear rama feature desde develop
2. Realizar commits
3. Crear Pull Request hacia develop
4. Revisar y aprobar cambios
5. Merge a develop
6. Hotfix desde main en caso de errores

---

## Convención de commits

Se utiliza el estándar:

- feat: nueva funcionalidad
- fix: corrección de errores
- docs: documentación
- refactor: mejora de código

Ejemplo:

feat: agregar login de usuario

fix: corregir error en validación
