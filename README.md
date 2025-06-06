## Taller prueba
## 🟢 Inicialización y Configuración

- `git init` – Inicializa un nuevo repositorio local.
- `git config --global user.name "Tu Nombre"` – Configura tu nombre de usuario global.
- `git config --global user.email "tuemail@example.com"` – Configura tu correo electrónico global.
- `git config --list` – Muestra la configuración actual de Git.

## 📦 Repositorios Remotos

- `git clone <url>` – Clona un repositorio remoto existente.
- `git remote -v` – Muestra los remotos asociados al repositorio.
- `git remote add origin <url>` – Agrega un nuevo repositorio remoto con el nombre "origin".
- `git remote remove origin` – Elimina el remoto llamado "origin".

## 📝 Gestión de Cambios

- `git status` – Muestra los archivos modificados y en staging.
- `git add <archivo>` – Agrega un archivo al área de preparación.
- `git add .` – Agrega todos los archivos modificados.
- `git commit -m "mensaje"` – Registra los cambios con un mensaje.
- `git commit -am "mensaje"` – Agrega y commitea directamente archivos ya seguidos.
- `git diff` – Muestra las diferencias entre archivos.
- `git log` – Muestra el historial de commits.

## 🔁 Actualización y Envío

- `git pull` – Descarga y fusiona cambios del repositorio remoto.
- `git push` – Envía los commits locales al remoto.
- `git push -u origin main` – Asocia la rama actual con la rama "main" en el remoto.

## 🌿 Ramas (Branching)

- `git branch` – Lista todas las ramas.
- `git branch <nombre>` – Crea una nueva rama.
- `git checkout <rama>` – Cambia a una rama específica.
- `git switch <rama>` – Cambia a una rama (más moderno que checkout).
- `git checkout -b <rama>` – Crea y cambia a una nueva rama.
- `git merge <rama>` – Fusiona una rama con la actual.
- `git branch -d <rama>` – Elimina una rama local.

## 🚨 Manejo de Errores y Conflictos

- `git stash` – Guarda temporalmente cambios no commiteados.
- `git stash pop` – Aplica los cambios guardados con stash.
- `git reset --hard HEAD` – Revierte todos los cambios al último commit.
- `git clean -fd` – Elimina archivos/directorios no rastreados.
- `git revert <hash>` – Crea un nuevo commit que revierte un commit anterior.

## 🧪 Historial y Comparación

- `git log --oneline --graph` – Muestra el historial en una línea y en forma gráfica.
- `git show <hash>` – Muestra los detalles de un commit específico.
- `git diff <rama1> <rama2>` – Muestra las diferencias entre dos ramas.

## 🔒 Credenciales y Autenticación

- `git config --global credential.helper store` – Guarda credenciales en texto plano (no recomendado).
- `git config --global credential.helper cache` – Guarda las credenciales temporalmente en memoria.

## 🧰 Otros Comandos Útiles

- `git tag <nombre>` – Crea un tag (versión específica).
- `git fetch` – Descarga los cambios remotos sin fusionarlos.
- `git rebase <rama>` – Reescribe la historia de commits sobre otra rama.
