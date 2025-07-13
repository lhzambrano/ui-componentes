# Kit de Componentes UI (HTML + CSS)

Este proyecto como para de la Actividad 5, contiene un conjunto de componentes UI reutilizables y accesibles construidos con HTML y CSS moderno.

## 📁 Estructura del proyecto

```
ui-componentes/
├── componentes/       # Componentes UI (botones, tarjetas, modales, etc.)
├── styles/           # Variables globales y estilos base
├── index.html        # Página demo con ejemplos de cada componente
└── README.md         # Guía de uso
```

## ✅ Componentes incluidos

- Botones (Primario, Secundario, Deshabilitado)
- Tarjetas de contenido
- Campos de formulario (inputs, selects, checkboxes)
- Navbar responsivo
- Modal (ventana emergente)
- Tooltip
- Tabs (pestañas con radio buttons)

## 🎨 Guía de estilos

- **Colores**: definidos en `styles/variables.css` como variables `--color-*`.
- **Tipografía**: base con `Segoe UI`, puede cambiarse desde `--font-base`.
- **Espaciado y Bordes**: controlados mediante `--spacing`, `--radius` y `--shadow`.

## 🧑‍💻 Cómo usar

1. Clona o descarga este repositorio.
2. Abre `index.html` en tu navegador.
3. Revisa el código fuente para reutilizar componentes en tus proyectos.

### 🧩 Ejemplo de inclusión

```html
<link rel="stylesheet" href="./styles/variables.css">
<link rel="stylesheet" href="./styles/base.css">
<link rel="stylesheet" href="./componentes/buttons.css">
```

## 📱 Diseño responsivo

- Se utilizan `flexbox` y `media queries` para asegurar compatibilidad móvil.
- Navbar y tarjetas se adaptan al ancho de la pantalla.
- Modal centrado y adaptable.

## ♿ Accesibilidad

- Etiquetas `<label>` correctamente asociadas a campos.
- Navegación de teclado para modales y tabs.
- Tooltips accesibles con `:hover`.

---

Desarrollado por [Luis Zambrano] - 2025
