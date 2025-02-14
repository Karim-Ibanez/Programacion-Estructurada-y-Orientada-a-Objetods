# Programacion Estructurada y Orientada a Objetods
## Instalacion del entorno de trabajo

1. Abrir terminal de powershell 
2. Escribir en la terminal <b>wsl --install</b>
3. Al terminar, reinicia la computadora para aplicar los cambios
4. Despues, escribe el comando <b>wsl --status </b> para comprobar que esté funcionando.
5. Para asegurarnos que es la version mas reciente usamos <b>wsl --update </b>
6. Usamos el comando <b>wsl</b> para iniciarlo
7. Al abrirlo te pedira crear un usuario y contraseña, pedirá dos veces la contraseña para confirmarla y esta no será visible
8. Instala gcc con el comando <b>sudo apt install gcc</b>
9. Confirma que se instaló correctamente con el comando <b>gcc --version</b>
10. Entra a Visual Studio Code y abre la terminal de ubuntu
11. Escribir el siguiente código y comprobar si funciona:
```languaje
#include <stdio.h>

void main(){
    printf("Hola ICI \n");
}
```
12. En la terminal escribir <b>gcc nombre del documento.c</b> para compilar el programa. Aqui se mostraran los errores del codigo si los tiene
13. Cuando no presente erroes el programa, escribir en la terminal <b>./a.out</b> para ejecutar el programa
14. FELICIDADES. Ya tienes instalado wsl y sabes como ejecutar un programa!!!!
