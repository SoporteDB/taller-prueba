# taller-prueba
#comando basicos de git:

git init                         # Inicializa un nuevo repositorio
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"
git config --list                # Muestra la configuración actual

git clone <url>                  # Clona un repositorio remoto
git remote -v                    # Muestra los remotos configurados
git remote add origin <url>     # Agrega un repositorio remoto
git remote remove origin        # Elimina el remoto llamado "origin"

git status                       # Muestra archivos modificados/no agregados
git add <archivo>                # Agrega un archivo al staging area
git add .                        # Agrega todos los archivos modificados
git commit -m "Mensaje"          # Guarda los cambios en el repositorio
git commit -am "Mensaje"         # Agrega y commitea (solo para archivos ya seguidos)
git diff                         # Muestra diferencias entre archivos modificados
git log                          # Muestra el historial de commits

git pull                         # Descarga y fusiona los cambios remotos
git push                         # Envía tus cambios al repositorio remoto
git push -u origin main          # Asocia la rama actual con la remota

git branch                       # Lista las ramas
git branch <nombre>              # Crea una nueva rama
git checkout <rama>              # Cambia a otra rama
git switch <rama>                # Alternativa moderna a checkout
git checkout -b <rama>           # Crea y cambia a una rama nueva
git merge <rama>                 # Fusiona la rama indicada con la actual
git branch -d <rama>             # Elimina una rama local

git stash                        # Guarda cambios sin hacer commit
git stash pop                    # Restaura los cambios guardados
git reset --hard HEAD            # Revierte todos los cambios al último commit
git clean -fd                    # Elimina archivos no rastreados
git revert <hash>                # Crea un commit que revierte un cambio específico

git log --oneline --graph        # Historial compacto y visual
git show <hash>                  # Muestra los detalles de un commit
git diff <rama1> <rama2>         # Compara ramas

git config --global credential.helper store      # Guarda credenciales en texto plano (inseguro)
git config --global credential.helper cache      # Guarda en memoria temporalmente

git tag <nombre>                 # Crea un tag (versión)
git fetch                        # Trae cambios remotos sin fusionar
git rebase <rama>                # Reescribe el historial sobre otra rama
