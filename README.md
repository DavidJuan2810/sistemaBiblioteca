Sistema de Gestión de Bibliotecas

Al clonar el repositorio, este viene completo para su correcto funcionamiento. Sin embargo, para que el sistema se ejecute correctamente de forma local,
debes instalar las dependencias tanto en el backend como en el frontend.
Sigue estos pasos:

- Desde la consola del proyecto, ingresa a la carpeta frontBiblioteca o back-end:
   cd frontBiblioteca      #ingresar a la carpeta
   npm install             #para intalar dependencias
asi mismo lo realizas con la carpeta back-end

- Debes tener activo Laragon o cualquier otro servidor local que permita trabajar con bases de datos mysql
  
- realizas las migraciones a la base de datos del sistema, desde la consola estando dentro de la carpeta del backend
   cd back-end
   npx prisma migrate dev --name nombre_migracion
  
- corres tanto el backend como el frontend, con el siguiente comando:
   npm run dev
   
- Ten en cuenta que debes tener dos consolas abiertas:
   Una ejecutando el backend (que corre en el puerto 3000).
   Otra ejecutando el frontend.         
