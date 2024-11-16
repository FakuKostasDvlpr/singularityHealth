# singularityHealth
Prueba tecnica

Aplicación de Login y Registro
Esta aplicación permite a los usuarios registrarse e iniciar sesión utilizando un conjunto específico de correos electrónicos predefinidos. Los usuarios pueden crear una contraseña durante el proceso de registro.

Requisitos
Antes de comenzar, asegúrate de tener las siguientes herramientas instaladas:

Node.js
npm o yarn
Instalación
Sigue estos pasos para instalar y ejecutar la aplicación en tu entorno local.

Clona este repositorio:

bash
Copiar código
git clone https://github.com/tuusuario/tu-repositorio.git
cd tu-repositorio
Instala las dependencias:

bash
Copiar código
npm install
# o si prefieres yarn
yarn install
Ejecuta la aplicación:

bash
Copiar código
npm run dev
# o con yarn
yarn dev
La aplicación debería estar disponible en http://localhost:3000.

Registro de Usuario
El proceso de registro requiere un correo electrónico específico de la lista proporcionada, y el usuario deberá crear una contraseña.

Correos Electrónicos Permitidos
A continuación se muestra una lista de los correos electrónicos que pueden ser utilizados para el registro:

george.bluth@reqres.in
janet.weaver@reqres.in
emma.wong@reqres.in
eve.holt@reqres.in
charles.morris@reqres.in
tracey.ramos@reqres.in
michael.lawson@reqres.in
lindsay.ferguson@reqres.in
tobias.funke@reqres.in
byron.fields@reqres.in
george.edwards@reqres.in
rachel.howell@reqres.in
Paso 1: Ingreso del Correo Electrónico
Durante el registro, se solicitará un correo electrónico. Si el correo está en la lista de correos permitidos, el sistema permitirá continuar con la creación de la contraseña.

Paso 2: Creación de Contraseña
Una vez que el correo electrónico sea validado, el usuario podrá crear una contraseña para su cuenta.

Login
Para iniciar sesión, el usuario debe ingresar un correo electrónico que coincida con los de la lista previamente mencionada y la contraseña que haya creado durante el registro.

API
La API utilizada para el login y registro solo acepta los correos electrónicos mencionados anteriormente. El flujo de autenticación se realiza mediante un token de autenticación que se devuelve tras un login exitoso.
