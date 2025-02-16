# Tienda Online de Guitarras

Este proyecto es una tienda online de guitarras que permite a los usuarios explorar un catálogo de guitarras y agregarlas al carrito de compras. Los usuarios pueden agregar hasta 5 guitarras al carrito y el sistema realiza los cálculos automáticamente para cada guitarra agregada o eliminada.

Es una aplicación web desarrollada con React, utilizando Vite como herramienta de construcción y TypeScript como superset de JavaScript para agregar características de tipado estático y seguridad.

**Nota:** Este proyecto es una implementación básica de un carrito de compras. No incluye funcionalidades de pago ni procesamiento de órdenes. Su enfoque está en la visualización del catálogo y el manejo del carrito de compras.

## 📋 Características

- **Catálogo de guitarras**: Los usuarios pueden ver una lista de guitarras disponibles en el catálogo.
- **Carrito de compras**: Los usuarios pueden agregar guitarras al carrito, con un límite de hasta 5 guitarras.
- **Cálculos automáticos**: Cada vez que se agrega o elimina una guitarra, se recalcula el total de la compra, considerando el precio individual de cada guitarra.
- **Límite de carrito**: El carrito de compras no permite agregar más de 5 guitarras.

En este proyecto, se implementó un hook personalizado llamado useCart para manejar un carrito de compras en la aplicación. A continuación, se describe la funcionalidad y el código detrás de este hook.

## Funcionalidad

El hook useCart proporciona una forma de agregar y eliminar elementos del carrito, así como de actualizar el estado del carrito en el almacenamiento local del navegador. Esto permite a los usuarios interactuar con el carrito de una manera más intuitiva y eficiente.

## Código

El código del hook useCart se encuentra en el archivo useCart.ts. A continuación, se muestra un resumen de la estructura y la funcionalidad del código:

Se importan las funciones useMemo, useState y useEffect de la biblioteca React.
Se define un estado cart que se inicializa con un arreglo de objetos CartItem.
Se define una función addToCart que agrega un nuevo elemento al carrito.
Se define una función removeFromCart que elimina un elemento del carrito por su ID.
Se utiliza el efecto secundario useEffect para actualizar el estado del carrito en el almacenamiento local del navegador.

## Ventajas

El uso del hook useCart proporciona varias ventajas, incluyendo:

Una forma más intuitiva y eficiente de interactuar con el carrito de compras.
La capacidad de actualizar el estado del carrito en el almacenamiento local del navegador.
Una estructura de código más organizada y fácil de mantener.

## ⚙️ Instalación

Para instalar y ejecutar el proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jempDev/guitar-ts.git
   ```
2. Instala las dependencias

   ```bash
   cd guitar-ts
   npm install
   ```

3. Iniciar la aplicacion
   ```bash
   npm run dev
   ```
