# Milkking.3d
Es un landing page enfocada en promocionar articulos impresos en 3d e incentivar la compra o cotizaciones.

# MilkKing 3D — Landing Page & Catálogo Interactivo

Landing page y plataforma web interactiva diseñada para **MilkKing 3D**, un estudio especializado en diseño, prototipado y manufactura aditiva (impresión 3D). La plataforma está optimizada para la captación y conversión de clientes minoristas, mayoristas y socios comerciales (estudiantes, profesionistas y emprendedores).

---

## 📌 Tabla de Contenidos

1. [Características Principales](https://www.google.com/search?q=%23-caracter%C3%ADsticas-principales)
2. [Identidad Visual y Paleta de Colores](https://www.google.com/search?q=%23-identidad-visual-y-paleta-de-colores)
3. [Estructura del Proyecto](https://www.google.com/search?q=%23-estructura-del-proyecto)
4. [Instalación y Uso](https://www.google.com/search?q=%23-instalaci%C3%B3n-y-uso)
5. [Configuración de Imágenes Reales](https://www.google.com/search?q=%23-configuraci%C3%B3n-de-im%C3%A1genes-reales)
6. [Canales de Integración](https://www.google.com/search?q=%23-canales-de-integraci%C3%B3n)
7. [Tecnologías Utilizadas](https://www.google.com/search?q=%23-tecnolog%C3%ADas-utilizadas)

---

## 🚀 Características Principales

* **Buscador en Tiempo Real:** Filtrado dinámico de artículos por palabras clave conectado directamente con la sección del catálogo.
* **Categorías Comerciales Profesionales:**
* Coleccionables & Cultura Pop
* Diseño de Interiores & Lifestyle
* Línea Vanity & Estética Personal
* Accesorios & Cuidado de Mascotas
* Ediciones Estacionales (Halloween, Navidad, temporadas especiales)
* Prototipado & Piezas a Medida


* **Tarjetas de Producto con Prueba Social:** Indicadores de evaluación en 5 estrellas y métricas de piezas vendidas acumuladas.
* **Ficha de Detalle e Interacción Móvil:**
* Modal interactivo para inspeccionar detalles y especificaciones de la pieza.
* Botón para copiar el enlace directo al portapapeles.
* Integración con la **Web Share API** para compartir en aplicaciones de mensajería desde dispositivos móviles.


* **Programa de Socios y Mayoristas:** Formulario de contacto directo estructurado con campos de piezas solicitadas, fecha estimada de entrega y canal de contacto preferido.
* **Sección FAQ:** Acordeón interactivo con respuestas a dudas frecuentes sobre materiales, tiempos de fabricación, envíos y acabados.
* **Diseño Responsivo:** Adaptación fluida para navegación en computadoras de escritorio y experiencia tipo Web App en teléfonos inteligentes.

---

## 🎨 Identidad Visual y Paleta de Colores

La interfaz sigue los lineamientos de contraste y balance estético de la marca:

| Color | Código HEX | Rol en la Interfaz |
| --- | --- | --- |
| **Azul Marino Primario** | `#021A54` | Botones de acción principal (CTA), logotipo, títulos y encabezados |
| **Rosa Intenso (Accent)** | `#FF85BB` | Badges de descuento, microinteracciones y estados hover |
| **Rosa Suave** | `#FFCEE3` | Fondos de realce, chips secundarios y tarjetas destacadas |
| **Gris Neutro** | `#F5F5F5` | Fondo base de la plataforma para lectura limpia |

---

## 📂 Estructura del Proyecto

```text
milkking-3d/
│
├── index.html        # Estructura principal y maquetado de la landing page
├── css/
│   └── styles.css    # Reglas de estilo, variables de color y diseño responsivo
├── js/
│   └── app.js        # Lógica del buscador, filtros, modal, Web Share API y acordeón
└── img/
    ├── logo.png      # Logotipo oficial MilkKing 3D
    ├── taz.png       # Fotografía Tazmanian Devil
    ├── chimuelo.png  # Fotografía Llaveros Chimuelo
    ├── marcianos.png # Fotografía Trío Aliens Toy Story
    ├── pantera.png   # Fotografía Pantera Rosa
    └── medusa.png    # Fotografía Busto Escultura Medusa

```

---

## ⚙️ Instalación y Uso

1. **Clonar o descargar el repositorio:**
```bash
git clone https://github.com/tu-usuario/milkking-3d.git
cd milkking-3d

```


2. **Ejecutar localmente:**
* Al ser un desarrollo web ligero sobre tecnologías estándar (`HTML5`, `CSS3` y `JavaScript ES6+`), no requiere la instalación previa de gestores de dependencias ni compiladores.
* Abre directamente el archivo `index.html` en cualquier navegador web moderno, o utiliza extensiones de servidor local como **Live Server** en VS Code.



---

## 🖼️ Configuración de Imágenes Reales

Para vincular tus archivos fotográficos locales en lugar de las ilustraciones vectoriales por defecto:

1. Coloca tus imágenes dentro de la carpeta `img/`.
2. Abre el archivo de datos en `js/app.js` (o en la sección de scripts de `index.html`) y actualiza la propiedad `image` de cada artículo con su ruta relativa:

```javascript
const products = [
  {
    id: 1,
    name: "Figura Tazmanian Devil Colección",
    category: "coleccionables",
    image: "./img/taz.png", // Reemplaza aquí tu ruta local
    price: 320,
    rating: 5.0,
    sales: 142
  },
  // ... demás productos
];

```

---

## 📲 Canales de Integración

* **WhatsApp Business:** Conexión directa al número `+52 55 2081 0586` mediante el esquema `wa.me`, configurado con el mensaje predefinido:
> *"Hola te escribo para cotizarte mi articulo impreso en 3D, estoy buscando..."*


* **Instagram Oficial:** Redirección directa al perfil [@milkking.3d](https://www.instagram.com/milkking.3d/).
* **Mercado Libre:** Accesos directos para compras gestionadas con garantía de entrega y meses sin intereses.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura optimizada para accesibilidad y posicionamiento SEO local.
* **CSS3 Moderno:** Flexbox, CSS Grid, variables personalizadas (`CSS Custom Properties`) y media queries para breakpoints móviles.
* **JavaScript (Vanilla ES6+):** Manipulación dinámica del DOM, gestión de eventos de búsqueda en vivo y consumo de la Web Share API nativa.
