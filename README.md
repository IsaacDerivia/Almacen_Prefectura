--Hola esta es una guia para tonotos de como hacer generar la carpeta postgreserver dentro de tu maquina 
#Trunski Roy 

📦 Requisitos
En Windows:

Docker Desktop

Git for Windows

WSL2 habilitado

En Linux:

Docker Engine

Docker Compose Plugin

Git

1. Clonar el repositorio
git clone https://github.com/IsaacDerivia/PostgresServer.git (url del repositorio para que no tengas que buscarla pero si es diferente pegalo en el comando )
cd PostgresServer

2. Cambiar a la rama server
git checkout server

3.Levantar el servidor PostgreSQL dentro de docker 
Windios o Linux DEIDAD : docker compose up -d 

para comprobar que esta corriendo:
docker ps
Debe mostrar algo como:
postgres_server   postgres:16   Up   0.0.0.0:5432->5432/tcp (Sino, ir con CHATGPT o rezarle a DIOS )

4. Connectarse al server desde DBeaver (de preferencia) o cualquier Gestor 
Host	localhost
Port	5432
User     ******
Password  ******
database  inventario

(No proporciono USER O PASSWORD por obvias razones) 


NOTA DEL CREADOR
El git no contiene la base de datos (Tambien por obvias razones) pero este es un paso a paso para  la configuracion 





