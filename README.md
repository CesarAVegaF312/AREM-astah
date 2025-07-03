# Uso de Astah UML para Modelado de Arquitectura Empresarial

Este repositorio guía a estudiantes y desarrolladores en el uso de **Astah UML (versión gratuita para estudiantes)** para realizar diagramas y modelos utilizados en arquitectura de software y sistemas empresariales.

---

## 🧩 ¿Qué es Astah UML?

[Astah UML](https://astah.net/products/astah-uml/) es una herramienta de modelado visual gratuita para estudiantes, que permite crear diagramas UML como:

- Diagramas de clases
- Casos de uso
- Actividades
- Secuencia
- Componentes
- Despliegue

---

## 🧑‍🎓 ¿Cómo descargar Astah UML para estudiantes?

1. Visita la página oficial: 👉 https://astah.net/products/astah-uml/
2. Descarga **Astah UML** (NO la versión Professional).
3. Ejecuta el instalador en tu sistema operativo (Windows, macOS, Linux).
4. Para configurar tu licencia gratuita de estudiante, sigue esta guía:  
   🔗 https://astah.net/support/set-student-license/?submissionGuid=8b38f78a-ef65-4732-98fa-dc98746fd4d7

---

## 🧾 Crear tu primer diagrama UML

### ✨ Ejemplo paso a paso: Diagrama de Clases - Sistema de Citas Médicas

**Objetivo**: Modelar un sistema simple donde un `Paciente` agenda una `Cita` con un `Médico`.

### 📝 Pasos en Astah:

1. Abre Astah UML y selecciona `File → New`.
2. Crea un nuevo `Class Diagram` desde el panel izquierdo.
3. Arrastra y suelta 3 clases: `Paciente`, `Cita`, `Médico`.
4. Añade atributos como:
   - `Paciente`: nombre, correo
   - `Cita`: fecha, estado
   - `Médico`: nombre, especialidad
5. Usa `Association` para conectar:
   - `Paciente` → `Cita` (1 a muchos)
   - `Cita` → `Médico` (muchos a 1)
6. Guarda el archivo como `sistema-citas.asta`.
7. Exporta una imagen desde `File → Export Image`.

---

## 📦 Recomendaciones

- Usa Astah para prácticas donde se requiere validación formal de UML.
- Complementa con herramientas como [draw.io](https://app.diagrams.net) para trabajos colaborativos o rápidos.
- Añade tus modelos en carpetas tipo `/ejemplos/` o `/proyectos/`.

---

## 📁 Estructura sugerida para este repositorio

```
astah-modelado/
├── ejemplos/
│   ├── sistema-citas.asta
│   └── diagrama-casos-uso.asta
├── recursos/
│   └── plantillas/
├── README.md
```

---

## ✅ Licencia

Este repositorio es de uso académico bajo licencia MIT. Los modelos fueron creados para fines educativos en el marco del curso de Arquitectura Empresarial.
