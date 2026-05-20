# TechFix - Sitio Web de Servicio Técnico

## Descripción
Sitio web profesional para la empresa TechFix, especializada en reparación y mantenimiento de computadoras de escritorio y portátiles.

## Estructura de Archivos

```
frtend-sum2D-ignacio-veliz/
├── index.html          # Página principal
├── ingreso.html        # Página de formulario para ingresar equipos
├── style.css           # Estilos CSS (responsive)
├── script.js           # Funcionalidades JavaScript
├── assets/
│   └── images/         # Carpeta para imágenes (hero image, etc.)
└── prompts.txt         # Notas y prompts del proyecto
```

## Características Principales

### 📱 Secciones del Sitio

1. **Navbar Sticky**
   - Logo y nombre de la empresa a la izquierda
   - Links de navegación: Inicio, Servicios, Precios, Nosotros
   - Botón "Ingresar equipo" con color de acento
   - Menú hamburguesa responsivo para móviles

2. **Sección Hero**
   - Imagen de fondo sobre reparación de PCs
   - Título principal "TechFix"
   - Slogan: "Tu solución integral en reparación de computadoras"
   - Botón "Ingresar mi equipo" que lleva a ingreso.html

3. **Indicadores de Confianza**
   - 5 Años de Experiencia
   - Garantía Escrita
   - Diagnóstico Gratuito
   - Tarjetas con iconos y efectos hover

4. **Sección de Servicios**
   - 8 servicios en tarjetas:
     - Reparación de PC de Mesa
     - Reparación de Portátil
     - Limpieza y Mantenimiento
     - Instalación de Sistema Operativo
     - Soporte Remoto
     - Venta de Repuestos
     - Cambio de Pantalla
     - Cambio de Teclado
   - Grilla responsiva (3+ columnas en desktop, 1 en móvil)
   - Información de tiempo estimado de trabajo

5. **Marcas Atendidas**
   - HP, Lenovo, Apple, Asus, Acer, Dell
   - Tarjetas con efectos hover suave

6. **Tabla de Precios**
   - Tabla HTML estiizada con CSS
   - Columnas: Servicio, Precio Desde, Tiempo Estimado
   - Cabecera con fondo degradado
   - Filas alternadas con fondo claro/oscuro
   - Efectos hover en filas

7. **Testimonios**
   - 3 testimonios de clientes
   - Nombre, servicio recibido, comentario
   - Calificación en estrellas (5 estrellas)
   - Tarjetas con efectos hover

8. **Footer**
   - Logo y nombre de la empresa
   - Horarios presencial y remoto
   - Dirección, email, teléfono, WhatsApp
   - Links a redes sociales
   - Copyright © 2026

### 🎨 Estilos CSS

#### Variables de Color
- **Azul Oscuro**: `#003d7a` (primario)
- **Gris**: `#6b7280` (secundario)
- **Blanco**: `#ffffff` (fondo)
- **Rojo/Rosa**: `#ff6b6b` (acento)

#### Tipografías
- **Títulos**: Montserrat (Google Fonts) - Moderna y robusta
- **Cuerpo**: Inter (Google Fonts) - Legible y clara

#### Características
- Transiciones suaves en todos los elementos interactivos
- Efectos hover en tarjetas de servicios y testimonios
- Bordes con gradientes en tarjetas
- Sombras sutiles para profundidad
- Animaciones de entrada fade-in-up

### 📱 Responsive Design

- **Desktop (> 768px)**: Grillas con 3+ columnas
- **Tablets (768px)**: Grillas con 2 columnas, fuentes reducidas
- **Móviles (< 480px)**: 
  - 1 columna para todos los elementos
  - Menú hamburguesa activado
  - Tabla de precios horizontal con scroll
  - Fuentes reducidas para mejor legibilidad

### 🔗 Página de Ingreso de Equipo (ingreso.html)

Formulario completo con campos:
- Nombre Completo (requerido)
- Email (requerido)
- Teléfono (requerido)
- WhatsApp
- Tipo de Equipo (dropdown)
- Marca del Equipo (dropdown)
- Modelo/Referencia
- Descripción del Problema (textarea)
- Servicio Requerido (dropdown)
- Urgencia (dropdown)

Características:
- Estilos consistentes con index.html
- Validación HTML5
- Efectos focus en inputs
- Mismo navbar y footer para coherencia
- Diseño responsivo

## 🚀 Instrucciones de Uso

1. **Agregar Imagen Hero**
   - Guardar imagen en `assets/images/hero-pc-repair.jpg`
   - Tamaño recomendado: 1920x600px (mínimo)

2. **Personalizar Contenido**
   - Editar precios en la tabla
   - Actualizar horarios en el footer
   - Cambiar datos de contacto (email, teléfono, dirección)
   - Actualizar testimonios con clientes reales

3. **Procesar Formulario**
   - El formulario actual muestra un alert al enviar
   - Para procesar datos reales, conectar con backend PHP, Node.js, etc.
   - O usar servicios como Formspree, EmailJS, Google Forms

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos modernos con variables CSS, Flexbox y Grid
- **JavaScript**: Interactividad y menú hamburguesa
- **Font Awesome**: Iconos
- **Google Fonts**: Tipografías

## ✨ Mejoras Futuras Recomendadas

- Integración con backend para procesar formularios
- Galería de trabajos realizados
- Blog o sección de noticias
- Sistema de reservas en línea
- Chat de atención al cliente
- Optimización SEO adicional
- Integración con redes sociales
- Analytics y tracking
- Certificados de seguridad HTTPS
- Base de datos para testimonios y precios dinámicos

## 📄 Compatibilidad

- ✅ Chrome (versiones modernas)
- ✅ Firefox (versiones modernas)
- ✅ Safari (versiones modernas)
- ✅ Edge (versiones modernas)
- ✅ Navegadores móviles iOS/Android

---

**Última actualización**: Mayo 2026
**Versión**: 1.0
