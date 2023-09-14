## Practica 2 Diego Lecanda

**¿Cómo se inicializa un repositorio en Git?**

Para abrir un repositorio de manera local empezamos con git init

```
git init 
```
Si es tu primera vez configurando Git se utilizan estos comandos

```
git config --global user.name "Nombre de Usuario"
git config --global user.email tuemail
git config --global user.ui true
git config --global init.defaultBranch main
```
Es importante recalcar que si estas en un equipo donde es usado por mas gente es necesario poner **local en vez de global.**

Para guardar los cambios en tu proyecto.
```
git add .
git commit -m "mensaje descriptivo del cambio"
```
---

**¿Cómo creas un repositorio en GitHub?**

Entras al link de https://github.com/

Si no tienes un cuenta la creas y te dirige a crear nuevo repositorio. Ahi eliges la configuracion que mas desees. 

**¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?**

```
git remote add origin https://github.com/usuario/repositorio.git
```
Una vez vinculado necesitamos subir nuestros cambios con este comandos 
```
git push -u origin master
```

---
**¿Cuál es el flujo básico de trabajo en Git y GitHub?**

- Working Directory: la carpeta local de tu computadora.

- Staging Area: git agrega los cambios realizados.

- Local repository: aqui se registran los cambios en el repositorio. 

- Remote repository: El repositorio remoto donde almacenamos nuestro proyecto. 



