# Milkking.3d
Es un landing page enfocada en promocionar articulos impresos en 3d e incentivar la compra o cotizaciones.

# MilkKing 3D — Landing Page & Catálogo Interactivo

Landing page y plataforma web interactiva diseñada para **MilkKing 3D**, un estudio especializado en diseño, prototipado y manufactura aditiva (impresión 3D). La plataforma está optimizada para la captación y conversión de clientes minoristas, mayoristas y socios comerciales (estudiantes, profesionistas y emprendedores).
El `README.md` se actualiza para reflejar la separación modular de archivos (`css/estilos.css`, `js/script.js` y `img/`), los nombres oficiales de las imágenes de referencia y la lista actualizada de categorías profesionales.

```markdown
# MilkKing 3D — Landing Page & Catálogo Interactivo

Plataforma web oficial y catálogo interactivo de **MilkKing 3D**, estudio especializado en diseño, prototipado y manufactura aditiva (impresión 3D). La interfaz está estructurada modularmente en HTML5, CSS3 y JavaScript vanilla para facilitar su despliegue inmediato en **GitHub Pages**.

---

## 📌 Tabla de Contenidos

1. [Estructura del Proyecto](#-estructura-del-proyecto)
2. [Identidad Visual y Paleta de Colores](#-identidad-visual-y-paleta-de-colores)
3. [Guía de Recursos Gráficos (Carpeta `img/`)](#-guía-de-recursos-gráficos-carpeta-img)
4. [Líneas de Producción y Categorías](#-líneas-de-producción-y-categorías)
5. [Canales de Integración y Contacto](#-canales-de-integración-y-contacto)
6. [Instalación y Despliegue en GitHub Pages](#-instalación-y-despliegue-en-github-pages)

---

## 📂 Estructura del Proyecto

El código está desacoplado para mantener orden en el repositorio y buenas prácticas de desarrollo web:

```text
milkking-3d/
│
├── index.html         # Maquetado semántico, estructura de secciones y enlaces
├── css/
│   └── estilos.css    # Variables globales (#021A54), estilos de componentes y diseño responsivo
├── js/
│   └── script.js      # Catálogo dinámico, buscador en vivo, Web Share API, modales y FAQ
├── img/               # Directorio exclusivo para imágenes y fotografías reales
│   ├── logo.png       # Logotipo oficial circular
│   ├── taz.png        # Figura Tazmanian Devil
│   ├── chimuelo.png   # Set de llaveros Chimuelo (Toothless)
│   ├── marcianos.png  # Trío de marcianos Toy Story
│   ├── pantera.png    # Figura Pantera Rosa
│   ├── medusa.png     # Escultura Medusa (Bambu Lab)
│   ├── calabaza.png   # Calabaza geométrica estacional
│   ├── vanity.png     # Organizador porta cosméticos
│   └── placa.png      # Placa para mascota con QR
└── README.md          # Documentación del proyecto

```

---

## 🎨 Identidad Visual y Paleta de Colores

La plataforma utiliza una combinación de colores que asegura contraste de lectura y resalta las acciones comerciales:

| Color | Código HEX | Aplicación en la Interfaz |
| --- | --- | --- |
| **Azul Marino Primario** | `#021A54` | Botones principales (CTA), isotipos, encabezados y navegación |
| **Rosa Vibrante (Accent)** | `#FF85BB` | Etiquetas de descuento, badges de oferta y detalles de hover |
| **Rosa Suave** | `#FFCEE3` | Fondos de realce, chips secundarios y tarjetas suaves |
| **Gris Neutro** | `#F5F5F5` | Fondo general de la plataforma para balance visual |

---

## 🖼️ Guía de Recursos Gráficos (Carpeta `img/`)

El archivo `js/script.js` vincula directamente los nombres de archivo dentro del directorio `img/`. Para personalizar el catálogo con tus fotos de estudio, coloca tus archivos con los siguientes nombres:

* `img/logo.png`: Logotipo oficial circular con fondo blanco perla.
* `img/taz.png`: Fotografía de Taz sobre fondo de estudio oscuro.
* `img/chimuelo.png`: Trío de llaveros Chimuelo con ojos luminiscentes verdes.
* `img/marcianos.png`: Trío de marcianos de Toy Story sobre fondo blanco.
* `img/pantera.png`: Escultura articulada de la Pantera Rosa.
* `img/medusa.png`: Fotografía del busto Medusa en proceso de impresión.

> **Sistema de Respaldo Gráfico (Fallback):** Si alguna fotografía no está presente en la carpeta `img/` o presenta demoras en la carga, el script activa automáticamente una ilustración vectorial con el sello de agua oficial `MILK·KING`.

---

## 🏷️ Líneas de Producción y Categorías

El catálogo incluye filtros rápidos con nombres profesionales y clasificación estacional automatizada:

1. **Coleccionables & Pop:** Figuras articuladas, piezas de animación y personajes de autor.
2. **Diseño de Interiores & Lifestyle:** Decoración moderna, organizadores y piezas para el hogar u oficina.
3. **Línea Vanity & Estética:** Organizadores para cosméticos, brochas y cuidado personal.
4. **Accesorios para Mascotas:** Placas de identificación y complementos resistentes en PETG.
5. **Edición Estacional:** Banner dinámico que detecta automáticamente la fecha del año (especial de Halloween en otoño o Navidad en invierno).
6. **Prototipado a Medida:** Cotizaciones para modelado personalizado y producción de lotes especiales.

---

## 📲 Canales de Integración y Contacto

* **WhatsApp Directo:** Botón de cotización directa vinculado a la línea `+52 55 2081 0586` con mensaje precargado:
> *"Hola te escribo para cotizarte mi articulo impreso en 3D, estoy buscando..."*


* **Instagram Oficial:** Enlace al perfil [@milkking.3d](https://www.instagram.com/milkking.3d/).
* **Mercado Libre:** Redirección a la tienda en línea para envíos rápidos y pagos con tarjeta.
* **Formulario de Socios:** Módulo para emprendedores, profesionistas y estudiantes que estructura datos de piezas requeridas y fecha límite, enviándolos directo a WhatsApp.

---

## 🚀 Instalación y Despliegue en GitHub Pages

1. **Clonar o inicializar el repositorio local:**
```bash
git init
git add .
git commit -m "feat: landing page modular MilkKing 3D"
git branch -M main
git remote add origin [https://github.com/](https://github.com/)<tu-usuario>/<tu-repositorio>.git
git push -u origin main

```


2. **Habilitar GitHub Pages:**
* Abre tu repositorio en GitHub y haz clic en **Settings**.
* En el menú lateral izquierdo, selecciona **Pages**.
* En **Source**, selecciona `Deploy from a branch`.
* En **Branch**, marca `main` y la carpeta `/ (root)`.
* Haz clic en **Save**. En un par de minutos, el sitio estará en línea en:
`https://<tu-usuario>.github.io/<tu-repositorio>/`



```

```
