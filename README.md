# Ejercicio-git-libro <img src="logomark-orange@2x.png" width="25"/>

<div align="justify">

## - Ejercicio 1.

<details>
    <summary>Clic para ver el contenido</summary>

### Crear la carpeta *Capítulos* y crear dentro el fichero *capítulo1.txt*.


```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit 6bd9a0fb2867d7afc0e44b3c0e15301598322683 (HEAD -> main, origin/main, origin/HEAD)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 12:56:25 2024 +0100

    Initial commit
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ mkdir capitulos
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > capitulos/capitulo1.txt

```


### Se hace un *"commit"* sobre los cambios.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadido capítulos 1."
[main eb84bae] Añadido capítulos 1.
 2 files changed, 20 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
 create mode 100644 capitulos/capitulo1.txt
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit eb84bae5c13a559c1526559892ec7bc256235d72 (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:11:41 2024 +0100

    Añadido capítulos 1.

commit 6bd9a0fb2867d7afc0e44b3c0e15301598322683 (origin/main, origin/HEAD)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 12:56:25 2024 +0100

    Initial commit
```
### Se muestran los cambios con *"git log"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit eb84bae5c13a559c1526559892ec7bc256235d72 (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:11:41 2024 +0100

    Añadido capítulos 1.

commit 6bd9a0fb2867d7afc0e44b3c0e15301598322683 (origin/main, origin/HEAD)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 12:56:25 2024 +0100

    Initial commit
```
</details>

----


## - Ejercicio 2.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea el fichero *"capítulo2.txt"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > capitulos/capitulo2.txt
```
### Se hace un *"commit"* sobre los cambios.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadido capítulo 2."
[main d2da645] Añadido capítulo 2.
 3 files changed, 57 insertions(+)
 create mode 100644 capitulos/capitulo2.txt
 ```

 ### Se muestran los cambios con *"git log"*.

 ```bash
 pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit d2da64531b3d32eba8f48bb1585449d2bf7ff581 (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:22:28 2024 +0100

    Añadido capítulo 2.

commit eb84bae5c13a559c1526559892ec7bc256235d72
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:11:41 2024 +0100

    Añadido capítulos 1.
```
</details>

----

## - Ejercicio 3.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea el fichero *"capítulo3.txt"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > capitulos/capitulo3.txt
```

### Se hace un *"commit"* sobre los cambios.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadido capítulo 3."
[main d0c568a] Añadido capítulo 3.
 2 files changed, 41 insertions(+)
 create mode 100644 capitulos/capitulo3.txt
 ```

 ### Se muestran los cambios con *"git log"*.

 ```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit d0c568ac0c2644688ab429890e31478ce2fa970b (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:29:25 2024 +0100

    Añadido capítulo 3.

commit d2da64531b3d32eba8f48bb1585449d2bf7ff581
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:22:28 2024 +0100

    Añadido capítulo 2.

commit eb84bae5c13a559c1526559892ec7bc256235d72
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 13:11:41 2024 +0100

    Añadido capítulos 1.

commit 6bd9a0fb2867d7afc0e44b3c0e15301598322683 (origin/main, origin/HEAD)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Mon Oct 14 12:56:25 2024 +0100

    Initial commit
```
### Se hace un *"git diff"*.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git diff 6bd9a0fb2867d7afc0e44b3c0e15301598322683..HEAD
diff --git a/README.md b/README.md
index 9a06b52..d05f9f3 100644
--- a/README.md
+++ b/README.md
@@ -1 +1,301 @@
-# ejercicio-git-libro
\ No newline at end of file
+# Ejercicio-git-libro
+
+<div align="justify">
+
+## - Ejercicio 1.

```

</details>

---

## - Ejercicio 4.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea el fichero *"índice.txt"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > indice.txt
```
### Se añaden cambios y se hace un *"commit"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Se crea índice."
[main bc12be7] Se crea índice.
 2 files changed, 99 insertions(+)
 create mode 100644 indice.txt
 ```

 ###  Se hace un *"echo"*.

 ```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ echo "Indice de los capítulos, con conceptos avanzados de git" >> indice.txt
```

### Se añaden los cambios a la zona de trabajo temporal, se vuelve a hacer un *"commit"* y se muestra quién ha hecho los cambios en el fichero con un *"git annotate"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadido el índice."
[main ff66f14] Añadido el índice.
 1 file changed, 1 insertion(+), 1 deletion(-)
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git annotate indice.txt
ff66f149        (   cdiagal     2024-10-14 13:41:12 +0100       1)Indice de los cápitulos, con conceptos avanzados de git.Indice de los capítulos, con conceptos avanzados de git.
```

</details>

---

## - Ejercicio 5.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea una nueva rama llamada "bibliografía".

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git checkout -b bibliografía                                                
Cambiado a nueva rama 'bibliografía'
```

### Se añaden los cambios a la zona de trabajo temporal, se hace un *"commit"* y se hace un *"push"* para actualizar todo el trabajo en la nube.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Se crea la rama bibliografía"
[bibliografía a6f3b6f] Se crea la rama bibliografía
 1 file changed, 40 insertions(+)
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git push --set-upstream origin bibliografía
Enumerando objetos: 28, listo.
Contando objetos: 100% (28/28), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (24/24), listo.
Escribiendo objetos: 100% (26/26), 3.41 KiB | 873.00 KiB/s, listo.
Total 26 (delta 7), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (7/7), done.
remote: 
remote: Create a pull request for 'bibliografía' on GitHub by visiting:
remote:      https://github.com/Cdiagal/ejercicio-git-libro/pull/new/bibliograf%C3%ADa
remote: 
To https://github.com/Cdiagal/ejercicio-git-libro
 * [new branch]      bibliografía -> bibliografía
Rama 'bibliografía' configurada para hacer seguimiento a la rama remota 'bibliografía' de 'origin'.
```

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git branch -av
* bibliografía                a6f3b6f Se crea la rama bibliografía
  main                        ff66f14 [adelante 5] Añadido el índice.
  remotes/origin/HEAD         -> origin/main
  remotes/origin/bibliografía a6f3b6f Se crea la rama bibliografía
  remotes/origin/main         6bd9a0f Initial commit
```

### Se añade el contenido de la rama *"bibliografía"* con la rama "*main*" mediante un "git merge" y posteriormente se documenta el cambio con un "*commit*" y git push.

```bash
bae2@jpexposito-VirtualBox:~/ejercicio-git-libro/ejercicio-git-libro$ git add .
bae2@jpexposito-VirtualBox:~/ejercicio-git-libro/ejercicio-git-libro$ git commit -m "Se genera un git merge a la rama principal"
[main c0f9a30] Se genera un git merge a la rama principal
 1 file changed, 4 insertions(+)
bae2@jpexposito-VirtualBox:~/ejercicio-git-libro/ejercicio-git-libro$ git push
Enumerando objetos: 9, listo.
Contando objetos: 100% (9/9), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (5/5), listo.
Escribiendo objetos: 100% (5/5), 798 bytes | 798.00 KiB/s, listo.
Total 5 (delta 1), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Cdiagal/ejercicio-git-libro
   7a47ea7..c0f9a30  main -> main
```
</details>

---

## - Ejercicio 6.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea el fichero *"capítulos/capítulo4.txt"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > capitulos/capitulo4.txt         
En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto.

```

### Se hace un commit con el mensaje *"Añadido capítulo 4"* y se actualiza en la nube.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Se añade el capítulo 4"
[main eeac524] Se añade el capítulo 4
 2 files changed, 22 insertions(+), 43 deletions(-)
 create mode 100644 capitulos/capitulo4.txt
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git push
Enumerando objetos: 8, listo.
Contando objetos: 100% (8/8), listo.
Compresión delta usando hasta 4 hilos
Comprimiendo objetos: 100% (4/4), listo.
Escribiendo objetos: 100% (5/5), 705 bytes | 352.00 KiB/s, listo.
Total 5 (delta 2), reusados 0 (delta 0), pack-reusados 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Cdiagal/ejercicio-git-libro
   b7c1296..eeac524  main -> main
```

### Se ejecuta el comando *"git log --graph --all --oneline"* para mostrar la historia del repositorio incluyendo todas las ramas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log --graph --all --oneline
* 9a62fed (HEAD -> main, origin/main, origin/HEAD) Se hacen nuevas modificaciones para subsanar errores
* eeac524 Se añade el capítulo 4
* b7c1296 Se hace merge
* c0f9a30 Se genera un git merge a la rama principal
*   08f5431 Merge branch 'bibliografía'
|\  
| * c8da4bf (origin/bibliografía, bibliografía) Se genera el último cambio
| * a6f3b6f Se crea la rama bibliografía
* | 7a47ea7 cambios en capitulo2.txt
|/  
* ff66f14 Añadido el índice.
* bc12be7 Se crea índice.
* d0c568a Añadido capítulo 3.
* d2da645 Añadido capítulo 2.
* eb84bae Añadido capítulos 1.
* 6bd9a0f Initial commit

```
</details>

---


## - Ejercicio 7.

<details>
    <summary>Clic para ver el contenido</summary>

### Se cabmia a la rama bibliografía y se crea el fichero *"bibliografía.txt"* añadiendo la referencia descrita en las indicaciones.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git branch            
* bibliografía
  main
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > bibliografia.txt
Chacon, S. and Straub, B. Pro Git. Apress.

```

### Se hace un commit con el comentario descrito y se muestra el historial del repositorio incluyendo todas las ramas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadida la primera referencia bibliográfica"
[bibliografía 8a9200e] Añadida la primera referencia bibliográfica
 1 file changed, 1 insertion(+)
 create mode 100644 bibliografia.txt
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log --graph --all --oneline                            
* 8a9200e (HEAD -> bibliografía) Añadida la primera referencia bibliográfica
| * 9eb7e43 (origin/main, origin/HEAD, main) se ejecuta git log --graph --all --oneline y se cambia de rama a bibliografía
| * 9a62fed Se hacen nuevas modificaciones para subsanar errores
| * eeac524 Se añade el capítulo 4
| * b7c1296 Se hace merge
| * c0f9a30 Se genera un git merge a la rama principal
| *   08f5431 Merge branch 'bibliografía'
| |\  
| |/  
|/|   
* | c8da4bf (origin/bibliografía) Se genera el último cambio
* | a6f3b6f Se crea la rama bibliografía
| * 7a47ea7 cambios en capitulo2.txt
|/  
* ff66f14 Añadido el índice.
* bc12be7 Se crea índice.
* d0c568a Añadido capítulo 3.
* d2da645 Añadido capítulo 2.
* eb84bae Añadido capítulos 1.
* 6bd9a0f Initial commit

```

</details>

---

## - Ejercicio 8.

<details>
    <summary>Clic para ver el contenido</summary>

### Se fusiona la rama bibliografía con la rama main y se muestra la historia del repositorio incluyendo todas las ramas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log --graph --all --oneline                                    
*   8527db4 (HEAD -> main) Merge branch 'bibliografía'
|\  
| * 8a9200e (bibliografía) Añadida la primera referencia bibliográfica
* | 6a99125 se añaden las indicaciones del ejercicio7 en README
* | 9eb7e43 (origin/main, origin/HEAD) se ejecuta git log --graph --all --oneline y se cambia de rama a bibliografía
* | 9a62fed Se hacen nuevas modificaciones para subsanar errores
* | eeac524 Se añade el capítulo 4
* | b7c1296 Se hace merge
* | c0f9a30 Se genera un git merge a la rama principal
* | 08f5431 Merge branch 'bibliografía'
|\| 
| * c8da4bf (origin/bibliografía) Se genera el último cambio

```

### Se elimina la rama bibliografía.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git branch -D bibliografía
Eliminada la rama bibliografía (era 8a9200e).

```

### Se muestran los resultados de la historia del repositorio incluyendo todas las ramas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log --graph --all --oneline
*   8527db4 (HEAD -> main) Merge branch 'bibliografía'
|\  
| * 8a9200e Añadida la primera referencia bibliográfica
* | 6a99125 se añaden las indicaciones del ejercicio7 en README
* | 9eb7e43 (origin/main, origin/HEAD) se ejecuta git log --graph --all --oneline y se cambia de rama a bibliografía
* | 9a62fed Se hacen nuevas modificaciones para subsanar errores
* | eeac524 Se añade el capítulo 4
* | b7c1296 Se hace merge
* | c0f9a30 Se genera un git merge a la rama principal
* | 08f5431 Merge branch 'bibliografía'
|\| 
| * c8da4bf (origin/bibliografía) Se genera el último cambio
| * a6f3b6f Se crea la rama bibliografía
* | 7a47ea7 cambios en capitulo2.txt
|/  
* ff66f14 Añadido el índice.
* bc12be7 Se crea índice.
* d0c568a Añadido capítulo 3.
* d2da645 Añadido capítulo 2.
* eb84bae Añadido capítulos 1.
* 6bd9a0f Initial commit

```

</details>

---

## - Ejercicio 9.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea la rama bibliografía y se cambia a la misma.

```bash 

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git checkout -b bibliografía
Cambiado a nueva rama 'bibliografía'

```

### Se cambia el fichero *"bibliografía.txt"* añadiendo las referencias indicadas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > bibliografia.txt
Chacon, S. and Straub, B. Pro Git. Apress.
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.

```

### Se añaden los cambios a la zona de intercambio temporal y se hace un commit.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadida nueva referencia bibliográfica"
[bibliografía c264086] Añadida nueva referencia bibliográfica
 2 files changed, 107 insertions(+), 1 deletion(-)

```

### Se cambia a la rama principal y se fusiona la rama *"bibliografía"* con la rama *"main"*.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git checkout main
Cambiado a rama 'main'
Tu rama está adelantada a 'origin/main' por 3 commits.
  (usa "git push" para publicar tus commits locales)
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git merge bibliografía
Actualizando 8527db4..f60bfff
Fast-forward
 README.md        | 106 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 bibliografia.txt |   3 +++
 2 files changed, 108 insertions(+), 1 deletion(-)

```

### Se resuelve el conflicto dejando el fichero *"bibliografia.txt"* con las nuevas referencias.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > bibliografía.txt
Chacon, S. and Straub, B. Pro Git. Apress.
Loeliger, J. and McCullough, M. Version control with Git. O’Reilly.
Hodson, R. Ry’s Git Tutorial. Smashwords (2014)

```

### Se añaden los cambios a la zona de intercambio temporal y se hace un commit con el mensaje indicado.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add .
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Resuelto conflicto de bibliografía"
[main dd176ca] Resuelto conflicto de bibliografía
 2 files changed, 41 insertions(+)
 create mode 100644 "bibliograf\303\255a.txt"

```

### Se muestra la historia del repositorio incluyendo todas las ramas.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log --graph --all --oneline
* dd176ca (HEAD -> main) Resuelto conflicto de bibliografía
* f60bfff (bibliografía) Se corrigen errores para cambiar de rama y generar fusión
* c264086 Añadida nueva referencia bibliográfica
*   8527db4 Merge branch 'bibliografía'
|\  
| * 8a9200e Añadida la primera referencia bibliográfica
* | 6a99125 se añaden las indicaciones del ejercicio7 en README
* | 9eb7e43 (origin/main, origin/HEAD) se ejecuta git log --graph --all --oneline y se cambia de rama a bibliografía
* | 9a62fed Se hacen nuevas modificaciones para subsanar errores
* | eeac524 Se añade el capítulo 4
* | b7c1296 Se hace merge
* | c0f9a30 Se genera un git merge a la rama principal

```
</details>


# Ejercicio-git-tag

## - Ejercicio 1.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crean etiquetas para luego enviarla al repositorio remoto y se muestra la lista de etiquetas presentes en el repositorio usando *"git tag"*.

```bash
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git tag
1.0.0
1.0.1

```
</details>

--- 

## - Ejercicio 2.

<details>
    <summary>Clic para ver el contenido</summary>

### Se hace un cambio añadiendo una línea en el archivo "capítulo1.txt" y se genera un commit. Luego se revierte con *"git revert"* y se muestra el resultado con *"git log"*.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit d29f20a382c029a8465058fb6251aaa41b502200 (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Wed Oct 23 22:45:57 2024 +0100

    Revert "Se agrega una línea en el capítulo1"
    
    This reverts commit 3e4c36d317f9a4aecf7f81c7bf6d9c3c7deea495.

commit 3e4c36d317f9a4aecf7f81c7bf6d9c3c7deea495
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Wed Oct 23 22:45:19 2024 +0100

```
</details>

--- 

## - Ejercicio 3.

<details>
    <summary>Clic para ver el contenido</summary>

### Se crea una nueva rama llamada "nueva-funcionalidad", se añade el archivo "capitulo5.txt" con una línea de texto de contenido.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git checkout -b "nueva-funcionalidad"
Cambiado a nueva rama 'nueva-funcionalidad'
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git branch
  bibliografía
  main
* nueva-funcionalidad

```

### Se realiza un commit.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git add . 
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Se crea nueva rama y archivo capitulo5.txt"
[nueva-funcionalidad 6bee86b] Se crea nueva rama y archivo capitulo5.txt
 2 files changed, 41 insertions(+), 1 deletion(-)
 create mode 100644 capitulos/capitulo5.txt

```


### Se vuelve a la rama main y se usa *"git cherry-pick"* para aplicar el commit de la rama "nueva-funcionalidad" en "main".

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Se crea una nueva rama y archivo capitulo5.1.txt" 
[nueva-funcionalidad 34bf73f] Se crea una nueva rama y archivo capitulo5.1.txt
 1 file changed, 25 insertions(+)
pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git checkout main
Cambiado a rama 'main'


pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git cherry-pick 6bee86bf180ab7cddcf3efab2fda53d5e9945e44
[main 3206924] Se crea nueva rama y archivo capitulo5.txt
 Date: Wed Oct 23 22:56:47 2024 +0100
 2 files changed, 41 insertions(+), 1 deletion(-)
 create mode 100644 capitulos/capitulo5.txt

```

---

### Se muestra el historial de la rama main para comprobar que el commit ha sido agregado.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
commit 3206924de2739175bdc40adef1955759bb3e3d74 (HEAD -> main)
Author: cdiagal <cdiagalprog@gmail.com>
Date:   Wed Oct 23 22:56:47 2024 +0100

         Se crea nueva rama y archivo capitulo5.txt
```


## - Ejercicio 4.

<details>
    <summary>Clic para ver el contenido</summary>

### Se pasa a la rama "main" y se añade al archivo "README.md", ciertas descripciones como pueden ser esta.

```bash

pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git branch
  bibliografía
* main
  nueva-funcionalidad

```

</details>
