# Practica-GitHub-Keepcoding
### <u>By Marcos Gutierrez Moya</u>

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    - <b>Comando:</b> *git reset --hard head~1* 
    - He usado este comando para resetear el commit al anterior pero perdiendo los cambios del working copy.

1. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    - <b>Comando:</b> *git reflog*
    - He usado este comando para obtener el id de los commit.
    - <b>Comando:</b> *git reset --hard (id del commit)*
    - He usado este comando para deshacer el retroceso del commit y volver al último que tenía.
1.  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    - <b>Comando:</b> *git merge main*
    - He usado este comando para fusionar la rama main en la rama styled.
1. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    - Si lo causó porque cambié el archivo git-nuestro.md y la rama styled no tenía la misma información en esas líneas concretas.
1. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    - No ha causado conflictos porque la información de la rama main está en el repositorio y lo que hemos cambiado es el local.
1. ¿Qué comando o comandos utilizaste en el paso 25?
    - <b>Comando:</b> *git log --graph*
    - Podría usar para que se viese mejor: *--oneline --decored*
1. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    - Si, porque el puntero de main apuntaría al lugar de title y se quedaría con los datos modificados.
1.  ¿Qué comando o comandos utilizaste en el paso 27?
    - <b>Comando:</b> *git reset head~1* 
1.  ¿Qué comando o comandos utilizaste en el paso 28?
    - <b>Comando:</b> *git restore --staged (nombre del archivo)* 
1.  ¿Qué comando o comandos utilizaste en el paso 29?
    - <b>Comando:</b> *git branch -D title* 
1.  ¿Qué comando o comandos utilizaste en el paso 30?
    - <b>Comando:</b> *git reflog* 
    - <b>Comando:</b> *git reset --hard (id del commit)* 
1.  ¿Qué comando o comandos utilizaste en el paso 32?
    - <b>Comando:</b> *git log --reverse* 
    - <b>Comando:</b> *git reset --hard (id del commit)* 
1.  ¿Qué comando o comandos utilizaste en el paso 33?
    - <b>Comando:</b> *git reflog* 
    - <b>Comando:</b> *git reset --hard (id del commit)*  

