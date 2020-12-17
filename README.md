Aplicación móvil de chat en tiempo reaL

1. Herramientas
- Ionic 5 + Angular 
- Firebase 

2. Pasos para correr localmente 
- Clonar el repositorio con `git clone https://github.com/Dannygua/APP-Chat.git`
- Localmente ingresar al directorio raíz del proyecto y ejecutar `npm install`, este comando se encarga de leer las dependencias del archivo package.json e instalarlas en la aplicación, al realizar esto se crea la carpeta node_modules
- Una vez realizado esto y con Ionic previamente instalado, ya tenemos todo lo necesario para correr nuestro proyecto localmente, para realizarlo ejecutamos `ionic serve` 
- El resultado de esto será que podemos ver el contenido de nuestra app en nuestro navegador a través de la dirección localhost:3000 

3. Para compilar la app 
- Ejecutar el comando `npm run ionic:build --prod`, este comando compila el proyecto y los archivos desplegables los almacena en la carpeta build 
- Después de esto podemos iniciar el proceso para montar nuestra app en la Play Store o App Store, para lo cual se recomienda revisar la documentación. 


