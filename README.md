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

- Configurar los parametros para que se decarge la informacion que se obtuvo en UDP y se pueda descarg un archivo llamado trafico_yol.pcap con un peso de 727 KB formato compatible con el programa WireShark donde se relizara el analisis de la informacion. 

<img width="627" height="496" alt="UDP 4" src="https://github.com/user-attachments/assets/ed06b4f7-2f02-401e-9033-bbcd9c9dd9a1" />

- Trafico que se obtuvo del video

  <img width="1539" height="943" alt="UDP 6" src="https://github.com/user-attachments/assets/feec0e5b-329f-48f4-900a-0fd0c8515578" />

### Analisis del archivo con trafico de protocolo TCP 

- la conversación encuentrar un paquete con protocolo TCP (o
HTTP/HTTPS) Haga clic derecho y seleccione Follow TCP Stream Verá la
comunicación completa para descargar el archivo yolov8n.pt

<img width="1902" height="994" alt="TCP ana 1" src="https://github.com/user-attachments/assets/f15a4885-ac25-41a7-8b32-27bd0c31718e" />

- tcp
flags syn 1 Filtra los paquetes que inician la conexión (el famoso
three way handshake

<img width="1666" height="950" alt="TCP ana 2" src="https://github.com/user-attachments/assets/c2c449bc-1174-4604-afe8-1c06169eb724" />

- tcp
analysis retransmission Muestra si hubo paquetes que se perdieron y tuvieron que
reenviarse, una característica clave de TCP

<img width="1580" height="935" alt="TCP ana 3" src="https://github.com/user-attachments/assets/92c05fa6-d5dc-4d27-9dc5-e64b1cbc4135" />


### Analisis del archivo con trafico de protocolo UDP

- la conversación encuentrar un paquete con protocolo UDP (o
HTTP/HTTPS) Haga clic derecho y seleccione Follow UDP Stream Verá la
comunicación completa para descargar el archivo yolov8n.pt

<img width="1904" height="996" alt="UDP ana 1" src="https://github.com/user-attachments/assets/f366ab9a-8816-4070-9785-4ac025631bc3" />

## Preguntas 
- Ques es Yolo:
 Es un algoritmo de detección de objetos basado en inteligencia artificial que permite identificar y localizar objetos en imágenes o videos en tiempo real, analizando la imagen completa en una sola pasada.

- Cuales son sus caracteristicas principales:
 Sus características principales destacan su alta velocidad, su capacidad para detectar y clasificar múltiples objetos al mismo tiempo y su eficiencia al reducir el tiempo de procesamiento.

- Que arquitectura tiene
  Se basa en una red neuronal convolucional (CNN), compuesta por un backbone que extrae características de la imagen, un neck que combina información a diferentes escalas y un head que realiza las predicciones finales de los objetos detectados.

  







  
