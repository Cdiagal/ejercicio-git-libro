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




