# Ejercicio-git-libro

<div align="justify">

## - Ejercicio 1.

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

----


## -Ejercicio 2.

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

----

## -Ejercicio 3.

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

ro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git diff
diff --git a/README.md b/README.md
index 4780265..78c4b1b 100644
--- a/README.md
+++ b/README.md
@@ -104,5 +104,43 @@ Date:   Mon Oct 14 13:11:41 2024 +0100
 pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ cat > capitulos/capitulo3.txt
 
 
+### Se hace un *"commit"* sobre los cambios.
+
+```bash
+pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git commit -m "Añadido capítulo 3."
+[main d0c568a] Añadido capítulo 3.
+ 2 files changed, 41 insertions(+)
+ create mode 100644 capitulos/capitulo3.txt
+ ```
+
+ ### Se muestran los cambios con *"git log"*.
+
+ ```bash
+pro@jpexposito-VirtualBox:~/Repositorios GitHub/ejercicio-git-libro$ git log
+commit d0c568ac0c2644688ab429890e31478ce2fa970b (HEAD -> main)
+Author: cdiagal <cdiagalprog@gmail.com>
+Date:   Mon Oct 14 13:29:25 2024 +0100
+
+    Añadido capítulo 3.
+
+commit d2da64531b3d32eba8f48bb1585449d2bf7ff581
+Author: cdiagal <cdiagalprog@gmail.com>
+Date:   Mon Oct 14 13:22:28 2024 +0100
+
+    Añadido capítulo 2.
+
+commit eb84bae5c13a559c1526559892ec7bc256235d72
+Author: cdiagal <cdiagalprog@gmail.com>
+Date:   Mon Oct 14 13:11:41 2024 +0100
+
+    Añadido capítulos 1.
+
+commit 6bd9a0fb2867d7afc0e44b3c0e15301598322683 (origin/main, origin/HEAD)
+Author: cdiagal <cdiagalprog@gmail.com>
+Date:   Mon Oct 14 12:56:25 2024 +0100
+
+    Initial commit
+```
+

```

---

## -Ejercicio 4.

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

---

## -Ejercicio 5.

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

## -Ejercicio 6.

### Se crea un 



