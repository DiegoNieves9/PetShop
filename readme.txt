Descargar los siguiente en el cmd:

npm install firebase
npm install firebase react-firebase-hooks


Instalación de la app de Android Studio:

1. Descarga el APK de la app de Android Studio
2. Habilita la opción para instalar aplicaciones de fuentes desconocidas:
   "Configuración" > "Seguridad" o "Configuración" > "Aplicaciones"
3. Abre el explorador de archivos en el dispositivo Android
4. Encuentra el archivo APK y toca para iniciar la instalación
5. Sigue las instrucciones en pantalla para completar la instalación


Forma alternativa de instalación de la app de Android Studio:

1. Descarga la versión más reciente de Android Studio
2. Descarga y exporta el proyecto "Coordenadas" a Android Studio
3. Abre el proyecto y ve al apartado "Device Manager"
4. Ahora deberás conectar tu dispositivo Android
5. Habilita la opción "Depuración por USB" en caso de conectarlo por medio de un cable o la opción "Depuración inalámbrica" para conectarlo por medio de Wi-fi. Ambas opciones se encuentran en:
"Configuración" > "Opciones de desarrollador".
Si no encuentras "Opciones de desarrollador" deberás habilitarlas.
Habilitar las opciones de desarrollador y depuración:
Ve a "Configuración" en tu dispositivo Android, ve a la sección "Acerca del teléfono" o "Acerca del dispositivo", busca "Número de compilación" o "Número de versión" y toca repetidamente en este apartado (es posible que te pida ingresar una contraseña); si has realizado correctamente lo anterior, veras un mensaje indicando que las opciones de desarrollador están activadas, ve a "Configuración", luego a "Opciones de desarrollador" y busca la opción “Depuración de USB” o “Depuración inalámbrica” según sea el caso y actívala.
6. Si conectaste tu dispositivo por cable ahora debería aparecer conectado en el apartado de “Physical”. Si habilitaste la opción “Depuración inalámbrica” ve a Android Studio y da clic en “Pair using Wi-Fi”, luego elige entre “Pair using QR code” o “Pair using pairing code”, para cada caso vuelve al apartado de “Depuración inalámbrica” y ve a configuración, elige entre la opción “Vincular dispositivo mediante código QR” o “Vincular dispositivo con código de sincronización” según lo que hayas elegido en Android Studio, luego de escanear el código QR o introducir el código de sincronización tu dispositivo debería aparecer conectado en el apartado de “Physical”.
7. Da clic en “Run 'app'” y espera a que termine el proceso, al terminar la app deberá estar descargada en tu dispositivo.

Ejecución del sitio web para monitorear:
1. En la carpeta titulada "mapas.rar" deberán extraerse los archivos para que la aplicación de ejecute de manera correcta.
2. Teniendo los archivos listos, dentro de la carpeta "Public" dar doble click en el archivo titulado "index.html"
3. Una vez dentro del sitio web, aparecerá un inicio de sesión donde se deberá de colocar el nombre de usuario con el cual se dió de alta en la página de compras, seguido del código que se le proporcionó al adquirir el producto.
4. De inmediato aparecerá una ventana emergente, la cual le pedirá hacer "Click" para poder ingresar al monitoreo de las ubicaciones una vez que se haya verificado el código que proporcionó.
5. Una vez dentro del monitoreo de ubicaciones, usted podrá ver la última ubicación guardada expresada en coordenadas y para un mejor entendimiento, un mapa que muestra la dirección que arrojan las coordenadas.
6. El usuario debe presionar el botón "Activar GPS" para poder iniciar la búsqueda, después de eso, deberá presionar el botón "Buscar" para mostrar la ubicación exacta de dónde se encuentra la mascota.
7. El usuario puede ver la fecha y hora exacta en la que se hizo el registro de las coordenadas proporcionadas por el GPS.