# Comandos Básicos de Git

Git es una herramienta poderosa de control de versiones. Aquí te mostramos los comandos más indispensables para trabajar con Git de manera efectiva.

## 1. **Configuración Inicial**

Antes de comenzar a trabajar con Git, es necesario configurar tu información de usuario. Esto solo se hace una vez.

### Configurar Nombre de Usuario y Correo Electrónico
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu-email@example.com"


git config --list

git clone https://github.com/usuario/repositorio.git

git status

git add .

git commit -m "Mensaje descriptivo del cambio"

git checkout -- archivo.txt


