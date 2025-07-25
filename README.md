# Actividad-1-Repositorio de Github

## Los pasos a realizar son:

1. Crear la carpeta del proyecto
2. Abrimos la carpeta en vscode
3. Trabajamos en los archivos, agregando lo necesario, instalando paquetes,etc
4. Creamos un archivo llamado .gitignore en el cual escribimos ahí el nombre de los archivos que NO queremos subir a la nube ya sea por razones de seguridad o privacidad
5. Abrimos la terminal o git bash y escribimos el siguiente comando para configurar nuestro usuario para que podamos subir cosas a github
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
6. Luego nos dirigimos a la carpeta raíz del archivo en el terminal o git bash, hacemos git init
7. Hacemos el siguiente comando para agregar los archivos nuevos: git add .
8. Escribimos en el terminal: git commit -m "Primer commit"
9. Creamos el repositorio en github
10. En github en el proyecto nos proporcionan un enlace, lo copiamos y realizamos el siguiente comando: git remote add origin https://github.com/tu-usuario/nombre-del-repo.git
11. Hacemos push con el siguiente comando: git push -u origin master, si la rama se llama main, entonces hacemos: git push -u origin main
