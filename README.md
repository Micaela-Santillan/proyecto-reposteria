# Dulce Tentación | Repostería Artesanal 

Aplicación web de tipo catálogo con carrito de compras desarrollada con **HTML5, CSS3 y JavaScript puro**, como proyecto final para la materia Laboratorio de Programación (Tecnicatura Superior en Desarrollo de Software).

## Rubro Elegido
**Gastronomía / Pastelería Artesanal.** 
El proyecto ofrece una identidad propia ("Dulce Tentación"), orientada a la venta y pedidos online de productos de repostería casera (tortas, budines, tartas y alfajores) con ubicación en Juan B. Alberdi, Tucumán.

---

##  Funcionalidades Principales

- **Catálogo Dinamico:** Generación automática de tarjetas de productos a partir de un array de objetos utilizando `map()` y template strings.
- **Filtros:** Filtrado de productos por categoria. 
- **Gestión de Carrito:** 
  - Agregar productos, aumentar/disminuir cantidades y eliminar ítems individuales o vaciar el carrito completo.
  - Control para evitar duplicados (incrementa la cantidad si el producto ya fue añadido).
  - Cálculo automático del total y contador dinámico de ítems.
- **Persistencia de Datos (`localStorage`):** 
  - El carrito de compras y la preferencia de tema (claro/oscuro) se guardan localmente para no perderse al recargar la página (protegido con bloques `try/catch`).
- **Interfaz Interactiva y Accesible:**
  - Modo oscuro / claro con persistencia.
  - Notificaciones visuales tipo *Toast* para acciones de usuario.
  - Diseño responsivo (adaptado para celulares y computadoras de escritorio) utilizando **Bootstrap 5.3**.

---
##  Tecnologías Utilizadas

- **HTML5** (Estructura semántica, offcanvas).
- **CSS3** (Variables CSS personalizados, soporte nativo para modo oscuro/claro y media queries).
- **JavaScript Moderno (ES6+)** (Manipulación del DOM, delegación de eventos, `localStorage`, arrow functions, `Set`, métodos de arrays).
- **Bootstrap 5.3 & Bootstrap Icons** (Sistema de grillas y componentes UI).
