# 💻 Landing Page Personal - Maria Fernanda Moreno Acosta

Este proyecto es una **landing page personal** desarrollada con HTML5 y CSS3, diseñada para ser completamente **responsiva** y adaptarse a distintos tamaños de pantalla (dispositivos móviles, tablets y escritorios). 

Es una presentación profesional como desarrolladora Backend & Frontend en formación.

---

## ✨ Características Principales

- Diseño moderno y atractivo.
- Totalmente responsivo.
- Secciones claras: Inicio, Sobre Mí, Habilidades, Contacto.
- Colores personalizados y tipografía consistente.
- Adaptación automática de grid y botones en diferentes resoluciones.
- Navegación accesible con buenas prácticas de semántica HTML.


---

## 🧱 Estructura del Proyecto

```
/LandingPageMariaFernanda
│
├── index.html             # Página principal
├── LICENSE                # Licencia del proyecto
├── README.md              # Documentación del proyecto
├── .gitignore             # Archivos ignorados por Git
├── .vscode/               # Configuración del entorno de VS Code
│
├── _css/
│   └── style.css          # Estilos CSS personalizados
│
├── _img/
│   └── mafe.jpg           # Imagen del autor
```



## 🖼️ Secciones del Sitio

### 📌 Header (Navegación)
- Contiene un menú de navegación horizontal que se transforma en vertical en pantallas pequeñas.
- Usa `flexbox` y `media queries` para adaptarse de forma fluida.

### 💡 Sección Hero
- Presentación principal con título, descripción y botones de acción.
- Fondo con `linear-gradient` y texto centrado.
- Los botones se acomodan verticalmente en dispositivos móviles.

### 👩‍💻 Sobre Mí
- Biografía breve, estudios y experiencia.
- Layout dividido entre texto e imagen.
- Uso de `flex-wrap` para adaptarse a pantallas pequeñas.

### 🛠️ Habilidades
- Se muestra una grilla (`grid`) con tarjetas de habilidades.
- Estructura **100% responsive**:
  - 1 columna en móvil
  - 2 columnas en tablet
  - 4 columnas en escritorio

### 📞 Contacto (Footer)
- Mensaje de cierre e invitación a trabajar en conjunto.
- Botón con enlace a GitHub estilizado y adaptado a pantallas móviles.

---

## 🎨 Responsividad del CSS

El diseño responsivo se implementa mediante:

### 🔸 Variables CSS personalizadas (`:root`)
- Colores, tipografía, espaciados y breakpoints centralizados.

### 🔸 Media Queries (`@media`)
- Se ajustan paddings, tamaños de letra, dirección de `flex` o `grid`, etc.

### 🔸 Tipografía adaptativa (`clamp()`)
- Ejemplo:
  ```css
  font-size: clamp(1.75rem, 4vw, 2.5rem);

## 🔸 Grillas y Flexbox responsivas
.skills__grid cambia de 1 a 4 columnas según el ancho de pantalla.

.hero__actions, .nav__list y .about__content se reorganizan automáticamente.

## 📱 Breakpoints Utilizados
css
Copiar código
--breakpoint-sm: 640px;
--breakpoint-md: 768px;
--breakpoint-lg: 1024px;
--breakpoint-xl: 1280px;
🚀 Tecnologías Utilizadas
HTML5

CSS3 con Variables y Media Queries

Flexbox y CSS Grid


## 👤 Autora
Maria Fernanda Moreno Acosta de la ficha 3147235

## 📌 Notas Finales
Este proyecto fue creado como parte de mi portafolio personal y aprendizaje continuo de desarrollo web. Su diseño y estructura buscan mostrar no solo el contenido profesional, sino también buenas prácticas en diseño adaptable y moderno.