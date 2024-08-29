# GitHubBasic

# Introducción a Git

Este repositorio cubre los conceptos básicos de Git, desde la configuración inicial hasta las operaciones esenciales. Aquí aprenderás cómo comenzar a trabajar con Git en tus proyectos.

## 1. Configuración inicial

Antes de comenzar a usar Git, es importante configurarlo correctamente.

### Configurar tu identidad

Esto es necesario para que tus commits estén correctamente asociados con tu nombre y correo electrónico.
#### Name
```bash
git config --global user.name "Tu Nombre"
```
#### Email
```bash
git config --global user.email "tuemail@example.com"
```

## 2. Comandos basicos

Comandos comunes 

### Init
```bash
git init
```

### Status
```bash
git status
```

### Add
```bash
git add .
```

### Commit
```bash
git commit -m "nombre_del_commit"
```

### Log
```bash
git log
```

### Alias
```bash
git config --global alias.st "status -s -b"
git config --global alias.als "config --global -e"
git config --global alias.cm "commit -m"
git config --global alias.lg "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ar)%C(reset)%C(white)%s%C(reset)%C(dim white)- %an%C(reset)%C(bold yellow)%d%C(reset)' --all"
``


