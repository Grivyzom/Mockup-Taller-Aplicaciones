# Sistema de Gestión Cosmofood - Mockup

## Descripción del Proyecto

Sistema integral de gestión de ventas y pedidos para el local de comida rápida **Cosmofood** ubicado en Valdivia. Este mockup presenta las interfaces de usuario diseñadas para digitalizar y optimizar los procesos de venta, gestión de inventario, delivery y atención al cliente.

## Problemática Abordada

- **Gestión manual de pedidos** que genera errores y demoras
- **Falta de control de inventario** en tiempo real
- **Ausencia de canal digital** para clientes
- **Procesos desorganizados** en cocina y delivery
- **Registros de ventas deficientes** para toma de decisiones

## Objetivos del Sistema

### Para Clientes
- Realizar pedidos online de manera rápida y segura
- Seguimiento en tiempo real del estado de pedidos
- Gestión de perfil personal y historial de compras
- Sistema de reclamos y sugerencias

### Para Administradores
- Control completo del catálogo de productos
- Gestión de repartidores y delivery
- Reportes de ventas y análisis de rendimiento
- Atención centralizada de reclamos

### Para Personal Operativo
- **POS (Cajero)**: Interfaz rápida para ventas presenciales
- **Cocina**: Panel de comandas y gestión de estados
- **Repartidores**: Vista de pedidos asignados

## Estructura del Mockup

```
\Informatica\Mockup-Taller\
├── README.md
├── index.html                 # Landing page principal
├── assets/
│   ├── css/
│   │   ├── styles.css        # Estilos principales
│   │   └── components.css    # Componentes reutilizables
│   ├── js/
│   │   ├── main.js          # JavaScript principal
│   │   └── navigation.js    # Navegación entre páginas
│   └── images/              # Recursos gráficos
├── pages/
│   ├── auth/
│   │   ├── login.html       # Inicio de sesión
│   │   └── register.html    # Registro de usuarios
│   ├── customer/
│   │   ├── catalog.html     # Catálogo de productos
│   │   ├── cart.html        # Carrito de compras
│   │   ├── checkout.html    # Proceso de pago
│   │   └── profile.html     # Perfil del cliente
│   ├── admin/
│   │   ├── dashboard.html   # Panel administrativo
│   │   ├── products.html    # Gestión de productos
│   │   ├── orders.html      # Gestión de pedidos
│   │   └── reports.html     # Reportes y estadísticas
│   ├── pos/
│   │   └── cashier.html     # Sistema POS para cajero
│   └── kitchen/
│       └── orders.html      # Panel de cocina
└── documentation/           # Documentación adicional
```

## Historias de Usuario Implementadas

### Sprint 1 - Fundación y Cuentas de Usuario
- **HU05**: Cliente - Crear cuenta en el sistema
- **HU06**: Cliente - Iniciar sesión
- **HU07**: Cliente - Restablecer contraseña
- **HU01**: Administrador - Visualizar productos
- **HU02**: Administrador - Agregar productos
- **HU03**: Administrador - Desactivar productos
- **HU04**: Administrador - Modificar productos

### Sprint 2 - Ciclo de Venta y Preparación
- **HU10**: Cliente - Agregar productos al carrito
- **HU11**: Cliente - Completar transacción
- **HU24**: Cajero/Admin - Interfaz POS
- **HU25**: Cajero/Admin - Registrar pagos
- **HU26**: Cocina - Visualizar pedidos
- **HU27**: Cocina - Cambiar estado de pedidos
- **HU16**: Admin - Actualizar estado delivery
- **HU19**: Cliente - Seguimiento de pedidos
- **HU12**: Admin - Registro de ventas

### Sprint 3 - Operaciones de Delivery
- **HU13**: Admin - Gestionar repartidores
- **HU14**: Admin - Visualizar pedidos delivery
- **HU15**: Admin - Asignar repartidores
- **HU18**: Repartidor - Ver pedidos asignados
- **HU08**: Cliente - Ver datos personales
- **HU17**: Cliente - Cambiar contraseña

### Sprint 4 - Soporte y Funciones Adicionales
- **HU20**: Cliente - Ingresar reclamos
- **HU21**: Admin - Visualizar reclamos
- **HU22**: Admin - Responder reclamos
- **HU23**: Cliente - Ver historial de reclamos
- **HU09**: Cliente - Editar datos personales

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica de las páginas
- **CSS3**: Estilos y diseño responsive
- **JavaScript**: Interactividad y navegación
- **Bootstrap/Tailwind**: Framework CSS para componentes
- **Diseño Mobile-First**: Optimizado para dispositivos móviles

## Funcionalidades Clave

### Módulo de Clientes
- Registro y autenticación segura
- Catálogo de productos con búsqueda y filtros
- Carrito de compras dinámico
- Checkout con múltiples métodos de pago
- Seguimiento de pedidos en tiempo real
- Sistema de reclamos y soporte

### Módulo Administrativo
- Dashboard con métricas clave
- CRUD completo de productos
- Gestión de estados de pedidos
- Administración de repartidores
- Reportes de ventas y análisis
- Gestión centralizada de reclamos

### Módulo Operativo
- **POS**: Venta rápida para atención presencial
- **Cocina**: Panel de comandas con estados
- **Delivery**: Asignación y seguimiento de entregas

## Metodología de Desarrollo

- **Análisis de Requerimientos**: Entrevistas, cuestionarios y observación
- **Priorización**: Técnica MoSCoW (Must have, Should have, Could have)
- **Estimación**: Puntos de historia con secuencia Fibonacci
- **Sprints**: 4 sprints de 3 semanas cada uno
- **Diseño UML**: Paradigma 4+1 vistas

## Instalación y Uso

1. **Clonar o descargar** el repositorio
2. **Abrir index.html** en cualquier navegador web moderno
3. **Navegar** entre las diferentes interfaces usando los enlaces
4. **Explorar** las funcionalidades de cada módulo

## Usuarios de Prueba

### Cliente
- **Email**: cliente@cosmofood.cl
- **Contraseña**: Cliente123

### Administrador
- **Email**: admin@cosmofood.cl
- **Contraseña**: Admin123

### Cajero
- **Email**: cajero@cosmofood.cl
- **Contraseña**: Cajero123

## Datos Mock

El sistema incluye datos de prueba para:
- **Productos**: Menú variado con categorías
- **Pedidos**: Ejemplos en diferentes estados
- **Repartidores**: Personal activo e inactivo
- **Reportes**: Estadísticas simuladas

## Próximos Pasos

1. **Implementación Backend**: API REST con base de datos
2. **Integración de Pagos**: Pasarela de pagos real
3. **Notificaciones**: Push notifications y emails
4. **Analytics**: Dashboard con datos reales
5. **App Móvil**: Versión nativa para iOS/Android

## Equipo de Desarrollo

- **Francisco Alfaro**: Frontend & UX/UI
- **Ricardo Álvarez**: Backend & Database
- **Francisco Fuentealba**: Full Stack & DevOps

## Contacto

**Institución**: INACAP  
**Ramo**: Taller de Diseño y Desarrollo de Aplicaciones  
**Docente**: [Nombre del Profesor]  
**Período**: Septiembre - Noviembre 2025

---

**Cosmofood** - Digitalizando la experiencia gastronómica en Valdivia 🍔📱