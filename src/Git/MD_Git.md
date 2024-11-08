# Topics List

- 01 - Configuration Commands
- 02 - Commands List

![Header](./src/custom/img/00_commands.jpg)

---

## 01 - Configuration Commands

| Command                                    | Description                                                                 |
| :----------------------------------------: | :-------------------------------------------------------------------------: |
| `git config --list`                        | Muestra la configuración actual de Git                                      |
| `git config --global user.name "YourUserNickName"` | Configura el nombre de usuario global                                |
| `git config --global user.email "YourUserEmailName@Email.com"` | Configura el correo electrónico global                            |
| `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"` | Genera una clave SSH usando el correo electrónico para identificación |
| `ssh -T git@github.com`                    | Verifica la conexión SSH con GitHub                                         |
| `C:\Users\YourUserExamplePc\.ssh`          | Ubicación predeterminada de las claves SSH en Windows                       |
| `config` (SSH config file)                 | Archivo de configuración SSH personalizado para múltiples hosts             |

## Installation Steps

1. **Download Git:**
   - Go to: https://git-scm.com/downloads
   - Download and install the version for your OS. Use default options.
   
2. **Check current configuration:**
   - Use `git config --list` to see the current configuration.
   
3. **Set up your user details:**
   - Set global username and email using:
     - `git config --global user.name "YourUserNickName"`
     - `git config --global user.email "YourUserEmailName@Email.com"`

4. **Generate an SSH key:**
   - Generate an SSH key using your email for identification:
     - `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"`
   - Locate the file in the `.ssh` folder, e.g., `C:\Users\YourUserExamplePc\.ssh`.

5. **Add your SSH public key to GitHub:**
   - Add the generated SSH key to your GitHub account in the SSH settings.

6. **Verify the connection:**
   - Use the command `ssh -T git@github.com` to verify the SSH connection to GitHub.

---

## 02 - Commands List

| Command                                   | Description                                                       |
| :---------------------------------------: | :---------------------------------------------------------------- |
| `git branch nameNewBranch`                | Crea una nueva rama                                                |
| `git branch`                              | Lista todas las ramas locales                                      |
| `git branch -a`                           | Lista todas las ramas (locales y remotas)                          |
| `git branch -r`                           | Lista las ramas remotas                                            |
| `git branch -l`                           | Lista las ramas locales                                            |
| `git checkout`                            | Cambia a la rama indicada                                          |
| `git checkout -b nombre-de-la-rama`       | Crea y cambia a la rama nueva                                      |
| `git checkout nameBranch`                 | Cambia a la rama nombrada                                          |
| `git checkout develop`                    | Cambia a la rama 'develop'                                         |
| `git remote -v`                           | Ver el origen del repositorio remoto                               |
| `git log --oneline`                       | Ver el último commit                                               |
| `git log --oneline -5`                    | Ver los últimos 5 commits                                          |
| `git clone <URL>`                         | Clonar un repositorio desde la URL                                 |
| `git remote add origin <URL>`             | Asociar un repositorio local con un repositorio remoto             |
| `git push origin <branch>`                | Subir los cambios de una rama local al repositorio remoto          |
| `git pull origin <branch>`                | Descargar y fusionar los cambios del remoto a tu rama local        |
| `git push --set-upstream origin <branch>` | Subir una nueva rama que no existe en el repositorio remoto        |
| `git reset --hard HEAD`                   | Restaurar al último commit de tu rama actual                       |
| `git merge <feature-branch>`              | Fusionar una rama (ejemplo: `feature/update-project-settings`)     |
| `git pull origin develop`                 | Actualizar la rama actual con los cambios de 'develop'             |
| `git push origin develop`                 | Subir los cambios a la rama 'develop' en el repositorio remoto     |

---

## Additional Resources

- [Git Downloads](https://git-scm.com/downloads)
- [GitHub SSH Key Documentation](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
