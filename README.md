Integrantes:
  Daniel Figueroa
  Priscila Hernández

Nombre del proyecto:
  Ha uru app
  
Informacion adicional primera entrega:
  - Page 1: principal
  - Page 2: estres
  - Page 3: page3






Informacion segunda entrega:
  
  Estimada profesora, para el el avance de esta entrega es necesario instalar por linea de comando lo siguiente:
  
  Para FIREBASE:
  
  -	>npm install firebase @angular/fire --save
  -	>ng add @angular/fire 
  -	>npm i firebase



  Para STORAGE:
  
  - >npm install @ionic/storage
  - >npm install @ionic/storage-angular

Con todo instalado ya se podra levantar el servidor correspondiente y se podra navegar por los pages implementados y siempre que se haya registrado y logueado en la aplicacion y se compruebe que se cargue el usuario nuevo en la pagina web del firebase.


Informacion Tercera entrega:
Se realiza vincula el proyecto de angular con android studio agregando las carpetas necesaras con los siguientes comandos:
  - >ionic capacitor add android -- crear carpeta android
  - >ionic build -- crear carpeta www
 
De forma adicional se agregan los siguientes comandos para evitar los errores:
  - >npm install @capacitor/core
  - >npm install @capacitor/android
  - >npm instal --legacy-peer-deps
 
 finalmente se ingresa el comando para copiar el proyecto a la carpeta android:
   - >ionic capacitor copy android

Se realizan los test de extremo a extremos a traves del framework jasmine y la carpeta e2e agregada al proyecto

Se genera la APK del proyecto a traves de las opciones disponibles de android studio y se emular a traves de la misma aplicacion para ver su instacion
