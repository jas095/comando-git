# comando-git
Recomendaciones de <b>Github</b> para el manejar de los repositorios mediante algunos comandos.


We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# my-app" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/username/my-app.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/username/my-app.git
git push -u origin master

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
