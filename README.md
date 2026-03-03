# MUPA Landing Page

Landing page oficial del Museo Paleontológico del Gobierno de San Juan - "Tierra de Gigantes".

## 🦕 Descripción

Sitio web estático desarrollado para el Museo Paleontológico de San Juan (MUPA), diseñado para proporcionar información sobre exhibiciones, visitas guiadas, investigación y contacto. La landing incluye páginas individuales accesibles mediante QR codes del sistema Magic Wall.

## 🚀 Características

- **Diseño Responsivo**: Optimizado para todos los dispositivos
- **Stack Moderno**: Tailwind CSS + HTML estático
- **SEO Optimizado**: Metadatos y estructura semántica
- **Páginas de Contenido**: Secciones específicas accesibles via QR codes
- **Navegación Intuitiva**: Experiencia de usuario fluida

## 📁 Estructura del Proyecto

```
mupa-landing-page/
├── index.html              # Landing principal
├── contenido/              # Páginas para QR codes
│   ├── trex.html          # Tyrannosaurus Rex
│   ├── megaterio.html     # Megaterio Gigante
│   ├── excavacion.html    # Excavación Paleontológica
│   ├── mapa.html          # Mapa Interactivo
│   └── puzzle.html        # Puzzle Educativo
└── README.md              # Este archivo
```

## 🌐 URLs Disponibles

### Página Principal
- `https://mupa-landing-page.vercel.app/`

### Páginas de Contenido (QR Codes)
- `https://mupa-landing-page.vercel.app/contenido/trex`
- `https://mupa-landing-page.vercel.app/contenido/megaterio`
- `https://mupa-landing-page.vercel.app/contenido/excavacion`
- `https://mupa-landing-page.vercel.app/contenido/mapa`
- `https://mupa-landing-page.vercel.app/contenido/puzzle`

## 🛠️ Stack Tecnológico

- **HTML5**: Estructura semántica
- **Tailwind CSS**: Framework de estilos (CDN)
- **Google Fonts**: Tipografía Inter
- **JavaScript Vanilla**: Interactividad básica
- **Vercel**: Hosting y deployment

## 🎨 Diseño y Branding

- **Colores Principales**:
  - Tierra: `#c5794f` (naranja terracota)
  - Óxido: `#cf5e4d` (rojo óxido)
  - Arena: `#d0b368` (amarillo arena)
- **Tipografía**: Inter (Google Fonts)
- **Estilo**: Moderno, educativo, accesible

## 📱 Secciones Principales

### index.html
- **Hero**: Presentación impactante del museo
- **Exhibiciones**: Destacados paleontológicos
- **Visitas**: Información práctica (horarios, ubicación, precios)
- **Investigación**: Proyectos científicos
- **Contacto**: Formulario y datos de contacto

### Páginas de Contenido
Cada página incluye:
- Header con navegación al index
- Hero section específico
- Contenido educativo detallado
- Footer consistente
- Enlaces relativos optimizados

## 🚀 Deployment

El sitio está deployado en Vercel con configuración automática. Para cambios:

1. Realizar modificaciones locales
2. Commitear cambios al repositorio
3. Vercel deploy automáticamente

## 📋 Requisitos

- Navegador moderno con soporte ES6+
- Conexión a internet (CDN dependencies)
- Resolución mínima: 320px (mobile)

## 🔧 Desarrollo Local

```bash
# Clonar repositorio
git clone [repository-url]

# Navegar al proyecto
cd mupa-landing-page

# Iniciar servidor local (opcional)
python -m http.server 8000
# o usar Live Server en VS Code
```

## 📊 Analytics y SEO

- Metadatos optimizados para motores de búsqueda
- Open Graph tags para redes sociales
- Estructura semántica HTML5
- Imágenes optimizadas con alt text

## 🔐 Seguridad

- No se utilizan frameworks del lado del servidor
- Dependencias externas via CDN confiables
- No se manejan datos sensibles del lado del cliente

## 🤝 Contribuciones

Para contribuir al proyecto:

1. Fork del repositorio
2. Crear branch de feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commitear cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push al branch (`git push origin feature/nueva-funcionalidad`)
5. Crear Pull Request

## 📞 Contacto

- **Museo**: `museo@unsj.edu.ar`
- **Teléfono**: `+54 264 426-0111`
- **Dirección**: Av. Ignacio de la Roza 590, San Juan

## 📄 Licencia

© 2024 Museo Paleontológico - Gobierno de San Juan. Todos los derechos reservados.

---

**Desarrollado para el Gobierno de San Juan**  
*Manteniendo viva la historia de 230 millones de años*
