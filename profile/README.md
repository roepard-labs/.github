<div align="center">

# 🚀 Roepard Labs

### *Innovación en Realidad Aumentada y Educación Digital*

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![Version](https://img.shields.io/badge/version-0.0.0-orange.svg)]()
[![PHP](https://img.shields.io/badge/PHP-8.4.7-777BB4?logo=php&logoColor=white)]()
[![A-Frame](https://img.shields.io/badge/A--Frame-1.7.1-EF2D5E?logo=aframe&logoColor=white)]()

<img src="https://raw.githubusercontent.com/roepard-labs/.github/main/profile/assets/banner.png" alt="Roepard Labs Banner" width="100%" />

*Construyendo el futuro de la educación con tecnología inmersiva*

---

</div>

## 🌟 Sobre Nosotros

**Roepard Labs** es una organización dedicada al desarrollo de soluciones innovadoras que combinan **Realidad Aumentada (AR)**, **Realidad Virtual (VR)** y **tecnologías web modernas** para transformar la educación y la experiencia de aprendizaje.

Nuestro proyecto insignia, **HomeLab AR**, es una plataforma educativa inmersiva diseñada para la **UAM**, que permite a los estudiantes desplegar y gestionar servicios virtuales de homelab en entornos del mundo real.

---

## 🎯 Proyectos Principales

### 🏠 [HomeLab AR](https://github.com/roepard-labs/thepearlo_vr-website)

Aplicación de realidad aumentada inmersiva que revoluciona la forma en que los estudiantes aprenden sobre infraestructura de TI y servicios de red.

**Características principales:**
- 🥽 Experiencias VR/AR con WebXR y A-Frame
- 🔐 Sistema de autenticación robusto con roles
- 📊 Dashboard administrativo completo
- 🎨 Interfaz moderna con Bootstrap 5
- 🌐 API RESTful en PHP 8.4
- 📱 Diseño responsivo y mobile-first

### 🔧 [Backend API](https://github.com/roepard-labs/thepearlo_vr-backend)

API REST robusta construida con arquitectura MVC en PHP, diseñada para escalar y mantener.

**Stack tecnológico:**
- PHP 8.4.7 con patrón MVC
- MySQL/MariaDB 10.6+
- Nginx como servidor web
- Autenticación basada en sesiones
- Middleware de seguridad

### 🌐 [Frontend Website](https://github.com/roepard-labs/thepearlo_vr-website)

Interfaz de usuario moderna e inmersiva con las últimas tecnologías web.

**Tecnologías:**
- HTML5, CSS3, JavaScript ES6+
- A-Frame 1.7.1 para VR/AR
- Bootstrap 5 para UI responsiva
- Three.js para gráficos 3D
- jQuery, SweetAlert2, Notyf

### 🎮 [App Store VR](https://github.com/roepard-labs/thepearlo_vr-appstore)

Tienda de aplicaciones virtual en realidad aumentada (en desarrollo).

### 🔗 [Networked Experiences](https://github.com/roepard-labs/thepearlo_vr-networked)

Experiencias colaborativas multi-usuario en VR/AR (en desarrollo).

---

## 🛠️ Stack Tecnológico

<div align="center">

### Backend
![PHP](https://img.shields.io/badge/PHP-8.4.7-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-10.6+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)

### VR/AR
![A-Frame](https://img.shields.io/badge/A--Frame-1.7.1-EF2D5E?style=for-the-badge&logo=aframe&logoColor=white)
![WebXR](https://img.shields.io/badge/WebXR-API-00D4AA?style=for-the-badge)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![AR.js](https://img.shields.io/badge/AR.js-3.4.7-FF6B6B?style=for-the-badge)

</div>

---

## 🚀 Comenzar

### 📋 Requisitos Previos

```bash
# Sistema operativo
Ubuntu 22.04 LTS o superior

# Software requerido
PHP >= 8.4.7
MySQL/MariaDB >= 10.6
Nginx >= 1.18
Node.js >= 18.x (opcional)
```

### ⚡ Instalación Rápida

```bash
# 1. Clonar el repositorio principal
git clone https://github.com/roepard-labs/thepearlo_vr-website.git
cd thepearlo_vr-website

# 2. Configurar base de datos
mysql -u root -p < database/schema.sql

# 3. Configurar variables de entorno
cp .env.example .env
nano .env  # Editar con tus credenciales

# 4. Configurar Nginx
sudo cp config/nginx.conf /etc/nginx/sites-available/homelab
sudo ln -s /etc/nginx/sites-available/homelab /etc/nginx/sites-enabled/
sudo nginx -t && sudo systemctl reload nginx

# 5. Configurar permisos
sudo chown -R www-data:www-data .
sudo chmod -R 755 .

# 6. ¡Listo! Accede desde tu navegador
https://tu-dominio.com
```

### 🔐 SSL/HTTPS (Requerido para WebXR)

```bash
# Instalar Certbot
sudo apt install certbot python3-certbot-nginx

# Obtener certificado SSL
sudo certbot --nginx -d tu-dominio.com
```

---

## 📚 Documentación

Nuestra documentación completa está disponible en el [repositorio de docs](https://github.com/roepard-labs/docs):

| 📖 Sección | 📝 Descripción |
|------------|----------------|
| [**Guía de Desarrollo**](https://github.com/roepard-labs/docs/blob/main/desarrollo.md) | Instalación, configuración y comandos |
| [**API Reference**](https://github.com/roepard-labs/docs/blob/main/api.md) | Documentación completa de endpoints |
| [**Arquitectura MVC**](https://github.com/roepard-labs/docs/blob/main/mvc.md) | Patrones y mejores prácticas |
| [**Sistema de Layouts**](https://github.com/roepard-labs/docs/blob/main/LAYOUTS-ARQUITECTURA.md) | Arquitectura de vistas y componentes |
| [**Componentes VR/AR**](https://github.com/roepard-labs/docs/blob/main/componentes.md) | Documentación de componentes A-Frame |
| [**Guía de Estilos**](https://github.com/roepard-labs/docs/blob/main/guia-estilos.md) | Paleta de colores y diseño visual |

---

## 🎨 Características Destacadas

### 🥽 Experiencia VR/AR Inmersiva

```javascript
// Componentes A-Frame personalizados
AFRAME.registerComponent('gaze-activator', {
  // Activación por mirada en VR
});

AFRAME.registerComponent('surface-detector', {
  // Detección de superficies en AR
});

AFRAME.registerComponent('item-deployer', {
  // Despliegue de elementos virtuales
});
```

### 🔐 Sistema de Autenticación Robusto

- ✅ Login/registro con email, teléfono o username
- ✅ Sesiones PHP seguras con middleware
- ✅ Sistema de roles (admin, user, supervisor)
- ✅ Validación de formularios en tiempo real
- ✅ Modal de autenticación integrado
- ✅ Dashboard administrativo completo

### 🎯 Arquitectura MVC Estricta

```
📁 api/
├── 🎮 controllers/     # Manejo de HTTP y sesiones
├── ⚙️ services/        # Lógica de negocio pura
├── 🗄️ models/          # Acceso a base de datos
├── 🔀 routes/          # Rutas de API
└── 🛡️ middleware/      # Seguridad y validaciones
```

### 🎨 UI/UX Moderna

- **Bootstrap 5** para diseño responsivo
- **DataTables** para gestión de datos
- **Chart.js** para visualización
- **SweetAlert2** para alertas elegantes
- **Notyf** para notificaciones toast
- **AOS** para animaciones on scroll
- **TomSelect** para selects avanzados

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Sigue estos pasos:

### 1️⃣ Fork el Proyecto
```bash
# Fork desde GitHub
# Clonar tu fork
git clone https://github.com/tu-usuario/nombre-repo.git
cd nombre-repo
```

### 2️⃣ Crear una Rama
```bash
git checkout -b feature/nueva-caracteristica
```

### 3️⃣ Realizar Cambios
```bash
# Hacer tus cambios
git add .
git commit -m "✨ feat: añadir nueva característica"
```

### 4️⃣ Push y Pull Request
```bash
git push origin feature/nueva-caracteristica
# Crear Pull Request desde GitHub
```

### 📝 Convenciones de Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```
✨ feat: nueva característica
🐛 fix: corrección de bug
📚 docs: documentación
💄 style: cambios de estilo/formato
♻️ refactor: refactorización de código
⚡ perf: mejora de rendimiento
✅ test: añadir tests
🔧 chore: tareas de mantenimiento
```

---

## 📊 Estadísticas del Proyecto

<div align="center">

![GitHub Stars](https://img.shields.io/github/stars/roepard-labs?style=social)
![GitHub Forks](https://img.shields.io/github/forks/roepard-labs?style=social)
![GitHub Watchers](https://img.shields.io/github/watchers/roepard-labs?style=social)

</div>

---

## 🗺️ Roadmap

### 🎯 Fase 1: MVP (Actual)
- [x] Sistema de autenticación completo
- [x] Backend API RESTful
- [x] Interfaz de usuario responsiva
- [x] Componentes VR básicos
- [ ] Dashboard administrativo completo
- [ ] Testing unitario backend

### 🚀 Fase 2: Expansión
- [ ] Experiencias AR con detección de superficies
- [ ] Sistema multi-usuario en tiempo real
- [ ] App Store VR integrada
- [ ] PWA con soporte offline
- [ ] Internacionalización (i18n)

### 🌟 Fase 3: Escalabilidad
- [ ] Microservicios con Docker
- [ ] CI/CD con GitHub Actions
- [ ] Monitoreo y analytics
- [ ] Optimización de rendimiento
- [ ] Sistema de plugins

---

## 👥 Equipo

<div align="center">

| 👤 Rol | 📧 Contacto |
|--------|-------------|
| **Lead Developer** | [@roepard-labs](https://github.com/roepard-labs) |
| **Frontend Developer** | Contribuye al proyecto |
| **Backend Developer** | Contribuye al proyecto |
| **VR/AR Specialist** | Contribuye al proyecto |

</div>

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## 🌐 Enlaces Útiles

<div align="center">

[![Website](https://img.shields.io/badge/Website-roepard--labs.com-00D4AA?style=for-the-badge&logo=google-chrome&logoColor=white)](https://roepard-labs.com)
[![Documentation](https://img.shields.io/badge/Docs-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/roepard-labs/docs)
[![Discord](https://img.shields.io/badge/Discord-Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/roepard-labs)
[![Twitter](https://img.shields.io/badge/Twitter-@roepardlabs-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/roepardlabs)

</div>

---

## 💖 Agradecimientos

Agradecemos especialmente a:

- **Universidad Autonoma de Manizales** por creer en nuestro proyecto
- La comunidad de **A-Frame** por sus increíbles herramientas
- Todos los **contribuidores** que hacen esto posible
- La comunidad **open source** por inspirarnos

---

<div align="center">

### 🌟 ¡Dale una estrella al proyecto si te gusta! ⭐

**Hecho con ❤️ por Roepard Labs**

![Footer](https://raw.githubusercontent.com/roepard-labs/.github/main/profile/assets/footer.png)

</div>