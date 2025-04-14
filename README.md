# **Actividad0 - SofiaKalpin**  
**Django Tutorial (Partes 1 a 4)**

Este repositorio contiene el código correspondiente al tutorial de Django, cubriendo desde la creación del proyecto hasta la implementación de vistas genéricas y un sistema de votación.

Puedes seguir el tutorial completo en la documentación oficial de Django:  
**[Django 5.0 Tutorial - Parte 1](https://docs.djangoproject.com/es/5.0/intro/tutorial01/)**

---

## **Requisitos**

Asegúrate de tener instalados los siguientes programas:

- **Python 3**: [Descargar](https://www.python.org/downloads/)
- **Django 5**: [Descargar](https://www.djangoproject.com/download/)

---

## **Commits Realizados**

### **Parte 1: Creación del Proyecto y la Aplicación**
- **[1.1]** Creación del proyecto `mysite`
- **[1.2]** Creación de la app `polls`

### **Parte 2: Configuración de la Base de Datos y Modelos**
- **[2.0]** Configuración de SQLite y migraciones
- **[2.1]** Definición de los modelos `Question` y `Choice`

### **Parte 3: Implementación de Vistas Básicas**
- **[3.0]** Implementación de vistas básicas
- **[3.1]** Uso de templates para vistas

### **Parte 4: Sistema de Votación y Vistas Genéricas**
- **[4.0]** Implementación del sistema de votación
- **[4.1]** Uso de vistas genéricas para simplificar el código

---

## **Ejecución del Proyecto**

Para ejecutar el proyecto, sigue estos pasos:

```bash
python manage.py migrate
python manage.py runserver
```
Se accede en: http://localhost:8000/polls/1/
