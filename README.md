## TP1 SO1

## Instalación de Ubuntu
Ya tenpia instalada una VM con Oracle VMB que empleo para usar Docker y K8S por ende voy a usar esa VM directamente para no tener que instalar otra


## Editores de C
Conozco varios como por ejemplo CodeBlocks y Eclipse pero generalmente Eclipse no funciona bien de entrada por lo tanto tome la determinacion de usar geany y luego compilaré por terminal por ahora

sudo apt-get install geany


## Git

Emplearé Github Desktop ya que lo uso en el día a día y son menos los comandos que necesito acordarme para usarlo y me agiliza el procesó de commits

sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.6.3-linux1/GitHubDesktop-linux-2.6.3-linux1.deb

sudo apt-get install gdebi-core

sudo gdebi GitHubDesktop-linux-2.6.3-linux1.deb


## Lo deje por las dudas...
…or create a new repository on the command line
echo "# laboratorio-1-RugenKunkka" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ICOMP-UNC/laboratorio-1-RugenKunkka.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/ICOMP-UNC/laboratorio-1-RugenKunkka.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project...
