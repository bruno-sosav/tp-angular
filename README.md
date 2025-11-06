# 🎓 Sistema de Gestión Académica - Angular

Una aplicación web desarrollada en Angular para la administración completa de estudiantes, con interfaz minimalista y operaciones CRUD.

## ✨ Características Principales

- **🖥️ Interfaz Minimalista**: Diseño limpio y moderno con paleta de colores negro y celeste
- **📱 Diseño Responsive**: Compatible con dispositivos móviles y tablets
- **🔧 CRUD Completo**: Crear, visualizar, editar y eliminar registros de estudiantes
- **⚡ Angular 17**: Desarrollado con la última versión del framework
- **🎨 Estilo Visual**: Tipografía clara, espacios bien definidos y efectos sutiles
- **📊 Backend Simulado**: JSON Server para desarrollo y testing

## 🛠️ Stack Tecnológico

- **Frontend**: Angular 17, TypeScript, HTML5, CSS3
- **Estilos**: CSS Variables, Diseño minimalista, Animaciones CSS
- **API**: JSON Server para simulación de backend
- **Fuentes**: Google Fonts (Inter)
- **Iconografía**: Emojis para mejor experiencia visual

## 🚀 Configuración y Ejecución

### Prerrequisitos
- Node.js (versión 18 o superior)
- npm
- Git

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/bruno-sosav/tp-angular.git

# Navegar al directorio
cd tp-angular

# Instalar dependencias
npm install
```

### Ejecución

```bash
# Terminal 1 - Servidor de datos
npx json-server --watch db.json --port 3001

# Terminal 2 - Servidor de Angular
ng serve

# La aplicación estará disponible en: http://localhost:4200
```

## 📋 Funcionalidades Implementadas

### ✅ Completadas
- Listado de estudiantes con diseño minimalista
- Formulario de registro de nuevos estudiantes
- Edición en tiempo real de información estudiantil
- Eliminación segura con diálogo de confirmación
- Interfaz adaptable a diferentes tamaños de pantalla
- Validación de campos obligatorios
- Manejo robusto de errores
- API REST simulada para desarrollo

## 🎯 Estructura de Datos

Cada estudiante contiene:
- **DNI** (Documento Nacional de Identidad)
- **Nombre** y **Apellido**
- **Correo Electrónico**
- **Cohorte** (Promoción o generación)
- **Estado** académico
- **Género**
- **Dirección** personal
- **Teléfono** de contacto

## 🎨 Características de Diseño

- **Minimalismo**: Espacios limpios y contenido bien organizado
- **Paleta de Colores**: Negro como base con acentos celestes
- **Tipografía**: Fuente Inter para máxima legibilidad
- **Navegación Intuitiva**: Flujo claro entre secciones
- **Feedback Visual**: Estados interactivos bien definidos
- **Accesibilidad**: Contraste adecuado y navegación por teclado

## 👨‍💻 Autor

**Bruno Villamón**  
GitHub: [@bruno-sosav](https://github.com/bruno-sosav)

## 📄 Licencia

Este proyecto es de código abierto y se distribuye bajo la Licencia MIT.

---

*Desarrollado como trabajo práctico de Angular - Gestión de Estudiantes*
