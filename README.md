School API – Proyecto Final

Este proyecto es una API REST para gestionar estudiantes, materias y calificaciones.  
Fue desarrollada en Go, usando el framework Gin y la base de datos SQLite mediante GORM.

Requisitos

Antes de ejecutar el proyecto asegúrate de tener instalado:

Go 1.20 o superior
Git
DBeaver

Instalación

Clona el repositorio:

```bash
git clone https://github.com/tuusuario/school-api.git
cd school-api

Endpoints Principales
Students

POST /api/students

GET /api/students

GET /api/students/:student_id

PUT /api/students/:student_id

DELETE /api/students/:student_id

Subjects

POST /api/subjects

GET /api/subjects/:subject_id

PUT /api/subjects/:subject_id

DELETE /api/subjects/:subject_id

Grades

POST /api/grades

PUT /api/grades/:grade_id

DELETE /api/grades/:grade_id

GET /api/grades/student/:student_id

GET /api/grades/:grade_id/student/:student_id
