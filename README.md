# 🏥 Hospital UTN FRGP - Sistema de Gestión Hospitalaria

Este proyecto fue desarrollado como parte de la **Tecnicatura Universitaria en Programación (UTN FRGP)**.  
Se trata de una aplicación web desarrollada con **C#**, **ASP.NET MVC** y **Entity Framework**, que simula un sistema de gestión hospitalaria con funcionalidades completas de CRUD, navegación por vistas y almacenamiento en base de datos.

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción |
|------------|-------------|
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="24"/> **C#** | Lenguaje principal de programación. |
| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" width="24"/> **ASP.NET MVC** | Framework para crear la estructura del sistema bajo el patrón Modelo-Vista-Controlador. |
| 🛢️ **Entity Framework** | ORM utilizado para mapear clases a una base de datos relacional. |
| 🧩 **Razor Pages** | Sistema de vistas dinámicas utilizado para mostrar contenido del lado del servidor. |
| 💻 **SQL Server** | Base de datos relacional para almacenamiento de información persistente. |
| 🖌️ **Bootstrap** | Framework CSS para la creación de una interfaz moderna y responsive. |

---

## ✅ Funcionalidades Implementadas

- ✅ CRUD completo de **Pacientes**, **Doctores**, **Especialidades**, **Turnos**.
- ✅ Listado y detalle de cada entidad.
- ✅ Formularios validados con **DataAnnotations**.
- ✅ Navegación fluida entre vistas mediante **Razor** y **Routing de ASP.NET**.
- ✅ Conexión a base de datos mediante **Entity Framework** (Code First o Database First).
- ✅ Diseño responsive con Bootstrap.

---

## 📁 Estructura del Proyecto
```
Hospital-UTN-FRGP/
├── Controllers/
│ ├── PacientesController.cs
│ ├── MedicosController.cs
│ └── TurnosController.cs
├── Models/
│ ├── Paciente.cs
│ ├── Medico.cs
│ └── Turno.cs
├── Views/
│ ├── Pacientes/
│ ├── Medicos/
│ └── Shared/
├── wwwroot/
│ └── (Estilos, JS, imágenes)
├── Data/
│ └── HospitalContext.cs
├── appsettings.json
├── Program.cs
├── Startup.cs
└── README.md
```


---

## 🚀 Objetivo del Proyecto

El objetivo del sistema es representar una solución funcional para la gestión hospitalaria, aplicando las buenas prácticas de desarrollo web con **.NET**, organización por capas y modelo relacional de datos.

---

## 📌 Posibles Mejoras a Futuro

- Implementación de frontend

---

👨‍💻 Desarrollado por [Joel Nicolás Morán](https://www.linkedin.com/in/joel-moran)  
📂 Repositorio: [github.com/ChiqoGamer/Hospital-UTN-FRGP](https://github.com/ChiqoGamer/Hospital-UTN-FRGP)
