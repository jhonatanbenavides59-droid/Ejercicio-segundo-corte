# Ejercicio-segundo-corte

### Actividad 

Usando la plataforma de Google Collab, que nos permite simular un entorno Linux se realizar algunas configuraciones usando la aplicación YOLO (es un modelo de inteligencia artificial que detecta objetos en imágenes y videos de forma rápida y eficiente, analizando toda la imagen en un solo paso.) para realizar una simulación de como funcionaria para los protocolos TCP y UDP, con el fin de identificar los pros y los contras de cada protocolo logrando tener la claridad del uso que se podría darle a cada uno y cuales son los escenarios más idóneos de cada uno. 

#### Primer escenario
-	Configurar el Google Collab para que use los recursos de la plataforma
  
<img width="362" height="358" alt="Entorno de ejecicion" src="https://github.com/user-attachments/assets/5b0bbb0f-8b92-4bcd-a4f8-0d934512d448" />

- Realizar la configuración del entorno, instalar las bibliotecas de ultralytics, instalar tcpdum

  <img width="1166" height="508" alt="Paso 1 tcp" src="https://github.com/user-attachments/assets/f5dabe65-481f-49cc-9106-e7f9cccd50ce" />

- Configurar los parametros que la aplicacion YOLO validara en la simulacion como lo son la interfaz, tamaño del paquete, una vez configurado el enterno se procede a generar trafico para que el YOLO recolecte los datos
  
  <img width="1467" height="522" alt="Paso 2 tcp" src="https://github.com/user-attachments/assets/cf0d3c59-0531-43e1-9ee9-c6c980b380ff" />

- Detener la captura de datos y descargar la informacion que se genero, para este coso se obtuvo un archivo llamado descarga_tcp.pcap con un peso de 781 KB formato compatible con el programa WireShark donde se relizara el analisis de la informacion. 

<img width="1900" height="943" alt="TCP Wire" src="https://github.com/user-attachments/assets/cbe4048d-36f8-4751-b074-8d44df266882" />
  
#### Segundo escenario

-	Configurar el Google Collab para que use los recursos de la plataforma, para este caso es necesario instalar dos librerias mas una que permite leer imagenes, video, en conjunto de una libreria que me permmite captura de paquetes para poder analalizar el trafico.

  <img width="377" height="68" alt="UDP 1" src="https://github.com/user-attachments/assets/60a0f261-400f-4de5-b155-4b45755c0eaa" />

- Desde el equipo se cargara un video llamado Video Test que contiene una autopista con trafico, para poder obtener datos

<img width="539" height="111" alt="UDP 2" src="https://github.com/user-attachments/assets/ef599d0a-f651-4e94-9d78-422916afcf0d" />

- Configurar los parametros que la aplicacion YOLO validara en la simulacion como lo son la interfaz, tamaño del paquete, una vez configurado el enterno se procede a generar trafico para que el YOLO recolecte los datos

  <img width="608" height="721" alt="UDP" src="https://github.com/user-attachments/assets/68f76fdc-0e58-4e7f-938c-520ab9d47e78" />

- Confirmacion de que YOLO esta realiando un analis del video.

  <img width="726" height="618" alt="UDP 3" src="https://github.com/user-attachments/assets/edfc4277-af80-4fa4-8622-ffc03fcf4eb8" />

- Configurar los parametros para que se decarge la informacion que se obtuvo en UDP y se pueda descarg un archivo llamado trafico_yol.pcap formato compatible con el programa WireShark donde se relizara el analisis de la informacion. 




  
