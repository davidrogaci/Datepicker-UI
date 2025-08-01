# Datepicker UI Component

Un componente de selector de fecha moderno y responsivo, desarrollado únicamente con HTML y CSS puro. Ideal para integrarlo en formularios, dashboards o cualquier aplicación web que requiera selección de fechas sin depender de JavaScript.

[![Project](https://roadmap.sh/projects/datepicker-ui)](https://roadmap.sh/projects/datepicker-ui)

---

## 🧩 Características

- Diseño simple, limpio y responsive
- Totalmente funcional sin JavaScript
- Interfaz visual de calendario estilo datepicker
- Input estilizado con efecto focus
- Navegación de calendario simulada (estática por ahora)
- Estilos personalizables con CSS
- Compatible con todos los navegadores modernos

---

## 🚀 Cómo usar

1. Cloná este repositorio o descargá los archivos ZIP
2. Abrí `index.html` en tu navegador local
3. Editá el archivo `index.html` para personalizar el texto, íconos o layout
4. Modificá `style.css` para adaptar estilos, colores o tipografías
5. (Opcional) Subí los archivos a tu servidor o GitHub Pages para hacer la demo pública

---

## 🔧 Personalización

- **Fecha actual:** Actualmente el calendario es estático, representando **Julio 2025**. Podés cambiar el mes/estructura manualmente.
- **Días del mes:** Los días están distribuidos en una grilla (`.days`) y el primer día está alineado al miércoles (día 3).
- **Iconos:** El ícono del calendario se encuentra en `assets/icons/calendar.svg`. Reemplazalo por tu propio ícono si lo deseás.
- **Tipografía:** Usa [Rubik](https://fonts.google.com/specimen/Rubik), importada desde Google Fonts.
- **Hover y focus:** Estilos interactivos visuales con `box-shadow` y `hover` suaves.

---

## 📁 Estructura del Proyecto

```
datepicker-ui/
├── assets/
│   └── icons/
│       └── calendar.svg     # Ícono del calendario
├── index.html               # Estructura HTML del componente
├── style.css                # Estilos y diseño del calendario
└── README.md                # Este archivo
```

---

## 🧪 Ejemplo de implementación

```html
<section class="calendar-header">
  <input type="text" id="datepicker" placeholder="dd /mm/ yyyy" />
  <a href="./index.html" target="_blank">
    <img src="./assets/icons/calendar.svg" alt="calendar icon" />
  </a>
</section>
```

---

## 📜 Licencia

Este proyecto está bajo la [Licencia Apache](LICENSE). Podés usarlo, modificarlo y distribuirlo libremente bajo los términos de dicha licencia.

---

## 🤝 Contribuciones

¿Querés mejorar este componente? ¡Las contribuciones son bienvenidas!
Abrí un `issue` o mandá un `pull request` con sugerencias, mejoras o features como navegación de meses, integración con JS, etc.

---

Hecho con ❤️ por [David Rogaci](https://github.com/davidrogaci)
