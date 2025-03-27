el reto nos pide lo siguiente: Can you make sense of this file? Download the file [here](https://artifacts.picoctf.net/c/476/enc_flag).
para resolverlo, primero descargamos el archivo que nos proporcionan con el comando wget

wget https://artifacts.picoctf.net/c/476/enc_flag

![[Pasted image 20250217233700.png]]

para resolver este reto nos ayudaremos de la pagina Cyberchef
![[Pasted image 20250217233936.png]]

para que nos entregue la bandera convertiremos a base64 en repetidas ocasiones hasta que nos muestre la bandera abajo a la derecha
![[Pasted image 20250217234015.png]]

flag: picoCTF{base64_n3st3d_dic0d!n8_d0wnl04d3d_4557ec3e}