# SISTEMA PETSHOP VETERINARIO


<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThHbyaVpQ62_zJ-nJdSuST5pKCtnemw2hwi85bHMaq6w&s=10" alt="Logo" style="width: 30%; max-width: 200px;">
</p>


# Pet Paradise - Landing Page & Sistema Base

## 📋 Datos Principales del Proyecto
* **Nombre de la Empresa:** Pet Paradise
* **Giro:** Venta de alimentos, accesorios/juguetes, farmacia veterinaria y servicios de peluquería canina.
* **Ubicación:** Av. Vicente Pérez Rosales #1420, Puerto Varas, Región de Los Lagos, Chile.
* **Contacto Principal:** `hola@petparadise.cl` | +56 65 299 8877
* **Tecnologías Front-End:** HTML5, Tailwind CSS (via CDN), Lucide Icons.
* **Persistencia / Backend base:** Arquitectura preparada para vinculación relacional mediante base de datos **MySQL Server**.

---

## 🗂️ Arquitectura de Carpetas y Árbol de Directorios (Tree)

El proyecto organiza sus activos estructurales, manuales técnicos de usuario y librerías internas bajo una distribución jerárquica limpia:

```text
pet-paradise-project/
│
├── index.html                   # Página de aterrizaje principal (Landing Page)
├── README.md                    # Documentación técnica del proyecto
│
├── assets/                      # Recursos visuales e imágenes estáticas
│   ├── images/
│   │   ├── logo.png             # Archivo fuente del logotipo corporativo
│   │   ├── hero-bg.jpg          # Fondo de cabecera (Vistas de Puerto Varas)
│   │   └── services/            # Fotografías para secciones específicas
│   │       ├── alimentos.jpg
│   │       ├── juguetes.jpg
│   │       ├── remedios.jpg
│   │       └── peluqueria.jpg
│   │
│   └── resources/               # Documentos e iconografía base complementaria
│       └── vector-assets/       # Vectores y SVG crudos
│
├── docs/                        # Repositorio de manuales y guías operativas
│   └── manuales/
│       ├── manual_usuario.pdf   # Guía de autogestión de stock para administradores
│       └── manual_tecnico.pdf   # Estructura del mapeo relacional de base de datos
│
└── lib/                         # Librerías y dependencias locales de reserva
    ├── tailwind/                # Backup local de hojas de estilo minificadas
    └── lucide/                  # Backup de scripts de iconografía nativa
```

---

## 🛠️ Requerimientos del Sistema
* **Servidor Web:** Apache 2.4+ o Nginx.
* **Motor de Base de Datos:** MySQL Server 8.0 o superior (o MariaDB equivalente).
* **Entorno Cliente:** Navegadores modernos con soporte completo de ES6+ (Chrome, Edge, Safari, Firefox).


