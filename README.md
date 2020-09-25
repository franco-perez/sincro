# sincro

esto es para sincronizar la carpeta remota con la carpeta local.

paso 1) crear carpeta en local
paso 2) escoger tipo de protocolo (Http, SSH) yo escogi SSH para no tener que poner mi contrasena cada vez que modifique algo.
paso 3) seguir los comandos que a continuacion se enumeran:

echo "# sincro" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:franco-perez/sincro.git
git push -u origin master