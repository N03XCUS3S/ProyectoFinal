# ProyectoFinal
Proyecto

---
## Frotnend

/frontend
│
├── public/
│   └── assets/
│       ├── sprites/
│       ├── backgrounds/
│       ├── sounds/
│       ├── fonts/
│       └── icons/
│
├── src/
│   ├── components/         # Componentes reutilizables UI (botones, menús, diálogos)
│   ├── scenes/             # Vistas principales: pantalla bar, gestión productos, menú principal, etc
│   ├── modules/            # Lógica de juego, helpers por funcionalidad (ej: barra empleados, inventario)
│   ├── services/           # Comunicación con backend/API, almacenamiento local
│   ├── styles/             # CSS/SCSS/archivos de estilo
│   ├── hooks/              # Hooks custom (si usas React)
│   ├── contexts/           # Contextos globales para estado (si usas React Context)
│   ├── utils/              # Utilidades varias
│   ├── index.html
│   ├── index.js (o .tsx)
│   └── index.css
│
├── package.json
└── .gitignore

---
## Backend

/backend
│
├── app/
│   ├── api/
│   │   ├── routes/         # Rutas REST relacionadas ('/users', '/products', '/orders', '/bar')
│   │   └── schemas/        # Esquemas de validación (DTOs)
│   ├── models/             # Modelos de base de datos (ORM)
│   ├── services/           # Lógica de negocio, helpers, integraciones externas
│   ├── core/               # Configuración, utilidades base (settings, middlewares)
│   ├── db/                 # Interacción con base de datos (conexiones, scripts, migraciones)
│   └── main.py (o index.js)
│
├── tests/
│   └── ...                 # Tests unitarios e integración
├── requirements.txt (o package.json)
└── README.md
