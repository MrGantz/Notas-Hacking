El título y el tutorial de la sugerencia parecen apuntar hacia el uso del comando `strings` como `strings strings` para obtener la bandera. En su lugar, podemos utilizar el comando grep, que filtra expresiones específicas en texto plano. Como sabemos que el formato de las banderas picoCTF es picoCTF{...}, podemos buscar picoCTF en grep. El comando sería entonces: `strings strings | grep picoCTF`
Pero antes de hacer esto tenemos que guardar el archivo que nos proporciona el reto y para ello copiamos el URL de la descarga y para poder obtener el archivo escribimos el comando `wget`
junto con el URL

así: wget https://jupiter.challenges.picoctf.org/static/fae9ac5267cd6e44124e559b901df177/strings


![[Guardar archivo strings.png]]

esto nos guardará el archivo strings que es necesario para obtener la bandera

ahora abrimos el archivo strings con el comando `strings strings | grep picoCTF`
![[General Skills 2/strings it/Obtencion de FLAG.png]]