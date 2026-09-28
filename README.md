# Proyecto_Bloque1_DWEC

<<<<<<< HEAD
raul


=======
>>>>>>> 156c8b19d176eca21692ff6c75af0a2ddc0adf4b
# Análisis de Amazon: Frontend, Backend y modelo Cliente-Servidor

## 1. Introducción

Amazon es una plataforma de comercio electrónico que permite a los usuarios buscar productos, consultar información, añadir productos al carrito y realizar compras a través de Internet.

Para que Amazon funcione correctamente intervienen diferentes tecnologías y componentes, principalmente el **Frontend**, el **Backend** y el modelo **Cliente-Servidor**.

---

## 2. Frontend

El **Frontend** es la parte de la aplicación que el usuario puede ver y utilizar directamente desde el navegador.

En Amazon, algunos ejemplos de elementos del Frontend son:

- Barra de búsqueda de productos.
- Menús y categorías.
- Imágenes de los productos.
- Nombre, precio y descripción de los productos.
- Botones como "Añadir al carrito" o "Comprar ahora".
- Carrito de compra.
- Formularios para introducir datos.
- Página de inicio de sesión.
- Diseño, colores, botones y otros elementos visuales.

El Frontend se ejecuta principalmente en el navegador del usuario y utiliza tecnologías como:

- **HTML**: estructura de la página.
- **CSS**: diseño y apariencia.
- **JavaScript**: comportamiento e interacción de la página.

Por ejemplo, cuando un usuario pulsa el botón **"Añadir al carrito"**, el Frontend se encarga de detectar la acción y comunicarse con el Backend para actualizar el carrito.

---

## 3. Backend

El **Backend** es la parte de Amazon que funciona en los servidores y que normalmente no podemos ver directamente.

Se encarga de procesar las peticiones realizadas por los usuarios y gestionar la información necesaria para que la aplicación funcione.

Algunas funciones del Backend de Amazon son:

- Gestionar las cuentas de los usuarios.
- Consultar los productos disponibles.
- Gestionar los precios y el stock.
- Procesar los carritos de compra.
- Gestionar los pedidos.
- Procesar los pagos.
- Guardar y consultar información en bases de datos.
- Gestionar los sistemas de autenticación.
- Enviar la información solicitada al usuario.

Por ejemplo, cuando buscamos un producto, el Backend recibe la búsqueda, consulta la información correspondiente y devuelve los resultados al navegador.

---

## 4. Modelo Cliente-Servidor

Amazon utiliza un modelo basado en **Cliente-Servidor**.

En este modelo existen principalmente dos partes:

- **Cliente**: normalmente es el navegador web del usuario.
- **Servidor**: son los sistemas informáticos que procesan las peticiones y proporcionan la información.

El funcionamiento básico sería el siguiente:

1. El usuario abre Amazon desde su navegador.
2. El navegador actúa como **cliente** y realiza una petición al servidor.
3. El servidor recibe la petición.
4. El Backend procesa la petición y consulta los datos necesarios.
5. El servidor devuelve una respuesta al cliente.
6. El navegador recibe la información y la muestra al usuario.

### Ejemplo: búsqueda de un producto

Si un usuario busca "ordenador portátil" en Amazon:

```text
USUARIO
   |
   v
NAVEGADOR WEB
   |
   | Petición: "ordenador portátil"
   v
SERVIDOR DE AMAZON
   |
   v
BACKEND
   |
   v
BASE DE DATOS
   |
   | Resultados
   v
BACKEND
   |
   | Respuesta
   v
NAVEGADOR WEB
   |
   v
USUARIO