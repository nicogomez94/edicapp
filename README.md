# ServiciosHogar - Marketplace de Servicios para el Hogar

Un prototipo web responsivo para una aplicación de servicios para el hogar estilo marketplace que conecta clientes con profesionales verificados.

## 🏠 Características Principales

### Para Clientes
- **Búsqueda de servicios** por categoría y ubicación
- **Registro e inicio de sesión** simple y seguro
- **Panel de usuario** con historial de solicitudes
- **Formulario de solicitudes** con descripción e imágenes
- **Gestión de pagos** y métodos de pago
- **Sistema de calificaciones** para profesionales

### Para Profesionales
- **Panel de operario** con trabajos asignados
- **Listado de oportunidades** de trabajo disponibles
- **Subida de fotos** al completar trabajos
- **Sistema de reseñas** y calificaciones recibidas
- **Seguimiento de ganancias** y estadísticas

## 🎨 Diseño

- **Responsivo**: Adaptable a móviles, tablets y escritorio
- **Moderno**: CSS Grid y Flexbox para layouts flexibles
- **Accesible**: Colores con buen contraste y navegación intuitiva
- **Profesional**: Paleta de colores azules y grises que inspiran confianza

## 🛠️ Tecnologías

- **HTML5** semántico y accesible
- **CSS3** moderno con variables CSS y diseño responsivo
- **JavaScript ES6+** para interactividad
- **Fuentes Google** (Inter) para tipografía moderna

## 📱 Páginas Incluidas

1. **`index.html`** - Página principal con categorías y búsqueda
2. **`register.html`** - Registro para clientes y profesionales
3. **`login.html`** - Inicio de sesión con acceso demo
4. **`panel-usuario.html`** - Dashboard del cliente
5. **`panel-operario.html`** - Dashboard del profesional

## 🚀 Cómo usar

1. **Abrir el proyecto**: Simplemente abre `index.html` en tu navegador
2. **Navegar**: Explora las diferentes páginas usando el menú
3. **Modo demo**: Usa los botones demo en login para acceder a los paneles
4. **Responsivo**: Redimensiona la ventana para ver el diseño adaptativo

## 📋 Funcionalidades Implementadas

### Generales
- ✅ Navegación responsive con menú hamburguesa
- ✅ Búsqueda de servicios por categoría
- ✅ Formularios de registro e inicio de sesión
- ✅ Diseño mobile-first

### Panel Cliente
- ✅ Resumen de solicitudes activas
- ✅ Historial completo de trabajos
- ✅ Formulario para nuevas solicitudes
- ✅ Gestión de métodos de pago
- ✅ Sistema de tabs navegable

### Panel Profesional
- ✅ Dashboard con estadísticas clave
- ✅ Listado de trabajos asignados
- ✅ Nuevas oportunidades de trabajo
- ✅ Modal para subir fotos de trabajos
- ✅ Sistema de calificaciones y reseñas
- ✅ Seguimiento de ganancias

### Interactividad
- ✅ Validación básica de formularios
- ✅ Navegación entre tabs
- ✅ Modales funcionales
- ✅ Notificaciones y alertas
- ✅ Previsualización de imágenes

## 🎯 Casos de Uso

### Como Cliente
1. Registro en la plataforma
2. Búsqueda de servicios por categoría
3. Creación de solicitud con detalles y fotos
4. Recepción y comparación de propuestas
5. Seguimiento del progreso del trabajo
6. Calificación del profesional

### Como Profesional
1. Registro como prestador de servicios
2. Búsqueda de oportunidades de trabajo
3. Envío de propuestas a clientes
4. Ejecución y documentación del trabajo
5. Recepción de pagos y calificaciones

## 🎨 Paleta de Colores

- **Primario**: `#2563eb` (Azul profesional)
- **Secundario**: `#64748b` (Gris neutro)
- **Acento**: `#3b82f6` (Azul claro)
- **Éxito**: `#059669` (Verde)
- **Advertencia**: `#d97706` (Naranja)
- **Error**: `#dc2626` (Rojo)
- **Fondo**: `#f8fafc` (Gris muy claro)

## 📱 Breakpoints Responsivos

- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: > 768px

## 🔮 Próximas Mejoras

- [ ] Sistema de chat en tiempo real
- [ ] Integración con mapas para ubicación
- [ ] Sistema de pagos real
- [ ] Notificaciones push
- [ ] App móvil nativa
- [ ] API backend completa
- [ ] Base de datos de usuarios y servicios
- [ ] Sistema de verificación de profesionales

## 📄 Estructura del Proyecto

```
julian-prototipo/
├── .github/
│   └── copilot-instructions.md
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── index.html
├── login.html
├── register.html
├── panel-usuario.html
├── panel-operario.html
└── README.md
```

## 💻 Desarrollo Local

Para desarrollo local, puedes usar cualquier servidor HTTP estático:

```bash
# Con Python 3
python -m http.server 3000

# Con Node.js (http-server)
npx http-server -p 3000

# Con PHP
php -S localhost:3000
```

Luego abre http://localhost:3000 en tu navegador.

## 🤝 Contribuciones

Este es un prototipo de demostración. Para contribuir:

1. Fork el proyecto
2. Crea una branch para tu feature
3. Commit tus cambios
4. Push a la branch
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

## 👥 Créditos

- **Diseño y desarrollo**: Prototipo creado para demostración
- **Iconos**: Emojis nativos para simplicidad
- **Fuentes**: Google Fonts (Inter)
- **Inspiración**: Plataformas como TaskRabbit, Thumbtack, y servicios locales

---

⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub!
