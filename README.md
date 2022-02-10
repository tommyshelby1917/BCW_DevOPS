# Práctica DevOPS - Fullstack Web | Keepcoding
## Josep Miquel Arenas Beltran

- Desplegamiento de la app de backend con NodeJS
  - Acceso: http://18.158.60.121/
  - Features:
    1) Nginx 
    3) NodeJS
    4) MongoDB
    5) Supervisor

- Desplegamiento de la app de frontend con ReactJS
  - Acceso: http://ec2-18-158-60-121.eu-central-1.compute.amazonaws.com/
  - Features:
    1) ReactJS
    2) Redux
    3) Backend desplegado Heroku: https://still-plateau-53054.herokuapp.com/
  - En el backend tendremos disponibles los siguientes endpoints:
    1) /api/auth/signup POST: Nos permite crear usuarios
    2) /api/auth/me GET: Nos devuelve la información del usuario autenticado
    3) /api/auth/login POST: Devuelve un token de acceso cuando le pasamos un email y password de un usuario correctos
    4) /api/v1/adverts GET: Devuelve un listado de anuncios
    5) /api/v1/adverts POST: Crea un anuncio
    6) /api/v1/adverts/tags GET: Devuelve el listado de tags disponibles
    7) /api/v1/adverts/:id GET: Devuelve un único anuncio por Id
    8) /api/v1/adverts/:id DELETE: Borra un anuncio por Id
