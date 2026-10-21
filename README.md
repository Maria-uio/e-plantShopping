# e-plantShopping

## Paradise Nursery: aplicación de carrito de compras

**e-plantShopping** es una aplicación web de comercio electrónico para **Paradise Nursery**, una tienda en línea de plantas de interior. Fue desarrollada con **React** y **Redux Toolkit** como proyecto final del curso.

### Funcionalidades

- **Página de inicio** con el nombre de la tienda, una breve descripción y el botón "Get Started".
- **Catálogo de plantas** organizado en 5 categorías: purificadoras de aire, aromáticas, repelentes de insectos, medicinales y de bajo mantenimiento.
- **Botón "Add to Cart"**, que se deshabilita una vez que la planta se agregó al carrito.
- **Barra de navegación** con enlaces a Paradise Nursery (inicio), Plants (catálogo) y el ícono del carrito, que muestra la cantidad total de artículos.
- **Carrito de compras** donde puedes:
  - aumentar o disminuir la cantidad de cada planta,
  - eliminar plantas,
  - ver el subtotal por planta y el costo total,
  - volver al catálogo con "Continue Shopping",
  - usar el botón "Checkout" (próximamente).

### Tecnologías

- React
- Redux Toolkit (`createSlice`, `configureStore`)
- JavaScript (ES6+)
- CSS

### Cómo ejecutar el proyecto

```bash
git clone https://github.com/TU_USUARIO/e-plantShopping.git
cd e-plantShopping
npm install
npm run dev
```

Para ver la versión compilada:

```bash
npm run build
npm run preview
```

### Estructura principal

```
e-plantShopping/
├── src/
│   ├── App.jsx
│   ├── ProductList.jsx
│   ├── CartItem.jsx
│   ├── CartSlice.jsx
│   ├── store.js
│   └── main.jsx
├── package.json
└── README.md
```

### Maria-uio

Proyecto desarrollado por **Mari**.
