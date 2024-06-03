# Laboratorio 5js ChatClase
## Link para visualizar online
https://steady-smakager-a31502.netlify.app/
## Para ejectuar de forma local
### Tener Docker
### 1. Crear la imagen
```docker build -t uvg-chat-image .```
### 2. Crear el contenedor
```docker run --name chat-container -p 8080:80 uvg-chat-image```
### 3. Ejecutar el docker
```docker start chat-container ```  

## Si tiene algun problema sigue los siguietnes pasos
### 1. Para el contener
```docker stop chat-container```
### 2. Borra el contenedor
```docker rm chat-container```
### 3. BOrra la imagen 
```docker rmi uvg-chat-image```
### 4. Ejectua los pasos anteiores
