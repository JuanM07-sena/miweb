# Informe-Git-y-GitHub
<img width="347" height="145" alt="download" src="https://github.com/user-attachments/assets/3872a962-988c-4eb5-8467-cd60e014b3db"/>

 > Instrucciones puestas por el instructor:

- Mira atentamente los dos videos asignados sobre Git y GitHub.

- Crea un archivo README.md donde expliques, con tus propias palabras:

- Los principales comandos de Git (por ejemplo: git init, git add, git commit, git push, etc.).

- El proceso paso a paso para enviar tus cambios a un repositorio en GitHub.

- Incluye capturas de pantalla que evidencien cada etapa del proceso.

- Sube tu informe al repositorio de GitHub y comparte el enlace como entrega.

## Introducción breve

Este informe resume algunos de los comandos de Git y el paso a paso para enviar cambios a un repositorio en GitHub vistos en los vídeos brindados por el instructor.


##  Principales comandos de Git

| **Comando de Git** | **Descripción del comando** |
|--------------|----------------|
| `git init` | Este comando inicia un nuevo repositorio local en la carpeta actual. |
| `git status` | Sirve par amostrar el estado actual de todos los archivos del proyecto. |
| `git add .` | Con este agregamos todos los archivos modificados al área de preparación. |
| `git commit -m "mensaje"` | Sirve para guardar los cambios con un mensaje el cual tiene que ser descriptivo. |
| `git branch` | Muestra las ramas disponibles en el repositorio. |
| `git checkout -b nombre-rama` | Crea una nueva rama y nos dirige a esa nueva rama. |
| `git remote add origin URL` | Nos conecta el repositorio local en donde estamos trabajando con uno en GitHub. |
| `git push -u origin main` | Envía los cambios al repositorio (github) en la rama principal (main). |
| `git pull` | Descarga y fusiona los últimos cambios del repositorio remoto. |

## Paso a paso para subir un repositorio de Git a GitHub

- Una vez tengas el repositorio local listo para subirlo a la nube, tienes que conectarlo al repositorio GitHub el cuál será con este comando, este comando sube el proyecto local al repositorio remoto en GitHub por primera vez y establece una conexión entre la rama local master(principal) y la rama remota(la de GitHub) para futuros envíos de cambios.
<img width="502" height="33" alt="image" src="https://github.com/user-attachments/assets/2e13ff46-705f-4943-adae-1afb30a71c1b" />

- Este comando sube el proyecto local al repositorio remoto por primera vez y vincula la rama local master con la rama remota para futuras actualizaciones.
<img width="478" height="186" alt="image" src="https://github.com/user-attachments/assets/833163df-11c6-4a94-ac9d-1720252546ff" />

- Crea una nueva rama llamada ramaC (puede ser cualquier nombre que pongas) y cambia a ella para trabajar de forma independiente sin afectar la rama principal.
  <img width="528" height="55" alt="image" src="https://github.com/user-attachments/assets/2e89662c-f608-41ff-9c27-dfff8d6af914" />

  - Envía la nueva rama ramaC al repositorio remoto y la deja conectada para sincronizar los cambios mejor.
    <img width="566" height="150" alt="image" src="https://github.com/user-attachments/assets/c4b9c52e-6cf0-4980-8eb3-08929e733ef4" />



