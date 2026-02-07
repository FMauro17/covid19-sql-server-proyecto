# Sistema de Gestión de Datos COVID-19 - Ciudad Autónoma de Buenos Aires

![SQL Server](https://img.shields.io/badge/SQL%20Server-2022-red)
![Azure Data Studio](https://img.shields.io/badge/Azure%20Data%20Studio-Latest-blue)
![Status](https://img.shields.io/badge/Status-Completado-success)

## 📋 Descripción

Sistema completo de gestión de datos COVID-19 de Buenos Aires desarrollado con SQL Server, procesando **3.6M+ registros**. Implementa optimización con índices, triggers para auditoría automática, stored procedures con validación, funciones reutilizables y views para reportes.

Proyecto demostrativo de **SQL Server Programming** aplicando best practices profesionales.

## 🎯 Objetivo

Demostrar dominio avanzado de SQL Server mediante un proyecto real que incluye:
- Diseño de base de datos relacional
- Optimización de performance
- Programación avanzada (Triggers, SPs, Funciones, Views, Transacciones, Cursores)
- Manejo de grandes volúmenes de datos
- Best practices profesionales

## 🛠️ Tecnologías

- **SQL Server 2022** (Docker en Mac)
- **Azure Data Studio**
- **Python** (carga de datos con pymssql)
- **Docker**

## 📊 Estructura del Proyecto

### FASE 1: Exploración y Análisis
- Creación de base de datos y tablas
- Carga de 3.6M+ registros desde CSV
- Análisis exploratorio de datos

### FASE 2: Limpieza y Normalización
- Corrección de inconsistencias
- Manejo de valores NULL
- Validación de fechas
- Normalización de texto

### FASE 3: Optimización
- **7 índices** creados (Clustered y Non-Clustered)
- **19 columnas** optimizadas
- Mejora de performance: 60-80%
- Reducción de espacio: ~40%

### FASE 4: Lógica de Negocio
- **3 Triggers**: Auditoría automática y validaciones
- **4 Stored Procedures**: Reportes, limpieza, actualizaciones
- **3 Funciones**: Escalares y de tabla
- **2 Views**: Dashboards y casos enriquecidos
- **Transacciones**: Operaciones atómicas
- **Cursores**: Procesamiento fila por fila

## 📈 Estadísticas

- **Registros procesados**: 3,600,000+
- **Período**: 2020-2021
- **Tablas**: 6
- **Índices**: 7
- **Objetos programables**: 12
- **Líneas de código**: ~2,500

## 🖼️ Capturas del Proyecto

### Estructura de Base de Datos
![Estructura](imagenes/ESTRUCTURA%20BASE%20DE%20DATOS.png)

### Análisis de Datos
![Distribución por Género](imagenes/DISTRIBUCION%20DE%20CASOS%20POR%20GENERO.png)
![Fechas Extremas](imagenes/CASOS%20DIFERENCIAS%20FECHAS%20EXTREMAS.png)

### Objetos Programables
![Triggers](imagenes/CREANDO%20TRIGGER.png)
![Stored Procedures](imagenes/CREANDO%20PROCEDIMIENTOS.png)
![Funciones](imagenes/CREANDO%20FUNCIONES.png)
![Views](imagenes/CREANDO%20VIEWS.png)
![Transacciones](imagenes/CREANDO%20TRANSACCION.png)
![Cursores](imagenes/CREANDO%20CURSOR.png)

### Validaciones
![Foreign Keys](imagenes/ANALIZANDO%20EXISTENCIA%20DE%20FOREIGN%20KEYS.png)
![Fechas](imagenes/VERIFICACION%20DE%20FECHAS%20INCONSISTENTES.png)

## 🎓 Certificación

**SQL Server Programming** - EducaciónIT (Enero - Febrero 2026)

## 📁 Archivos del Proyecto

- `Proyecto_Personal_SQL.sql` - Script completo con todas las fases
- `imagenes/` - Capturas de pantalla del desarrollo

## 💡 Conceptos Aplicados

✅ DDL, DML  
✅ Índices (Clustered, Non-Clustered, Compuestos)  
✅ Triggers (AFTER INSERT/UPDATE/DELETE)  
✅ Stored Procedures (TRY-CATCH, Transacciones)  
✅ Funciones (Escalares, Tabla)  
✅ Views  
✅ Transacciones (BEGIN, COMMIT, ROLLBACK)  
✅ Cursores  
✅ Optimización de queries  

## 🔗 Contacto

**Filani Mauro**  
📧 mauro_filani@hotmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/maurofilani)  
🐙 [GitHub](https://github.com/FMauro17)

## 📄 Licencia

Este proyecto es de código abierto con fines educativos.

---

⭐ Si te resultó útil este proyecto, dejá una estrella en el repositorio
