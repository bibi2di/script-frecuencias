# Script para análisis de frecuencias

Se trata de un script de utilidad para descifrar mensajes mediante el análisis de frecuencias. 
Cuenta con un menú con las opciones de:

1.  Contar la frecuencia de palabras
2.  Contar la frecuencia de las letras
3.  Sustituir palabras
4.  Sustituir letras

Mediante la combinación de sustitución entre las palabras más frecuentes y las letras más frecuentes, el usuario puede descifrar el mensaje rápidamente, introduciendo a mano los caracteres/palabras que quiere sustituir. 
Un método arcaico y poco automatizado, pero funcional.


## Cómo se usa: 

En la terminal de comandos (situado en el directorio donde se encuentra el ejecutable): 

```console
tunombre@tuordenata:~$ ./frecuencias.sh nombre_del_archivo_que_quieres_descifrar.txt
MENÚ!
1 - Frecuencia de palabras
2 - Frecuencia de las letras
3 - Sustituir palabras
4 - Sustituir letras
5 - Salir
Elige una opción: 
```

Las dos primeras opciones te permitirán obtener los datos que usarás para descifrar el texto, mientras que las dos siguientes te permiten realizar las sustituciones. El resultado se guardará en un archivo llamado *resultado.txt*.

