USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación (main)
$ mkdir primerExamen

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación (main)
$ cd 'Examen Intro'
bash: cd: Examen Intro: No such file or directory

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación (main)
$ cd primerExamen

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mkdir 'Reino Animal' 'Reino Vegetal' 'Reino Mineral' 'Mascotas' 'Salvajes'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ touch Perro.txt León.txt Gato.txt Tomate.txt

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Perro.txt Gato.txt Mascotas

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Mascotas 'Reino Animal"
> ^C

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Gato.txt Perro.txt ../'Reino Animal'
mv: target '../Reino Animal' is not a directory

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Gato.txt Perro.txt ../
mv: cannot stat 'Gato.txt': No such file or directory
mv: cannot stat 'Perro.txt': No such file or directory
USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ cd Mascotas

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Mascotas (main) 
$ mv Gato.txt Perro.txt ../'Reino Animal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Mascotas (main) 
$ cd ../

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Mascotas 'Reino Animal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ cd 'Reino Animal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Reino Animal (main)
$ mv Gato.txt Perro.txt Mascotas

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Reino Animal (main)
$ cd ../

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Salvajes 'Reino Animal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv León.txt 'Reino Animal'/Salvajes

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ mv Tomate.txt 'Reino Vegetal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ touch Jirafa.txt 'Reino Animal'/Salvajes

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ touch 'Reino Animal'/Salvajes Jirafa.txt

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ touch 'Reino Animal'/Salvajes/Jirafa.txt

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ cd 'Reino Animal'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Reino Animal (main)
$ rm -r Mascotas
rm: cannot remove 'Mascotas/Gato.txt': Permission denied
rm: cannot remove 'Mascotas/Perro.txt': Permission denied

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Reino Animal (main)
$ rm -r Mascotas

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen/Reino Animal (main)
$ cd ../

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ ls -r
'Reino Vegetal'/  'Reino Mineral'/  'Reino Animal'/

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ ls -R
.:
'Reino Animal'/  'Reino Mineral'/  'Reino Vegetal'/

'./Reino Animal':
Salvajes/

'./Reino Animal/Salvajes':
Jirafa.txt  León.txt

'./Reino Mineral':

'./Reino Vegetal':
Tomate.txt

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ pwd
/c/Users/USUARIO/Desktop/Examen Introduccion a la prgramación/primerExamen

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git init
Initialized empty Git repository in C:/Users/USUARIO/Desktop/Examen Introduccion a la prgramación/primerExamen/.git/

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git config user.name “juancarlosp94"
> ^C

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git config user.name juancarlosp94

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be 
committed)
        Reino Animal/
        Reino Vegetal/

nothing added to commit but untracked files present (use "git add" to track)

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git remote add origin https://github.com/juancarlosp94/PrimerExamenPerdigonJuan.git

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be 
committed)
        Reino Animal/
        Reino Vegetal/

nothing added to commit but untracked files present (use "git add" to track)

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git add .

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git commit -m 'Primer commit'
[main (root-commit) e0426b7] Primer commit
 3 files changed, 0 insertions(+), 0 deletions(-)     
 create mode 100644 Reino Animal/Salvajes/Jirafa.txt  
 create mode 100644 "Reino Animal/Salvajes/Le\303\263n.txt"
 create mode 100644 Reino Vegetal/Tomate.txt

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 396 bytes | 49.00 KiB/s, 
done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0  
To https://github.com/juancarlosp94/PrimerExamenPerdigonJuan.git
 * [new branch]      main -> main

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (main)
$ git checkout -b desarrollo
Switched to a new branch 'desarrollo'

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (desarrollo)    
$ git commit -m 'nueva rama'
On branch desarrollo
nothing to commit, working tree clean

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (desarrollo)    
$ touch Readme.md

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (desarrollo)    
$ git add .

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (desarrollo)
$ git commit -m 'commit desarrollo'
[desarrollo bea23aa] commit desarrollo
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Readme.md

USUARIO@DESKTOP-6S0PIL6 MINGW64 ~/Desktop/Examen Introduccion a la prgramación/primerExamen (desarrollo)
$ git push origin desarrollo
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 77.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'desarrollo' on GitHub by visiting:
remote:      https://github.com/juancarlosp94/PrimerExamenPerdigonJuan/pull/new/desarrollo
remote:
To https://github.com/juancarlosp94/PrimerExamenPerdigonJuan.git
 * [new branch]      desarrollo -> desarrollo
