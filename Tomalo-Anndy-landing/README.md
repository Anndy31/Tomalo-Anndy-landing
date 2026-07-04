# FleetTrack Pro — Landing Page

**Plataforma empresarial de gestión de flotas y transporte**

## Información del estudiante

| Campo | Detalle |
|-------|---------|
| **Estudiante** | Anndy Ismael Tomaló Quinllín |
| **Tema asignado** | Plataforma empresarial de gestión de flotas y transporte |
| **Asignatura** | Fundamentos Web — NRC 30875 |
| **Docente** | Ing. Gabriel Gustavo Narváez |
| **Universidad** | ESPE — Sede Santo Domingo |

---

## Descripción del proyecto

**FleetTrack Pro** es una landing page profesional desarrollada para una empresa ficticia de gestión de flotas vehiculares. La página presenta los servicios, planes empresariales y datos de contacto de la compañía, con un diseño responsive adaptado a dispositivos móviles, tabletas y computadoras de escritorio.

La landing page comunica de forma clara los servicios de monitoreo GPS, gestión de conductores y reportes estratégicos, dirigida a empresas de transporte, logística y distribución en Ecuador.

---

## Vista previa

![Vista previa de FleetTrack Pro](img/captura-principal.png)

> *Reemplazar con captura real al finalizar el desarrollo.*

---

## Tecnologías utilizadas

- **HTML5** — estructura semántica
- **CSS3** — estilos externos modulares con variables CSS
- **Bootstrap 5.3** — sistema de grillas, componentes y utilidades
- **Bootstrap Icons 1.11** — biblioteca de iconos
- **Git** — control de versiones
- **GitHub Pages** — publicación del proyecto

---

## Estructura del proyecto

```
tomaló-anndy-landing/
│
├── index.html               ← Página principal (única)
│
├── css/
│   ├── estilos.css          ← Variables CSS, tipografía y estilos generales
│   ├── componentes.css      ← Tarjetas, botones, formularios, testimonios, footer
│   └── responsive.css       ← Media queries mobile first (768px, 992px, 1366px)
│
├── img/
│   ├── logo.png             ← Logotipo de la empresa
│   ├── hero.jpg             ← Imagen principal del hero
│   ├── servicio-01.jpg      ← Imagen servicio: Monitoreo GPS
│   ├── servicio-02.jpg      ← Imagen servicio: Gestión de conductores
│   └── servicio-03.jpg      ← Imagen servicio: Reportes
│
├── docs/
│   └── informe.pdf          ← Informe técnico del proyecto
│
└── README.md                ← Este archivo
```

---

## Secciones de la landing page

1. **Header / Navbar** — menú sticky colapsable con Bootstrap
2. **Hero** — presentación principal con CTA hacia servicios
3. **Estadísticas** — +500 flotas, 12 años, 98% uptime
4. **Nosotros** — identidad, público y propuesta de valor
5. **Servicios** — 3 tarjetas Bootstrap con iconos y CTA
6. **Planes** — carrusel Bootstrap con 3 planes empresariales
7. **Testimonios** — 2 testimonios de gerentes de empresas reales
8. **Contacto** — formulario con nombre, correo, teléfono, select y textarea
9. **Aside CTA** — banner de llamada a la acción
10. **Footer** — datos de contacto, redes sociales y copyright

---

## Instrucciones para abrir el proyecto localmente

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/tomaló-anndy-landing.git
   ```

2. Navega a la carpeta del proyecto:
   ```bash
   cd tomaló-anndy-landing
   ```

3. Abre `index.html` directamente en tu navegador, o usa Live Server en VS Code.

> No requiere instalación de dependencias ni servidor backend.

---

## Enlace GitHub Pages

🌐 [Ver proyecto publicado](https://usuario.github.io/tomaló-anndy-landing/)

> *Actualizar con el enlace real al publicar en GitHub Pages.*

---

## Paleta de colores

| Color | Código | Uso |
|-------|--------|-----|
| Azul pastel | `#BED8E8` | Fondos de secciones y testimonios |
| Celeste | `#D9ECF2` | Fondos alternos, celeste del hero |
| Verde menta | `#CCE4DA` | Sección Nosotros |
| Azul pizarra | `#425C70` | Header, botones, footer, títulos |

---

## Fuentes de imágenes e iconos

### Imágenes
Las imágenes utilizadas provienen de [Unsplash](https://unsplash.com) y [Pexels](https://pexels.com), ambas de uso libre bajo licencia Creative Commons.

- Hero: Unsplash — búsqueda "fleet management dashboard"
- Servicios: Unsplash — búsqueda "gps tracking", "truck driver", "data analytics"

### Iconos
- [Bootstrap Icons v1.11](https://icons.getbootstrap.com/) — licencia MIT, uso libre

---

## Breakpoints responsive probados

| Tamaño | Dispositivo |
|--------|-------------|
| 375px | iPhone SE |
| 768px | iPad |
| 1366px | Laptop estándar |
