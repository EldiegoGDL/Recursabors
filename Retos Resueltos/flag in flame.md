## Descripción 
The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it. The team is relying on your skills to uncover any concealed information within this unusual log.Download the encoded data here: [Logs Data](https://challenge-files.picoctf.net/c_amiable_citadel/7644875fe64cafe647bcd166855b1adf4368ed7f13be7acb281f8647eb0a5b83/logs.txt). Be prepared—the file is large, and examining it thoroughly is crucial .
## Solución
Descargar el archivo logs.txt

Convertirlo en base 64. 

Nos damos cuenta que es un .png.

Cambiamos la extensión a .png.

dentro de la imagen viene un codigo en hexadecimal.

Lo decodificamos usando una pagina.

obtenemos la flag:

picoCTF{forensics_analysis_is_amazing_ec1984fc}
## Notas Adicionales 
## Referencias
https://gchq.github.io/CyberChef/#recipe=From_Hex('Auto')&input=NzA2OTYzNkY0MzU0NDY3QjY2NkY3MjY1NkU3MzY5NjM3MzVGNjE2RTYxNkM3OTczNjk3MzVGNjk3MzVGNjE2RDYxN0E2OTZFNjc1RjY1NjMzMTM5MzgzNDY2NjM3RA 
