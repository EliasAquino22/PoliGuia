<div align="center">

# POLIGUÍA

### Mapa interactivo del campus universitario

**Facultad Politécnica · Universidad Nacional del Este (UNE)**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![SVG](https://img.shields.io/badge/SVG-Vectorial-FFB13B?style=flat-square&logo=svg&logoColor=black)

</div>

---

## Descripción

**PoliGuia** es un proyecto web que presenta un mapa interactivo de las instalaciones de la Facultad Politécnica de la Universidad Nacional del Este. Permite explorar visualmente diferentes espacios del campus y consultar información descriptiva al pasar el cursor sobre las zonas habilitadas.

El mapa está construido con gráficos vectoriales **SVG** integrados en HTML. La interacción se implementa en **JavaScript**, mientras que el diseño utiliza **CSS** y la grilla de **Bootstrap 5**.

## Funcionalidades implementadas

- **Mapa vectorial del campus:** visualización de edificios, áreas abiertas, caminos, zonas deportivas y estacionamientos mediante SVG.
- **Resaltado al pasar el cursor:** las áreas interactivas cambian de color para indicar la selección.
- **Panel de información contextual:** muestra el nombre y la descripción de la zona sobre la que se posiciona el cursor.
- **15 zonas con descripciones interactivas:** incluye instalaciones académicas, administrativas, deportivas y espacios comunes.
- **Distribución adaptable:** el contenido se organiza mediante la grilla de Bootstrap y reglas CSS para pantallas de distinto tamaño.
- **Ejecución sin backend:** es un sitio estático que no requiere base de datos ni servidor de aplicaciones.

### Algunas zonas disponibles

| Académicas y administrativas | Servicios y espacios comunes |
| --- | --- |
| Laboratorios, aulas y aula magna | Biblioteca y restaurante universitario |
| Coordinación y mesa de entrada | Comedor y sala de estudio |
|  | Baños, estacionamiento principal y áreas deportivas |

También se incluyen zonas como Poliplaza 1 y el área de calistenia.

> **Alcance actual:** las descripciones se activan mediante eventos `mouseover`. La interacción táctil y por teclado, la búsqueda de lugares, la geolocalización y el cálculo de rutas no están implementados en esta versión.

## Tecnologías

| Tecnología | Uso en el proyecto |
| --- | --- |
| HTML5 | Estructura de la página e integración del mapa SVG |
| CSS3 | Estilos personalizados, resaltado y ajustes visuales |
| JavaScript | Eventos del mapa y actualización del panel informativo |
| Bootstrap 5 | Sistema de grillas y distribución adaptable |
| SVG | Representación vectorial de las áreas del campus |

## Cómo ejecutar el proyecto

No es necesario instalar dependencias ni configurar una base de datos.

1. Cloná el repositorio:

   ```bash
   git clone https://github.com/EliasAquino22/PoliGuia.git
   ```

2. Ingresá a la carpeta `PoliGuia`.
3. Abrí `index.html` con un navegador web moderno.
4. Pasá el cursor sobre las áreas interactivas del mapa para ver su descripción.

También es posible descargar el repositorio como ZIP desde GitHub y abrir el archivo `index.html`.

## Estructura del proyecto

```text
PoliGuia/
├── index.html         # Página principal y mapa SVG
├── script.js          # Eventos e información de las zonas
├── style.css          # Estilos de la interfaz
├── assets/
│   ├── bootstrap/     # Archivos CSS y JS de Bootstrap
│   └── img/           # Logotipos e imágenes del proyecto
└── README.md          # Documentación
```

## Consideraciones y posibles mejoras

- Añadir interacción por clic o toque y soporte de teclado para mejorar la accesibilidad.
- Incorporar descripciones para más sectores del mapa.
- Revisar y optimizar el tamaño de imágenes y recursos estáticos.
- Mejorar los textos y contrastes visuales en dispositivos móviles.

Estas son **mejoras propuestas**, no funcionalidades disponibles actualmente.

## Créditos

Proyecto desarrollado por **Elías Aquino**.

---

<div align="center">

**Proyecto académico de exploración visual del campus universitario.**

</div>
