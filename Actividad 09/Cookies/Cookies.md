
#### Description

Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:64944/](http://mercury.picoctf.net:64944/)



para resolver este reto usaremos la consola de UBUNTU o cualquier sistema de linux

y usaremos este comando:

for i in {0..20}; do curl -s http://mercury.picoctf.net:64944/check -H "Cookie: name=$i"; done |
grep picoCTF

![[Actividad 09/Cookies/Obtencion de Flag.png]]


FLAG:
picoCTF{3v3ry1_l0v3s_c00k135_cc9110ba}