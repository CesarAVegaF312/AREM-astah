# Uso de Astah UML para Modelado de Arquitectura Empresarial

Este repositorio ya no se mantiene. La guía de instalación de Astah UML y el ejemplo del sistema de citas médicas ahora están en el repositorio de notación del curso:

**[AREM-ArchiMate → herramientas/astah_uml.md](https://github.com/CesarAVegaF312/AREM-ArchiMate/blob/main/herramientas/astah_uml.md)**

## ¿Qué es Astah UML?

## Licencia

- Diagramas de clases
- Casos de uso
- Actividades
- Secuencia
- Componentes
- Despliegue

---

## ¿Cómo descargar Astah UML para estudiantes?

1. Visita la página oficial: https://astah.net/products/astah-uml/
2. Descarga **Astah UML** (NO la versión Professional).
3. Ejecuta el instalador en tu sistema operativo (Windows, macOS, Linux).
4. Para configurar tu licencia gratuita de estudiante, sigue esta guía:  
   https://astah.net/support/set-student-license/

---

## Crear tu primer diagrama UML

### Ejemplo paso a paso: Diagrama de Clases - Sistema de Citas Médicas

**Objetivo**: Modelar un sistema simple donde un `Paciente` agenda una `Cita` con un `Médico`.

### Pasos en Astah:

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

## Recomendaciones

- Usa Astah para prácticas donde se requiere validación formal de UML.
- Complementa con herramientas como [draw.io](https://app.diagrams.net) para trabajos colaborativos o rápidos.
- Añade tus modelos en carpetas tipo `/ejemplos/` o `/proyectos/`.

---

## Estructura sugerida para este repositorio

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

## Licencia

© César Augusto Vega Fernández. Material del curso Arquitectura Empresarial, Universidad de La Sabana, bajo licencia [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).
