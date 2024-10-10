# ejercicio-git-branch2
## Realiza una clonación del repositorio. Recuerda que debes utilizar git clone.
```code
bae2@jpexposito-VirtualBox:~$ git clone https://github.com/Brayan-PD/ejercicio-git-branch2
Clonando en 'ejercicio-git-branch2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Recibiendo objetos: 100% (3/3), listo.
```
## Crea un nuevo brancho rama para los nuevos cambios que vas a introducir.
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$  git checkout -b ejercicio1-branch
Cambiado a nueva rama 'ejercicio1-branch'
```
## Añade la siguiente clase al repositorio:
```code
     public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```
## Hacer commit de los cambios
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git commit -m "Se incluye el Ejercicio1.java"
En la rama ejercicio1-branch
Cambios no rastreados para el commit:
  (usa "git add <archivo>..." para actualizar lo que será confirmado)
  (usa "git restore <archivo>..." para descartar los cambios en el directorio de trabajo)
        modificados:     README.md

Archivos sin seguimiento:
  (usa "git add <archivo>..." para incluirlo a lo que será confirmado)
        ejercicio1.java

sin cambios agregados al commit (usa "git add" y/o "git commit -a")
```
## Sube los cambios a tu repositorio
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git push origin ejercicio1-branch
Total 0 (delta 0), reusados 0 (delta 0), pack-reusados 0
remote: 
remote: Create a pull request for 'ejercicio1-branch' on GitHub by visiting:
remote:      https://github.com/Brayan-PD/ejercicio-git-branch2/pull/new/ejercicio1-branch
remote: 
To https://github.com/Brayan-PD/ejercicio-git-branch2
 * [new branch]      ejercicio1-branch -> ejercicio1-branch
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git add .
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git push origin ejercicio1-branch
```
## comando que tuve que hacer para subir los datos
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git push --set-upstream origin ejercicio1-branch
Enumerando objetos: 6, listo.
Contando objetos: 100% (6/6), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (4/4), listo.
Escribiendo objetos: 100% (4/4), 877 bytes | 438.00 KiB/s, listo.
Total 4 (delta 0), reusados 0 (delta 0), pack-reusados 0
To https://github.com/Brayan-PD/ejercicio-git-branch2
   4576c5e..1b97dbb  ejercicio1-branch -> ejercicio1-branch
Rama 'ejercicio1-branch' configurada para hacer seguimiento a la rama remota 'ejercicio1-branch' de 'origin'.
```
## Se vuelven hacer los pasos, creamos el nuevo branch
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$  git checkout -b ejercicio2-branch
Cambiado a nueva rama 'ejercicio2-branch'
```
## Añade la siguiente clase al repositorio:
```code
     public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```
## Hacer un add 
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git add .
```
## Hacer commit de los cambios
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git commit -m "Se incluye el Ejercicio2.java"
[ejercicio2-branch e8857f3] Se incluye el Ejercicio2.java
 2 files changed, 26 insertions(+)
 create mode 100644 ejercicio2.java
```
## Sube los cambios a tu repositorio
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git push origin ejercicio2-branch
Enumerando objetos: 6, listo.
Contando objetos: 100% (6/6), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (4/4), listo.
Escribiendo objetos: 100% (4/4), 571 bytes | 571.00 KiB/s, listo.
Total 4 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ejercicio2-branch' on GitHub by visiting:
remote:      https://github.com/Brayan-PD/ejercicio-git-branch2/pull/new/ejercicio2-branch
remote: 
To https://github.com/Brayan-PD/ejercicio-git-branch2
 * [new branch]      ejercicio2-branch -> ejercicio2-branch
```
## Crea un nuevo branch o rama para los nuevos cambios que vas a introducir.
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git checkout -b  ejercicio3-branch 
Cambiado a nueva rama 'ejercicio3-branch'
```
## Se añade el ejercicio3.java
```code
     public class Ejercicio1 {
     public static void main(String[] args) {
         System.out.println("Ejercicio 1 realizado.");
     }
 }    
```
## Se hace un add
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git add .
```
## Se hace un commit
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git commit -m "Se incluye el Ejercicio3.java"
[ejercicio3-branch 4dbed5c] Se incluye el Ejercicio3.java
 2 files changed, 24 insertions(+), 1 deletion(-)
 create mode 100644 ejercicio3.java
```
## Se sube los cambios 
```code
bae2@jpexposito-VirtualBox:~/ejercicio-git-branch2$ git push origin ejercicio3-branch
Enumerando objetos: 5, listo.
Contando objetos: 100% (5/5), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (3/3), listo.
Escribiendo objetos: 100% (3/3), 487 bytes | 487.00 KiB/s, listo.
Total 3 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ejercicio3-branch' on GitHub by visiting:
remote:      https://github.com/Brayan-PD/ejercicio-git-branch2/pull/new/ejercicio3-branch
remote: 
To https://github.com/Brayan-PD/ejercicio-git-branch2
 * [new branch]      ejercicio3-branch -> ejercicio3-branch
```