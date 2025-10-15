### Descripcion
The login system has been upgraded with a basic rate-limiting mechanism that locks out repeated failed attempts from the same source. We’ve received a tip that the system might still trust user-controlled headers. Your objective is to bypass the rate-limiting restriction and log in using the known email address: **ctf-player@picoctf.org** and uncover the hidden secret.The website is running [here](http://amiable-citadel.picoctf.net:54832/). Can you try to log in?.Download the passwords list [here](https://challenge-files.picoctf.net/c_amiable_citadel/5458857328818398c6c5770b4ada8ce6e9f27a30e241c151eeed462bb33ac496/passwords.txt).

### Solucion
como vemos ahi al ver el passwords.txt tratamos de poner una contraseña en una hasta que lleguemos a la correcta, y la contraseña correcta fue rCRnekkE y con eso nos muestran la llave picoCTF{xff_byp4ss_brut3_1c447e47}

### Notas


### Referencias
