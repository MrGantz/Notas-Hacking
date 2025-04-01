
#### Description

Can you find the flag on this website.

Additional details will be available after launching your challenge instance.


Al intentar iniciar sesión en la pagina nos da esto:

![[Primer inicio de sesion.png]]

inicio de sesión con la inyección: 'or 1 == 1;

![[Inyección.png]]Aqui podemos ver toda la estructura de la base de datos:

![[Estructura BD.png]]ahora solo extraemos la informacion de la flag que se encuentra en la tabla: more_table

![[Actividad 10/More SQLi/Flag.png]]
FLAG:

picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_e3e46aae}