# Informe-Git-y-GitHub
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/6c91fc01-8d87-468c-b7f9-237bc6648478" />


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

- Este comando conecta el repositorio local con tu repositorio remoto en GitHub, el cual le asigna el nombre origin para poder subir o actualizar cambios de él.
<img width="502" height="33" alt="image" src="https://github.com/user-attachments/assets/2e13ff46-705f-4943-adae-1afb30a71c1b" />

- Este comando sube el proyecto local al repositorio remoto por primera vez y vincula la rama local master con la rama remota para futuras actualizaciones.
<img width="478" height="186" alt="image" src="https://github.com/user-attachments/assets/833163df-11c6-4a94-ac9d-1720252546ff" />

- Crea una nueva rama (puede ser cualquier nombre que pongas) y cambia a ella para trabajar de forma independiente sin afectar la rama principal.
  <img width="528" height="55" alt="image" src="https://github.com/user-attachments/assets/2e89662c-f608-41ff-9c27-dfff8d6af914" />

  - Envía la nueva rama (ramaC en mi caso) al repositorio remoto y la deja conectada.
    <img width="566" height="150" alt="image" src="https://github.com/user-attachments/assets/c4b9c52e-6cf0-4980-8eb3-08929e733ef4" />

  - Ya una vez hayas hecho lo anterior, al recargar la página de github, ya aparecerían los archivos subidos a tu repositorio GitHub.
    <img width="1258" height="442" alt="image" src="https://github.com/user-attachments/assets/2beddd82-0129-4964-ba74-c497c1516a85" />

  - Te aparecera esta opción la cuál es para cambiar de la rama principal a otras ramas que tu hayas creado aparte, como puedes ver yo cree la ramaC.
    <img width="416" height="345" alt="image" src="https://github.com/user-attachments/assets/fca139a7-a77a-4f45-84d1-e9115462e712" />
- Cómo ves, al seleccionar otra rama, aparecerán los archivos y el proyecto que trabajaste desde esa rama, sin afectar la rama principal que en mi caso es el master.
<img width="932" height="436" alt="image" src="https://github.com/user-attachments/assets/68ccd538-edb8-460a-8a2d-47aa51f9cd93" />




