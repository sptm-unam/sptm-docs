# GIT

Git es un sistema de control de versiones.

## Instalación

Link a Git
LInk a Visual Studio Code
Link a Git Lab

- Local repo
- Forks
- Clonar repositorio
- Agregar remotos
- Staging
- Commit
- Create Branches
- Change branches
- Push remote
- Merge
- Pull Requests
- Modificar un Pull Request
- Create Branch
- Cherry-Pick
- Stash
- Releases

## Cómo trabajar con un remoto 

- Encontrar el remoto que quieras colaborar 
![image](https://user-images.githubusercontent.com/9595617/218665331-d2cd177b-bc3a-4365-96e1-c0f8bb179c33.png)

- Crear un fork
![image](https://user-images.githubusercontent.com/9595617/218665425-30bc76d3-4337-4f1a-8b71-4a6431cb97e2.png)

- Clonar tu fork y navegar a la carpeta
![image](https://user-images.githubusercontent.com/9595617/218665605-4431dea7-ae38-4902-a000-264a56d84381.png)

```
git clone git@github.com:holomorfo/sptm-docs.git
cd sptm-docs
```


- Agregar el principal como remoto, llamarlo upstream o como quieran, en este caso es el original "sptm-unam/stpm-docs.git."
 ```
 git remote add upstream git@github.com:sptm-unam/sptm-docs.git
 ```
 En este caso estamos diciendo que vamos a agregar el repositorio `sptm-unam/sptm-docs.git` como remoto con el nombre `upstream`

- Haver un fetch de `upstram` para tener todas las ramas sincronizadas:
```
git fetch upstream
```

- Sincronizar con la rama main local y de Origin.
- Listo, mostrar cómo están colaborando

- Ahora hacer un PR
- Crear una rama con el nombre de los cambios que estamos haciendo desde una versión sincronizada de main.
- Hacer push ahí
- Crear un PR al archivo upstream
- Ya que lo acepten sincronizar nuestra rama Origin/main con origin/upstream.
- A mi me gusta que la rama main siempre sea un espejo de la de upstream.

Hay muchas otras formas de hacer esto, pero a mí me funciona esta manera.

## Referencias

- [Learn Git Branching](https://learngitbranching.js.org/): Aplicación web para aprender como funcionan las ramas en github.
- [Oh my git!](https://blinry.itch.io/oh-my-git): Juego descargable para aprender git desde cero.
- [Diagrama de flujo git por Nikki Siapno](https://twitter.com/NikkiSiapno/status/1593882400983072769?s=20&t=Q_Z1e7NYOrd8hzLS6WRlcQ)
![alt text](https://pbs.twimg.com/media/Fh6bl4DWIAAZxse?format=jpg&name=large)
- [GitHub Flow: Guía Básica](https://guides.github.com/introduction/flow/)
- [Usar Git para escritura](https://opensource.com/article/19/4/write-git)
- [Colaboración en equipo con Git](https://medium.com/anne-kerrs-blog/using-git-and-github-for-team-collaboration-e761e7c00281)
- [Cheatsheet de Markdown (para dar formato a archivos con extensión .md)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Manual "Pro Git"](https://git-scm.com/book/en/v2)
- [Borrar *branches* locales y remotos (limpieza)](https://railsware.com/blog/git-housekeeping-tutorial-clean-up-outdated-branches-in-local-and-remote-repositories/)

## Hacks

- [Remove All Commits – Clear Git History (Local & Remote)](https://www.shellhacks.com/git-remove-all-commits-clear-git-history-local-remote/)
- [Using Git to Manage System Configuration Files on Linux/MacOS](https://www.wangzerui.com/2017/03/06/using-git-to-manage-system-configuration-files/)
