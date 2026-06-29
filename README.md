# Gestión académica — Angular

Aplicación web para administrar alumnos y cursos. Incluye autenticación, permisos de administrador, navegación protegida y manejo de estado global con NgRx.

## Funcionalidades

- Inicio de sesión y estado de sesión.
- Guards para usuarios autenticados y administradores.
- Alta, edición y listado de alumnos.
- Alta, edición, detalle y listado de cursos.
- Pipes personalizados para fechas y valores booleanos.
- Estado de cursos y autenticación con NgRx.
- Pruebas unitarias de componentes, servicios, guards, pipes y reducers.

## Stack

- Angular 15 y TypeScript
- Angular Material y CDK
- NgRx Store, Effects y DevTools
- RxJS
- Jasmine y Karma

## Arquitectura

La aplicación se divide en módulos de `autenticacion`, `alumnos`, `cursos`, `core` y `shared`. Los modelos viven en `src/app/models`; los guards y servicios transversales en `core`; y el estado de negocio en carpetas `state`.

## Ejecución

```bash
npm install
npm start
```

Abrir `http://localhost:4200`.

## Comandos

```bash
npm run build
npm test
npm run watch
```

La configuración del entorno se encuentra en `src/environment/environment.ts`.

> Proyecto final educativo orientado a arquitectura modular, routing, formularios y estado reactivo en Angular.