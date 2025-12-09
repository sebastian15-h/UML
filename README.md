# Sistema de Gestión de Biblioteca Digital

## Descripción
Sistema para gestión de bibliotecas con módulos de autenticación y gestión de libros/préstamos.

## Módulos

### Módulo 1: Autenticación y Usuarios
- Registro de usuarios
- Login/Logout
- Gestión de perfiles
- Control de roles

### Módulo 2: Gestión de Libros y Préstamos
- Catálogo de libros
- Sistema de préstamos
- Reservas y devoluciones
- Reportes


## Estructura del Diagrama

┌─────────────────────────────────────┐
│ SISTEMA DE BIBLIOTECA DIGITAL │
├─────────────────────────────────────┤
│ │
│ [Iniciar Sesión] [Registrarse] │
│ [Buscar Libros] [Ver Perfil] │
│ │
│ [Solicitar Préstamo] [Ver Préstamos]│
│ [Reservar Libro] [Renovar] │
│ │
│ [Gestionar Usuarios][Agregar Libros]│
│ [Generar Reportes] [Configurar] │
│ │
└─────────────────────────────────────┘
↑ ↑ ↑
│ │ │
Estudiante Profesor Administrador
↖ ↗
[Usuario Base]

## Instalación
1. Clonar repositorio
2. Instalar dependencias
3. Configurar base de datos
4. Ejecutar aplicación

## Uso
- Estudiantes: Buscar y pedir libros
- Profesores: Préstamos extendidos
- Administradores: Gestionar sistema completo

## Autor
[Tu Nombre]

## Repositorio
https://github.com/tu-usuario/biblioteca-digital
