# Informe-Git-y-GitHub
Informe sobre Git y Git Hub
<img width="347" height="145" alt="download" src="https://github.com/user-attachments/assets/3872a962-988c-4eb5-8467-cd60e014b3db" />
 Instrucciones:

- Mira atentamente los dos videos asignados sobre Git y GitHub.

- Crea un archivo README.md donde expliques, con tus propias palabras:

- Los principales comandos de Git (por ejemplo: git init, git add, git commit, git push, etc.).

- El proceso paso a paso para enviar tus cambios a un repositorio en GitHub.

- Incluye capturas de pantalla que evidencien cada etapa del proceso.

- Sube tu informe al repositorio de GitHub y comparte el enlace como entrega.



Principales comandos de Git: 
Informe sobre Git y GitHub
📌 Introducción

Este informe resume, con mis propias palabras, los principales comandos de Git y el proceso paso a paso para enviar cambios a un repositorio en GitHub. Más abajo encontrarás ejemplos de comandos, el flujo completo y plantillas para insertar las capturas de pantalla que evidencien cada etapa.

🔧 Principales comandos de Git
Comando	¿Qué hace?	Ejemplo
git init	Inicializa un repositorio Git en la carpeta actual.	git init
git status	Muestra el estado de archivos: modificados, en stage, sin trackear.	git status
git add <archivo> / git add .	Añade archivos al área de staging (prepara para commit).	git add README.md git add .
git commit -m "mensaje"	Crea un commit (registro) con los cambios en staging y un mensaje descriptivo.	git commit -m "Agrego README inicial"
git log	Muestra el historial de commits.	git log --oneline
git branch	Lista ramas locales o crea una nueva (git branch nombre).	git branch feature-x
git checkout <rama> / git switch <rama>	Cambia a otra rama.	git checkout main
git merge <rama>	Fusiona otra rama en la rama actual.	git merge feature-x
git remote add origin <URL>	Conecta el repositorio local con un remoto (ej.: GitHub).	git remote add origin https://github.com/usuario/repo.git
git push -u origin <rama>	Envía commits al repositorio remoto y enlaza la rama local con la remota.	git push -u origin main
git pull	Descarga y aplica cambios del remoto a la rama actual.	git pull origin main
git clone <URL>	Clona un repositorio remoto en tu máquina.	git clone https://github.com/usuario/repo.git
