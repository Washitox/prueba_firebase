# Nombre de tu Proyecto

Breve descripción o resumen de tu proyecto.

## Tabla de Contenidos

- [Instalación](#instalación)
- [Uso](#uso)

## Instalación

# Paso 1: Instalación de Ionic CLI y Node.js
# Asegúrate de tener Node.js y npm instalados en tu sistema.

npm install -g @ionic/cli

# Paso 2: Clonar el Repositorio
git clone https://github.com/tu_usuario/tu_repositorio.git

# Paso 3: Navegar al Directorio del Proyecto y Instalar Dependencias
cd tu_repositorio
npm install

# Paso 4: Ejecutar en el Servidor de Desarrollo de Ionic
ionic serve

# Paso 5: Compilar y Ejecutar en un Dispositivo Android
# a. Agregar la Plataforma Android
ionic capacitor add android

# b. Construir la Aplicación
ionic build

# c. Abrir en Android Studio
npx cap open android

# d. Compilar y Ejecutar en un Dispositivo o Emulador Android
# Desde Android Studio, compila y ejecuta la aplicación en un dispositivo físico conectado o en un emulador Android.

## Uso

# Registro e Inicio de Sesión
1. Al abrir la aplicación, los usuarios serán recibidos con la pantalla de inicio de sesión.
2. Los nuevos usuarios pueden registrarse seleccionando la opción de "Crear cuenta" e ingresando su correo electrónico y contraseña.
3. Los usuarios registrados pueden iniciar sesión ingresando sus credenciales previamente registradas.

# Creación y Edición del Currículum Vitae (CV)
1. Una vez iniciada la sesión, los usuarios pueden acceder a su perfil personalizado.
2. Desde el perfil, los usuarios tienen la opción de crear un nuevo CV o editar un CV existente.
3. Para crear un nuevo CV, los usuarios pueden completar los campos de información personal, experiencia laboral y educación.
4. Para editar un CV existente, los usuarios pueden seleccionar el CV deseado desde su lista de CV y realizar las modificaciones necesarias.

# Visualización del Currículum Vitae (CV)
1. Después de crear o editar un CV, los usuarios pueden visualizarlo en formato de tarjeta.
2. El CV incluirá secciones para la información personal, la experiencia laboral y la educación, organizadas de manera clara y legible.

# Cierre de Sesión
1. Los usuarios pueden cerrar sesión en cualquier momento seleccionando la opción de "Cerrar sesión" desde el menú de la aplicación.
2. Después de cerrar sesión, los usuarios serán redirigidos a la pantalla de inicio de sesión.

##Conclusiones y recomendaciones
1. Tener en cuenta el incio de seción con firebase estableciendo bien el cliente.
2. Mas uso de las cuentas porque entra con cualquier registro a ver el curriculum.
3. Dedicar más tiempo a los enlaces de entrada para las cuentas y registro de nuestro guardado

