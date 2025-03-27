
#### Description

There is some interesting information hidden around this site [http://mercury.picoctf.net:39491/](http://mercury.picoctf.net:39491/). Can you find it?


Inspeccionando el codigo fuente de la pagina proporcionada podremos obtener la primera parte de la bandera:

picoCTF{t

![[Inspeccion de codigo.png]]


Inspeccionando la hoja de estilos podremos obtener la segunda parte

h4ts_4_l0

![[hoja de estilos.png]]


y haciendo uso del robots.txt podremos obtener la tercera parte:

t_0f_pl4c

![[Actividad 09/Scavenger Hunt/robots.txt.png]]



y usando el apache .htaccess podremos obtener la cuarta parte de la bandera:

3s_2_lO0k

![[apache.png]]


y por ultimo haciendo uso del .DS_Store obtendremos la ultima parte de la bandera:

_f7ce8828}

![[DS STORE.png]]


FLAG:

picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_f7ce8828}