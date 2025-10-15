## Descripción 
We’re in the middle of an investigation. One of our persons of interest, ctf player, is believed to be hiding sensitive data inside a restricted web portal. We’ve uncovered the email address he uses to log in: `ctf-player@picoctf.org`. Unfortunately, we don’t know the password, and the usual guessing techniques haven’t worked. But something feels off... it’s almost like the developer left a secret way in. Can you figure it out?The website is running [here](http://amiable-citadel.picoctf.net:55763/). Can you try to log in?
## Solución
Inspeccionar el codigo fuente 

Rotar esto 13 posiciones alfabéticamente para obtener lo siguiente:

ABGR: Wnpx - grzcbenel olcnff: hfr urnqre "K-Qri-Npprff: lrf"

NOTE: Jack - temporary bypass: use header "X-Dee-Access: yes"

Abrir BurpSuite
Interceptar la proxy de inicio de sesión y mandarla al repetidor.
En el repetidor agregar X Dee-Access: yes al encabezado y mandarlo para obtener la flag.

picoCTF{brut4_f0rc4_0d39383f}

## Notas Adicionales 
## Referencias
