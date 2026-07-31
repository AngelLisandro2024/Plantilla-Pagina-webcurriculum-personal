# 📄 Plantilla de Currículum Personal y Portafolio Profesional (Bootstrap 5)

Sitio web estático, adaptable y de diseño moderno concebido como plantilla base para la presentación de currículums de perfil técnico, portafolios de servicios y páginas personales de presentación laboral. Su estructura está optimizada para destacar la propuesta de valor del profesional y facilitar la conversión mediante botones directos de contacto por WhatsApp, correo y llamadas.

---

## ✨ Características Principales

* **💼 Hero Section de Presentación:** Módulo principal de alto impacto visual diseñado para destacar nombre, título profesional, propuesta clave y llamadas a la acción inmediatas.
* **🛠️ Módulo de Servicios:** Rejilla interactiva de tarjetas (*cards*) con efecto hover (*glassmorphism*) para exhibir ofertas técnicas o servicios profesionales con imágenes descriptivas.
* **🖼️ Galería de Portafolio con Visor Modal:** Módulo para previsualizar proyectos o trabajos realizados, integrado con un script en JavaScript (ES6) que abre cualquier imagen en pantalla completa al hacer clic.
* **📲 Contacto Multicanal Directo:** Botones estratégicos de llamada a la acción (CTA) configurados con la API de WhatsApp (`wa.me`), protocolo telefónico (`tel:`) y enlaces a correo electrónico (`mailto:`).
* **📱 Diseño 100% Responsivo:** Maquetado fluido basado en el sistema de rejilla de **Bootstrap 5.3.3**, optimizado para lectura y navegación en dispositivos móviles, tablets y escritorios.
* **🛠️ Código Guiado:** HTML y CSS ampliamente comentados paso a paso para sustituir de forma sencilla textos, datos de contacto, enlaces e imágenes.

---

## 🛠️ Stack Tecnológico

* **Estructura:** HTML5 Semántico
* **Estilos:** CSS3 (Variables nativas `:root` + Flexbox + Efectos Glassmorphism) / Bootstrap 5.3.3
* **Iconografía:** Bootstrap Icons 1.11.3
* **Lógica Client-Side:** JavaScript (ES6) para la apertura dinámica del visor modal y cálculo del año en el pie de página
* **Hosting / Despliegue:** GitHub Pages

---

## 📁 Estructura del Proyecto

```text
Curriculum_Personal/
├── Imagenes/          # Galería de imágenes (Logo, perfil, imágenes de servicios y proyectos)
│   ├── logo.jpg
│   ├── yo.jpg
│   └── [1-13].(png|jpg)
├── index.html         # Código fuente de la plantilla maquetado y comentado por secciones
├── styles.css         # Hoja de estilos personalizados, variables de color y efectos de tarjetas
└── README.md          # Documentación del proyecto
```
⚙️ Guía de Personalización Rápida
Editar Datos Personales y Textos: Abre index.html y modifica el nombre, título profesional y descripciones guiándote por los comentarios <!-- Aqui cambias... -->.

Configurar Enlaces de Contacto: Sustituye los números telefónicos en los enlaces de WhatsApp (https://wa.me/58...), llamadas (tel:+58...) y la dirección de correo electrónico.

Cambiar Imágenes de Perfil y Servicios: Sustituye las imágenes dentro de la carpeta Imagenes/ manteniendo la nomenclatura o actualizando las rutas src dentro de index.html.

Personalizar la Paleta de Colores: Modifica las variables contenidas dentro del bloque :root en styles.css para adaptar la combinación cromática a tu estilo personal.

👨‍💻 Sobre el Desarrollador
Ángel Fernández | T.S.U en Informática

Desarrollador de software backend y creador de soluciones digitales enfocadas en funcionalidad, rendimiento y diseño accesible.
