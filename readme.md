# Ejercicios del curso de Confección de pag Web#

##Configuración del Entorno ##

- Navegador: Chrome, Firefox, Edge, Sa
- Editor de código: Visual Studio Code
    <https://code.visualstudio.com/>
- NodeJS /  npm
    <https://nodejs.org/es/>
- Servidor Web de desarrollo: http-server 
    nmp install -g http-server (en pantalla de sistema)
- Git
   <https://git-scm.com/>

CONFIGURACION DE GIT

- Definir usuario y correo
- En Pantalla de sistema:
   git config --global user.name <mi nombre de usuario de git>
   git config -- global user.email <mi correo en git>
- Comprobar la configuración
   git config -l --global
- Crear un repositorio(en Github)
  - De local a remoto
     git init <carpeta en la que estamos trabajando> hacerlo en una carpeta antes de la que queremos
    utilizar
    - Hacemos un primer comit y sincronizamos para que se publique
    - Comprobamos el commit
      git log
    - Crear un repositorio vacio en Github
    - Sincronizar repositorios siguiendo instruciones de Github
      git remote add origin http://github.com/<nombre repositorio>.git
      git push -u origin master

 - De remoto a local
   - Clonamos el repositorio
     git clone <repositor<.git

