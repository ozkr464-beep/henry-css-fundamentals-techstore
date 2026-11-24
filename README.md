# TechStore — Galería Responsive de Productos

## Descripción

TechStore es una galería web de seis productos tecnológicos ficticios, desarrollada como ejercicio práctico durante mi formación **Full Stack Part Time en Soy Henry**.

El proyecto tiene como objetivo aplicar los fundamentos de HTML5 y CSS3 para construir una interfaz visualmente atractiva, organizada y adaptable a diferentes tamaños de pantalla.

**Autor:** Oscar Garnica  
**Programa:** Full Stack Part Time — Soy Henry  
**Módulo:** 01 — Fundamentos del Desarrollo Web  
**Clase:** CSS Fundamentals y Diseño Visual  
**Año:** 2026

## Tecnologías utilizadas

- **HTML5:** estructura semántica de la página.
- **CSS3:** estilos, colores, tipografía y diseño visual.
- **CSS Grid:** distribución responsive de productos.
- **Flexbox:** organización interna de las tarjetas.
- **HSL y variables CSS:** administración de colores.
- **Media queries:** ajustes visuales para dispositivos móviles.

## Características principales

- Galería de seis productos tecnológicos.
- Encabezado con degradado de colores.
- Tarjetas con fotografías, títulos, descripciones y precios.
- Diseño responsive de una, dos o tres columnas.
- Efectos hover y transiciones CSS.
- Fotografías almacenadas localmente.
- Preferencias de movimiento reducido.

## Diseño responsive

La distribución fue comprobada visualmente en tres tamaños de pantalla:

| Dispositivo | Ancho | Columnas |
|---|---|---|
| Escritorio | 1200 px | 3 |
| Tableta | 768 px | 2 |
| Móvil | 390 px | 1 |

## Estructura del proyecto

```text
galeria-productos/
├── css/
│   ├── reset.css
│   └── styles.css
├── img/
├── index.html
└── README.md
```

## Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta en Visual Studio Code.
3. Abrir `index.html` en un navegador o utilizar Live Server.

No requiere dependencias externas ni instalación de paquetes.

## Validación técnica

El proyecto fue comprobado utilizando herramientas de validación web:

- **Nu HTML Checker:** sin errores ni advertencias.
- **W3C CSS Validator:** sin errores.
- **Pruebas responsive:** realizadas en 1200 px, 768 px y 390 px.

Estas comprobaciones no sustituyen una auditoría completa de accesibilidad ni pruebas en todos los navegadores.

## Aprendizajes

Durante el desarrollo de TechStore practiqué:

- Separación entre estructura HTML y presentación CSS.
- Modelo de caja y uso de `box-sizing`.
- Variables CSS y colores HSL.
- Diferencias entre CSS Grid y Flexbox.
- Adaptación automática de columnas con `minmax()` y `auto-fit`.
- Control de dimensiones y recorte de imágenes con `object-fit`.
- Validación de código HTML y CSS.

## Estado

**Ejercicio práctico completado y validado.**

Proyecto académico con productos y precios ficticios, sin funcionalidad de comercio electrónico.