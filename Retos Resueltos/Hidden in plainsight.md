### Descripcion
You’re given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag.Download the jpg image [here](https://challenge-files.picoctf.net/c_saffron_estate/984460cb7eebc16b2908f91210cb8dc4936c63cb6d28c9475fa38dc6a443d1d6/img.jpg).

### Solucion
vemos el metada de la imagen y vemos un comentario que parece curioso, lo codificamos de base 64, despues de ello nos da esto steghide:cEF6endvcmQ= y eso lo decodificamos y sale pAzzword
y con el comando steghide extract -sf img.jpg, nos dara un flag.txt y ahi estara la bandera
picoCTF{h1dd3n_1n_1m4g3_2ac27d95}
### Notas


### Referencias
