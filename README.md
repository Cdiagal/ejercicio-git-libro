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




