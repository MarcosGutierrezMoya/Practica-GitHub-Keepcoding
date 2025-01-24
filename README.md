# Practica-GitHub-Keepcoding
### <u>By Marcos Gutierrez Moya</u>

1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    >Deshacer el último commit (perdiendo los cambios realizados en el working copy)
    - <b>Comando:</b> *git reset --hard head~1* 
    - He usado este comando para resetear el commit al anterior pero perdiendo los cambios del working copy.

1. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    >Rehacer el último commit (el que acabamos de deshacer)
    - <b>Comando:</b> *git reflog*
    - He usado este comando para obtener el id de los commit.
    - <b>Comando:</b> *git reset --hard (id del commit)*
    - He usado este comando para deshacer el retroceso del commit y volver al último que tenía.
1.  El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    >Hacer un merge con ‘main’ (styled absorbe a main)
    - <b>Comando:</b> *git merge main*
    - He usado este comando para fusionar la rama main en la rama styled.
1. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    >Hacer un merge de “htmlify” en “styled” (styled absorbe a htmlify)
    - Si lo causó porque cambié el archivo git-nuestro.md y la rama styled no tenía la misma información en esas líneas concretas.
1. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    >Desde “main”, hacer un merge con “styled”
    - No ha causado conflictos porque la información de la rama main está en el repositorio y lo que hemos cambiado es el local.
1. ¿Qué comando o comandos utilizaste en el paso 25?
    >Dibujar el diagrama
    - <b>Comando:</b> *git log --graph*
    - Podría usar para que se viese mejor: *--oneline --decored*
1. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    >Hacer un merge “no fast-forward” de “title” en “main” (main absorbe a title)
    - Si, porque el puntero de main apuntaría al lugar de title y se quedaría con los datos modificados.
1.  ¿Qué comando o comandos utilizaste en el paso 27?
    >Deshacer el merge (sin perder los cambios del working copy)
    - <b>Comando:</b> *git reset head~1* 
1.  ¿Qué comando o comandos utilizaste en el paso 28?
    >Descartar los cambios
    - <b>Comando:</b> *git restore --staged (nombre del archivo)* 
1.  ¿Qué comando o comandos utilizaste en el paso 29?
    >Eliminar la rama “title”
    - <b>Comando:</b> *git branch -D title* 
1.  ¿Qué comando o comandos utilizaste en el paso 30?
    >Rehacer el merge que hemos deshecho
    - <b>Comando:</b> *git reflog* 
    - <b>Comando:</b> *git reset --hard (id del commit)* 
1.  ¿Qué comando o comandos utilizaste en el paso 32?
    >Volver al commit inicial cuando se creó el poema
    - <b>Comando:</b> *git log --reverse* 
    - <b>Comando:</b> *git reset --hard (id del commit)* 
1.  ¿Qué comando o comandos utilizaste en el paso 33?
    >Volver al estado final, cuando pusimos título al poema
    - <b>Comando:</b> *git reflog* 
    - <b>Comando:</b> *git reset --hard (id del commit)*  

