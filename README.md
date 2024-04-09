2a) El archivo .gitignore es para ignorar archivos, es decir estos archivos no seran incluidos en la colaboracion, 
tambien git no rastreara estos archivos.
    Este se debe incluir al iniciar un proyecto, al clonar un repositorio o al agregar nuevas blibliotecas a nuestro proyecto.
    PASOS:
1-touch .gitignore        (creamos el archivo en la raiz de nuestro repositorio)
2-nano .gitignore         (abre el archivo en el editor)
3-*.log                   (ignora todos los archivos con extension log)
  node_modules/           (ignora el directorio node_modules)
4-Ctrl + O                (para guardar)
5-git status              (verificamos como esta)
6-git add .gitignore      (Agrega el archivo .gitignore para ignorar archivos y directorios)
  git commit -m "mensaje xxx"
