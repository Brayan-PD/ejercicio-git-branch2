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