

Crear un proyecto express con Symfony y enlazarlo a GitHub
==========================================================

1. Requisitos previos:
    
    * Cuenta en GitHub -> https://github.com/join?source=prompt-users-profile
    * Composer instalado en tu equipo -> https://getcomposer.com
    * Git instalado en tu equipo -> https://desktop.github.com/

2. Crea un proyecto mínimo de Symfony en local
    
    * Abre una consola de comandos
    * Ve al directorio con tus proyectos web
    * composer create-project symfony/skeleton symfony-express
    
3. Crea un repositorio en GitHub    

    * Abre la página con tus repositorios en GitHub -> https://github.com/juananruiz?tab=repositories
    * Dale al botón "New"
    * Ponle un nombre y una descripción pero no toques nada más.
    * Dale al botón "Create repository"
    * Copia las líneas:
        git remote add origin https://github.com/juananruiz/symfony-express.git
        git push -u origin master

4. Inicia tu repositorio local y enlálazo con el remoto en GitHub
    
    * Vuelve a la consola de comandos
    * Accede al directorio del nuevo proyecto
    * Teclea: git init && git add . && git commit -m"Subida inicial del esqueleto del proyecto"
    * Pega en la consola las líneas que copiaste de GitHub antes:
        git remote add origin https://github.com/juananruiz/symfony-expres.git
        git push -u origin master
    * Ve a la web de github y comprueba que tu repositorio allí contiene los ficheros de aquí
    *
5. Gracias por llegar hasta aquí, espero que te haya sido útil, dime si quieres que aclare algo, 
    o si te gustaría que hablara de algún tema relacionado,
    ...y si no te has quedado dormido sobre el teclado puedes darle al like
