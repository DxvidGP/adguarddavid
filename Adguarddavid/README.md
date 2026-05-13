## Evidencias del despliegue

### 1. Creación de directorios

Se ha creado la carpeta `C:\adguard-home-practica` para alojar el proyecto.
Dentro se han generado las subcarpetas `work` y `conf`.
Estas carpetas se usarán para almacenar la configuración y los datos de forma persistente.

<img width="744" height="521" alt="image" src="https://github.com/user-attachments/assets/c20d0b9c-f550-4284-bcbc-007b7009e1a1" />


### 2. Archivo docker-compose.yml

Se ha definido el servicio de AdGuard Home usando la imagen oficial.
Se han expuesto los puertos 3000 (setup inicial), 53 (servicio DNS) y 80 (panel web).
Se han configurado volúmenes persistentes con las carpetas `work` y `conf`.

<img width="750" height="320" alt="image" src="https://github.com/user-attachments/assets/4d7a137b-c69b-4818-8659-079a32ad63ce" />


### 3. Despliegue del contenedor

Se ha ejecutado `docker-compose up -d` para levantar el contenedor en segundo plano.
Docker ha descargado la imagen y ha iniciado el servicio correctamente.

<img width="752" height="101" alt="image" src="https://github.com/user-attachments/assets/94518c78-1560-4347-a37c-e0b984c18b03" />


### 4. Configuración de puertos

En el paso 2 del asistente se ha configurado la interfaz web en el puerto 80.
El servidor DNS se ha configurado en el puerto 53 usando todas las interfaces.
El servicio estará disponible en las direcciones 127.0.0.1 y 172.18.0.2.

<img width="532" height="715" alt="image" src="https://github.com/user-attachments/assets/ea9045be-c7e7-4a7c-b3d5-84792ecbb577" />



### 5. Verificación del bloqueo

Se ha bloqueado Chatgpt para la prueba, en las siguientes imagenes se puede apreciar

<img width="1079" height="244" alt="image" src="https://github.com/user-attachments/assets/6b7cab61-fe2c-4cc9-a182-1fc2061768b7" />


<img width="560" height="168" alt="image" src="https://github.com/user-attachments/assets/c00129c5-b141-4091-9b35-d42a34d612aa" />

<img width="1133" height="546" alt="image" src="https://github.com/user-attachments/assets/80f5e8a7-f213-41ab-b87a-14ea7c3e1443" />

