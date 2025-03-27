el reto nos pide lo siguiente:
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: [Addadshashanammu.zip](https://mercury.picoctf.net/static/e38f6a5b69b45d21e33cf7281d8c2531/Addadshashanammu.zip)

para ello, descargamos el archivo con el comando wget y el URL

wget https://mercury.picoctf.net/static/e38f6a5b69b45d21e33cf7281d8c2531/Addadshashanammu.zip
![[Pasted image 20250217232035.png]]

después, descomprimimos el archivo
![[Pasted image 20250217232138.png]]

entramos a la direccion del archivo y dentro usamos el comando strings para descubrir la bandera 
![[Pasted image 20250217232514.png]]

flag: picoCTF{l3v3l_up!_t4k3_4_r35t!_f3553887}
