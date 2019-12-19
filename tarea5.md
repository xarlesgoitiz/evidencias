# 1. Servidor ftp
### 1.1 Instalar Vsftpd (Very Secure FTP Daemon)

Es un servicio FTP que permite implementar servicios de archivos mediante protocolo FTP

![](fotos/Captura60.PNG)


### 1.2 COMO AÑADIR USUARIOS

para crear usuarios se utilizara este comando:
**sudo useradd -d xxdondexx xxusuarioxx**


![](fotos/Captura61.PNG)
![](fotos/Captura62.PNG)
 
hay que ponerle contraseña a los usuarios, utiliza este comando:
**sudo passwd nomreDeUsuario**

![](fotos/Captura63.PNG)

hay que abrir el puerto 21 para el FTP en el servidor. 
![](fotos/Captura64.PNG)
![](fotos/Captura65.PNG)
![](fotos/Captura66.PNG)

Falta reiniciar el servicio y ya funcionaria, para ello pon este comando:
**sudo service vsftpd restart**
![](fotos/Captura67.PNG)

Ya tienes todo configurado. :smile:
