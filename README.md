# Electro Emporium

> **Proyecto final en equipo** del bootcamp Henry (mayo a junio de 2024). Esta es una copia de portafolio: el repositorio original tiene la historia completa con los aportes de cada integrante.
>
> **Mi aporte** (115 de 408 commits, principalmente frontend): el perfil del usuario con sus productos publicados y sus ventas (crear, editar y eliminar productos), el detalle de producto con reseñas, el estado global con Redux Toolkit, y partes del inicio, la búsqueda y el registro.


¡Bienvenido al repositorio de Electro Emporium!

Electro Emporium es un marketplace de compra y venta de productos electrónicos, desarrollado por un equipo de 7 personas. Esta aplicación ofrece una experiencia completa para los usuarios, permitiéndoles autenticarse, crear sesión, cerrar sesión o eliminar su cuenta, con la autenticación proporcionada por Auth0.

## Funcionalidades Principales

- **Autenticación de Usuarios:** Sistema de autenticación proporcionado por Auth0.
- **Gestión de Productos:** Permite a los usuarios cargar, modificar, y eliminar productos.
- **Subida de Imágenes:** Integración con Cloudinary para el manejo de imágenes.
- **Reseñas y Calificaciones:** Los usuarios pueden dejar reseñas y calificar productos.
- **Carrito de Compras:** Funcionalidad de carrito para agregar productos y proceder con la compra.
- **Pago Integrado:** Integración con Mercado Pago para realizar pagos.
- **Gestión de Envío y Entrega:** Proceso completo de envío y entrega de productos.

## Tecnologías Utilizadas

- **Frontend:** JavaScript, React, Redux Toolkit, TypeScript, Bootstrap, Axios
- **Backend:** Node.js, Express.js, Sequelize
- **Base de Datos:** PostgreSQL
- **Autenticación:** Auth0
- **Manejo de Imágenes:** Cloudinary
- **Deploy:** Vercel

## Instalación y Uso

### Clonar el Repositorio

```bash
git clone https://github.com/alvarorojasdev/electro-emporium.git
cd PF
```

### Configuración del Backend

1. Navega a la carpeta del backend:
    ```bash
    cd backend
    ```
2. Instala las dependencias:
    ```bash
    npm install
    ```
3. Configura las variables de entorno en un archivo `.env` siguiendo el ejemplo proporcionado en `.env.example`.
    ```env
    DB_USER=your_db_user
    DB_PASSWORD=your_db_password
    DB_HOST=your_db_host
    DB_NAME=your_db_name
    CLOUDINARY_CLOUD_NAME=your_cloud_name
    CLOUDINARY_API_KEY=your_api_key
    CLOUDINARY_API_SECRET=your_api_secret
    AUTH0_DOMAIN=your_auth0_domain
    AUTH0_CLIENT_ID=your_auth0_client_id
    AUTH0_CLIENT_SECRET=your_auth0_client_secret
    MERCADO_PAGO_ACCESS_TOKEN=your_mercado_pago_access_token
    ```
4. Inicia el servidor:
    ```bash
    npm start
    ```

### Configuración del Frontend

1. Navega a la carpeta del frontend:
    ```bash
    cd ../frontend
    ```
2. Instala las dependencias:
    ```bash
    npm install
    ```
3. Configura las variables de entorno en un archivo `.env` siguiendo el ejemplo proporcionado en `.env.example`.
    ```env
    REACT_APP_API_URL=your_backend_api_url
    REACT_APP_AUTH0_DOMAIN=your_auth0_domain
    REACT_APP_AUTH0_CLIENT_ID=your_auth0_client_id
    REACT_APP_CLOUDINARY_URL=your_cloudinary_url
    ```
4. Inicia la aplicación:
    ```bash
    npm run dev
    ```

### Uso

1. Asegúrate de que el backend esté ejecutándose (`npm start` en la carpeta `backend`).
2. Ejecuta el frontend (`npm run dev` en la carpeta `frontend`).
3. Abre tu navegador y navega a `http://localhost:3000` para ver la aplicación en funcionamiento.

## Contribución

¡Contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:
1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Agrega nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

## Colaboradores

Este proyecto fue desarrollado por un equipo de personas talentosas, incluyendo:

1. [Gonzadeveloper](https://github.com/Gonzadeveloper)
2. [Alvaro Rojas](https://github.com/alvarorojasdev)
3. [CEQuinterogarcia](https://github.com/CEQuinterogarcia)
4. [MGoretta](https://github.com/MGoretta)
5. [GPWaterdrinker](https://github.com/GPWaterdrinker)
6. [lisalescano](https://github.com/lisalescano)
7. [MatiasPeusco](https://github.com/MatiasPeusco)


## Licencia

Este proyecto está licenciado bajo la Licencia MIT.

## Contacto

Para más información o consultas, puedes contactarme en:

- 📧 alvarorojas.dev@gmail.com
- 💻 [GitHub](https://github.com/alvarorojasdev)

---

¡Conéctate conmigo y comencemos a construir algo increíble juntos!
```


