# Azure Cloud Shell
Azure Cloud Shell, es una shell interactiva disponible desde el Portal de Azure que usamos directamente en el navegador para administrar los recursos de Azure sin necesidad de instalar ninguna herramienta en nuestro PC.

La shell dispone de 2 versiones:

- Bash: Si estáis acostumbrados a trabajar con comandos Linux.
- PowerShell: Si sois más del mundo Windows y comandos PS.

Azure Cloud Shell crea y utiliza una cuenta de almacenamiento de tipo Azure Files para los archivos que utilizamos en las sesiones de trabajo, esta cuenta de almacenamiento se creará la primera vez que usemos la shell y la veremos en nuestra suscripción.

Además tiene una serie de características que debemos conocer:

- Requiere montar un recurso compartido de archivos de Azure.
- Los permisos se establecen como usuario de Linux normal en Bash.
- Se ejecuta en un host temporal por cada sesión y usuario.
- Caduca la sesión trascurridos 20 minutos sin actividad interactiva.
- Usa el mismo recurso de archivos para Bash y para PowerShell.
- Se asigna a Cloud Shell una máquina por cuenta de usuario.
- $HOME con una imagen de 5 GB mantenida en el recurso compartido de archivos
