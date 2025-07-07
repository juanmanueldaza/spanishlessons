# Clases de Español con Juan

Un espacio para aprender español de forma personalizada, creativa y cercana. Clases individuales y grupales con enfoque adaptado a cada estudiante.

> **📁 Parte del Ecosistema daza.ar**: Este repositorio es parte del [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) entorno de desarrollo. Para la configuración de desarrollo local, flujo de trabajo unificado y documentación inter-sitios, consulta el [repositorio principal](https://github.com/juanmanueldaza/daza.ar-env).

## 🌐 Sitio en Vivo

Visita las clases de español en: **[spanishlessons.daza.ar](https://spanishlessons.daza.ar)**

## ✨ Características

- 🇪🇸 **Enfoque Personalizado** - Adaptado a intereses individuales
- 🗣️ **Conversación Dinámica** - Práctica oral desde el primer día
- 📚 **Metodología Flexible** - Individual, grupal o talleres de conversación
- 🎨 **Contenido Creativo** - Uso de arte, música, tecnología y cultura
- 🌍 **Modalidad Híbrida** - Presencial en Buenos Aires u online
- 📱 **Responsive** - Perfecto en todos los dispositivos
- 📝 **Contenido Dinámico** - Contenido desde archivos markdown remotos
- 🧭 **Navegación Integrada** - Usa el componente navbar de daza.ar

## 🎯 Destinatarios

- **👶 Principiantes** - Que quieren comenzar desde cero
- **🗣️ Conversadores** - Que buscan mejorar fluidez y pronunciación
- **📖 Creativos** - Escritores, artistas que desean expresarse con precisión
- **🌎 Extranjeros** - Que viven en Argentina o Latinoamérica
- **💼 Profesionales** - Que requieren español técnico o formal

## 🧩 Metodología

- **Personalización** - Enfoque según intereses: arte, tecnología, cultura, negocios
- **Actividades Dinámicas** - Juegos, simulaciones, lecturas, escritura creativa
- **Contexto Real** - Uso del idioma desde el primer día
- **Materiales Digitales** - Textos, videos, ejercicios interactivos

## 📅 Modalidades

### 🌱 Clases Individuales
- Ritmo y enfoque 100% adaptado
- Atención personalizada
- Flexibilidad de horarios

### 🤝 Clases Grupales
- Aprendizaje colaborativo
- Intercambio entre estudiantes
- Ambiente motivador

### 💬 Taller de Conversación
- Práctica oral intensiva
- Temas variados y actuales
- Ideal para intermedios y avanzados

## 🕒 Disponibilidad

- **📅 Días**: Lunes a viernes
- **⏰ Horarios**: 19:00 a 21:00 hs
- **📍 Modalidad**: Presencial (Buenos Aires) o virtual
- **👥 Formato**: Individual o grupal

## 🏗️ Arquitectura

Este sitio usa una **arquitectura de módulos remotos**:

- **Contenido**: Importado desde archivos markdown de [data.daza.ar](https://data.daza.ar/md/)
- **Navegación**: Usa el componente [navbar.daza.ar](https://navbar.daza.ar)
- **Procesamiento Markdown**: Usa el módulo [mdsite.daza.ar](https://mdsite.daza.ar/mdsite.js)
- **Generación PDF**: Funcionalidad de exportación integrada

## 🚀 Stack Tecnológico

- **HTML5** - Estructura de marcado semántico
- **CSS3** - Estilado moderno con acentos de colores españoles
- **JavaScript Vanilla** - Módulos ES6
- **Módulos Remotos** - Componentes compartidos del ecosistema daza.ar
- **GitHub Pages** - Hosting estático con dominio personalizado

## 📁 Estructura de Archivos

```
spanishlessons/
├── CNAME          # Configuración de dominio personalizado
├── index.html     # Archivo HTML principal
└── README.md      # Este archivo
```

## 🛠️ Desarrollo

### Desarrollo Local

Usa el [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) entorno de desarrollo:

```bash
# Clona el entorno de desarrollo
git clone https://github.com/juanmanueldaza/daza.ar-env.git
cd daza.ar-env

# Configura todos los sitios (incluyendo este)
./setup.sh

# Inicia los servidores de desarrollo
./dev.sh

# El sitio de clases de español estará disponible en:
# http://spanishlessons.local:3009
```

### Gestión de Contenido

El contenido se gestiona centralmente en el [repositorio data](https://github.com/juanmanueldaza/data):

1. Edita `spanish-lessons.md` en el repositorio data
2. Los cambios se reflejan automáticamente en el sitio en vivo
3. No se requiere despliegue para actualizaciones de contenido

### Despliegue

Despliegue automatizado vía GitHub Pages:

```bash
# Despliegue manual (si es necesario)
npm run deploy
```

## 🎨 Personalización

### Estilos

Usa propiedades CSS personalizadas con acentos españoles:

```css
:root {
  --spanish-accent: #c41e3a;
  --spanish-gold: #ffc72c;
  --window-bg: #fff;
  --window-border: #e1e4e8;
  --text-primary: #23232e;
  --link: #0366d6;
  --link-hover: #0056b3;
}
```

### Secciones de Contenido

Las clases de español muestran:

- **Disponibilidad** - Horarios y modalidades
- **Destinatarios** - Perfiles de estudiantes
- **Metodología** - Enfoque pedagógico
- **Modalidades** - Tipos de clases disponibles
- **Testimonios** - Experiencias de estudiantes
- **Contacto** - Información para reservas

## 🔧 Configuración

La configuración automática incluye:

- **Navbar**: Enlaces de contacto profesional
- **Exportación PDF**: Optimizado para impresión
- **Carga de Contenido**: Procesamiento markdown remoto
- **Accesibilidad**: Cumplimiento completo WCAG
- **SEO**: Meta tags y datos estructurados
- **Temas Españoles**: Colores y elementos visuales de la bandera española

## 🏗️ Integración con el Ecosistema

Este sitio de clases de español es parte del **ecosistema daza.ar**:

- **🛠️ Entorno de Desarrollo**: [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) - Configuración unificada de desarrollo
- **📋 Contribuciones**: Sigue el flujo de trabajo de branches en [daza.ar-env/CONTRIBUTING.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
- **🎯 Issues & Features**: Usa la plantilla [feature_improvement.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md)
- **🏗️ Arquitectura**: Ver [documentación de despliegue](https://github.com/juanmanueldaza/daza.ar-env/blob/main/docs/DEPLOYMENT.md)

### Sitios Relacionados

- **📄 Sitio CV**: [cv.daza.ar](https://cv.daza.ar) - Currículum completo detallado
- **📋 One Pager**: [onepager.daza.ar](https://onepager.daza.ar) - Resumen profesional
- **🏠 Página de Inicio**: [start.daza.ar](https://start.daza.ar) - Dashboard personal
- **🧭 Navbar**: [navbar.daza.ar](https://navbar.daza.ar) - Componente de navegación
- **📝 Mdsite**: [mdsite.daza.ar](https://mdsite.daza.ar) - Utilidades de procesamiento Markdown
- **📊 Data**: [data.daza.ar](https://data.daza.ar) - Repositorio de contenido
- **🖼️ Wallpapers**: [wallpapers.daza.ar](https://wallpapers.daza.ar) - Colección de fondos de pantalla
- **🧪 Laboratorio**: [laboratoriodeprogramacioncreativa.daza.ar](https://laboratoriodeprogramacioncreativa.daza.ar) - Laboratorio de programación creativa

## 👨‍🏫 Profesor

**Juan Manuel Daza** - Desarrollador Full Stack con formación en literatura y gestión cultural.

Con experiencia en periodismo musical y una perspectiva multidisciplinaria única, Juan Manuel combina la enseñanza del español con elementos creativos y culturales. Su enfoque personalizado permite que cada estudiante desarrolle sus habilidades lingüísticas de acuerdo a sus intereses específicos.

## 💬 Testimonios

> *"Las clases con Juan son un espacio para aprender con alegría. No sólo aprendí español, sino que me sentí parte de una cultura."*
> — Charlotte, Francia

> *"Juan adapta todo a tus intereses. Yo soy programador y aprendí vocabulario técnico, pero también mejoré mi conversación cotidiana."*
> — Lucas, Brasil

## 📱 Compatibilidad de Navegadores

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Navegadores móviles con diseño responsive

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor usa el entorno de desarrollo unificado:

1. Usa [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) para la configuración de desarrollo
2. Sigue las [pautas de contribución](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
3. Usa la [plantilla de features](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md) para nuevas características

### Contribuciones de Contenido

- **Contenido de Clases**: Edita `spanish-lessons.md` en el [repositorio data](https://github.com/juanmanueldaza/data)
- **Características del Sitio**: Contribuye a este repositorio o módulos compartidos
- **Diseño**: Sugiere mejoras UX/UI
- **Metodología**: Propón nuevas actividades o enfoques pedagógicos

## 👤 Autor

**Juan Manuel Daza**

- Website: [daza.ar](https://daza.ar)
- GitHub: [@juanmanueldaza](https://github.com/juanmanueldaza)
- LinkedIn: [juanmanueldaza](https://www.linkedin.com/in/juanmanueldaza)
- Email: juanmanueldaza@gmail.com

## 📄 Licencia

Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">
  <p>Hecho con ❤️ como parte del <a href="https://github.com/juanmanueldaza/daza.ar-env">ecosistema daza.ar</a></p>
  <p>
    <a href="https://spanishlessons.daza.ar">Sitio en Vivo</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env">Entorno de Desarrollo</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env/issues">Reportar Issue</a>
  </p>
</div>