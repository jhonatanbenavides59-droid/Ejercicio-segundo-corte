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
  

