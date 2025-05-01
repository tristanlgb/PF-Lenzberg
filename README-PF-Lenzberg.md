# 🎓 PF-Lenzberg – Sistema de Gestión de Cursos

**Entrega Final del Curso de Angular en Coderhouse**  
Proyecto aprobado con Angular y TypeScript.

## 📚 Descripción

Este proyecto es una aplicación web básica diseñada para gestionar cursos, estudiantes y docentes. Permite a los usuarios:

- Visualizar una lista de cursos disponibles.
- Inscribirse en cursos.
- Administrar cursos (crear, editar y eliminar) para usuarios con perfil de administrador.

## 👥 Roles de Usuario

- **Administrador**:
  - Crear nuevos cursos con fechas e inscripciones.
  - Editar y eliminar cursos existentes.
- **Usuario Estudiante**:
  - Visualizar cursos disponibles.
  - Inscribirse en cursos.

## 🛠️ Tecnologías Utilizadas

- Angular CLI 15.1.1
- TypeScript
- HTML5 y CSS3

## 🚀 Instrucciones para Ejecutar el Proyecto

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tristanlgb/PF-Lenzberg.git
   cd PF-Lenzberg
   ```

2. **Instalar dependencias**:
   ```bash
   npm install
   ```

3. **Iniciar el servidor de desarrollo**:
   ```bash
   ng serve
   ```

4. **Acceder a la aplicación**:
   Abre tu navegador en `http://localhost:4200/`.

## 🧪 Scripts Disponibles

- `ng serve`: Inicia el servidor de desarrollo.
- `ng build`: Compila la aplicación para producción.
- `ng test`: Ejecuta pruebas unitarias con Karma.
- `ng e2e`: Ejecuta pruebas end-to-end (requiere configuración adicional).

## 📁 Estructura del Proyecto

```
PF-Lenzberg/
├── src/
│   ├── app/
│   │   ├── components/       # Componentes de la aplicación
│   │   ├── services/         # Servicios para la lógica de negocio
│   │   ├── models/           # Interfaces y modelos de datos
│   │   └── app.module.ts     # Módulo principal de la aplicación
├── angular.json              # Configuración de Angular CLI
├── package.json              # Dependencias y scripts del proyecto
├── tsconfig.json             # Configuración de TypeScript
└── README.md                 # Documentación del proyecto
```

## 📌 Notas Adicionales

- Este proyecto fue desarrollado como parte del curso de Angular en Coderhouse.
- Actualmente, la persistencia de datos es en memoria; no se utiliza una base de datos.
- Se recomienda implementar autenticación y almacenamiento persistente para un entorno de producción.

## 👨‍💻 Autor

**Tristan Lenzberg**  
Desarrollador Full Stack  
[GitHub](https://github.com/tristanlgb) | [LinkedIn](https://ar.linkedin.com/in/tristan-lenzberg-9b13422b3)
