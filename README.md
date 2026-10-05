# EquipoWeb

Proyecto académico: U1 Actividad 8.
Flujo de trabajo, control de versiones y despliegue continuo.

## Aplicación
Prototipo de aplicación web para organizar tareas de un equipo distribuido.

## Herramientas
- Git
- GitHub
- GitHub Actions
- GitHub Pages

## Ramas
- main: versión estable.
- develop: integración de cambios.
- feature/*: nuevas funciones.
- fix/*: corrección de errores.

## Política de commits
Formato: tipo: descripción

Ejemplos:
- feat: agregar formulario de tareas
- fix: validar títulos vacíos
- docs: actualizar instrucciones

## Integración propuesta
1. Crear una rama desde develop.
2. Realizar cambios y subirlos.
3. Abrir un Pull Request hacia develop.
4. Solicitar revisión de otro integrante.
5. Integrar los cambios aprobados.
6. Abrir un Pull Request de develop hacia main para publicar.

## Responsabilidades propuestas
- Administrador: configura el repositorio y los accesos.
- Desarrollador: implementa cambios en ramas.
- Revisor: evalúa los Pull Requests de otros integrantes.
- Responsable de integración: verifica requisitos y realiza el merge.

## Despliegue propuesto
GitHub Actions validará los cambios y publicará en GitHub Pages
después de integrar a main.

## Estado
Estructura inicial. Protección de ramas y automatización pendientes.
