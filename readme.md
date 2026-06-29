# Curso de Introducción a GIT AF 47082 – GR 99733

 Introducción a GIT AF 47082 – GR 99733
- Duración: 16 horas
- Modalidad: On-line
- Fechas: L 29/06/2026 - J 02/07/2026
- Horario: 9:30 - 13:30
Formador: Alejandro Cerezo
<alce65@hotmail.es>

## Contenidos

- Conceptos básicos
    - ¿Qué es y que no es GIT?
    - Cómo usar correctamente GIT
    - Configuración imprescindible 
- Fundamentos y arquitectura interna de GIT
    - Diferencias entre el working directory, el stage y el repositorio
    - Qué es exactamente un commit
    - Tipos de referencias (HEAD, ramas y tags) 
- Commits
    - Cómo preparar selectivamente un commit
    - Cuando hacer un commit
    - Cómo deshacer commits
    - Buenas prácticas 
- Como resolver los conflictos
    - Qué es un conflicto, cómo reducir su frecuencia y cómo resolverlos
- Branching
    - Qué es exactamente una rama en GIT
    - Cómo trabajar con ramas y diferentes maneras de fusionarlas
    - Modelos de branching
    - Git Flow 
- Trabajando con repositorios remotos
    - Cómo comunicar los repositorios locales con los remotos
    - Diferentes escenarios cuando trabajamos en equipo contra un repositorio remoto
    - Configuración básica 
- Pull Requests
    - Por qué usar PR
    - Cómo hacer correctamente una PR
    - Cómo configurar el repositorio remoto si usamos “PR”

Desarrollo del curso en la carpeta Oficial -> [repo](https://github.com/IconoTC/-Introducci-n-a-GIT-AF-47082-GR-99733)

## Desarrollo del curso

### Día 1 (Lunes 29 junio 2026)

- Presentación profesor / alumnos
- Introducción: Qué es un SCV y qué un SCV distribuido
- IDE / Editor de código: Visual Studio Code (VSC)
- Instalación de Git
- Terminales
  Configuración inicial
  - Nombre de usuario y correo electrónico
- Primeros pasos con Git

  - Primer repo (init), primer commit: .gitignore / readme.md
  - Anatomía de un repositorio git: working directory, staging area (index o cache) y repositorio (.git)
  - Estados de un archivo: untracked (U), tracked (modified (M), staged (A), committed) -->
  - add/commit/reset y status/log/show - GitGraph
  - Mensajes de commit

- [Descanso] 11:30 - 11:50

- Primeros pasos con Git (2)

- Anatomía de comandos típicos, referencias VS paths

  - HEAD, master, HEAD~1 y otras referencias útiles
  - Referencias por mensaje de commit (:/cadena)

- Integración con otras herramientas y entornos
  - Clientes gráficos
  - Entornos de desarrollo
  - Repositorios remotos: GitHub, GitLab, Bitbucket
    - remotes -> push / pull
    - Clonar un repositorio: clone
- Comprobar el repositorio.
  - git log
  - git show
  - git diff
- Aliases
  - Qué son
  - Cómo crearlos desde el CLI: `git config --global alias.ch checkout`
  - Crearlos editando el fichero de configuración: `git config --global -e` -->
- Ficheros Markdown
  - Qué son
  - Sintaxis básica
  - Vista previa en VSC / GitHub / GitLab 



<!-- (No incluido en el curso actual)

- Git internals (1/2 día)

  - Estructura de un repositorio git: .git
  - Objetos git: blobs, trees, commits (y tags)
    - Creación y lectura de objetos
    - Creación del árbol de objetos en un primer commit
    - Modificación del árbol de objetos en commits sucesivos
  - Referencias: HEAD, ramas (tags y remotes)
  - Taller: creación de un repositorio git "a mano" 
-->

### Día 2 (Martes 30 junio 2026)

<!-- - Herramientas para preparar un buen commit en cualquier situación

  - Operaciones en la Staging Area (Index)
    - Añadir ficheros
    - Eliminar de la Staging Area (Index)
    - Preparar un commit parcial: git add -p
  - Eliminar ficheros: git rm
  - Cambiar nombre de ficheros: git mv
  - git blame
  - Recapitulando: Git básico

  - Reescribiendo la historia
    - Advertencia
    - git command --amend
      - Ref logs
    - git checkout y git reset (introducción)
-->

- [Descanso]

<!--

- Reescribiendo la historia (2)
  - git checkout
  - git reset
  - Evolución de git checkout: Nuevos comandos git switch y git restore
    - git checkout a nivel de archivo (restore)
    - git reset a nivel de archivo
  - rebase interactivo
    - edit: modificando un commit
    - squash y fixup: fusionando commits
    - drop: eliminando un commit
- Otros comandos
  - git clean
  - git revert 
-->

### Día 3 (Miércoles 1 julio 2026)

<!-- - Trabajando en paralelo

  - Ramas
    - Crear y seleccionar
      - Crear desde referencia
    - Ver ramas
    - Borrar ramas
    - Mover y renombrar ramas
  - git stash

  - Combinación de ramas: Merge y Rebase
    - git merge
      - fast-forward
      - three-way (ort) merge
    - git rebase -->

- [Descanso]

<!-- 
  - Combinación de ramas (continuación)

    - Resolución de conflictos

  - git cherry-pick

  - Preguntas: cherry-pick v. merge y modelos de branching

- Etiquetas (tags)

  - Tags anotadas y tags ligeros
  - Crear, listar, eliminar -->

### Día 4 (Jueves 2 julio 2026)

<!-- - Repositorios remotos

  - Repositorios "bare"
  - Clonar repositorios: git clone
  - git remote
  - git push
    - push tags
  - git pull

    - git fetch
    - git merge / git rebase
    - Conflictos

  - Ramas remotas
    - Seguimiento de ramas remotas (tracking branches)
    - Crear ramas locales a partir de ramas remotas: fetch + checkout / switch -c
    - Subir ramas locales a ramas remotas: -u
    - Eliminar ramas remotas
  - Pull requests (GitHub) / Merge requests (GitLab)
    - Flujo de trabajo típico
    - Revisión de código -->

- [Descanso]

<!-- - Pull requests (GitHub) / Merge requests (GitLab)
    - Resolución de conflictos en remoto
    - Buenas prácticas:
      - Actualizar la rama con la rama main antes de hacer el merge
      - Resolución de conflictos en local
      - Eliminar la rama una vez hecho el merge
  

- Flujos de trabajo (workflows)

  - Git Flow
  - GitLab Flow
  - GitHub Flow
    - Ship-Show-Ask

- Buenas prácticas

- Configuración avanzada de git
  - Hooks
  - Husky (Hooks en JS) 

--->

<!--
(No incluido en el curso actual, pero puede ser interesante para el alumno)

- Sub-proyectos (submodules)

- GitHub (comentario general)
  - Hosting de Repositorios
    - repositorios públicos y privados; ramas y remotos: push y pull (v.s.)
    - forks
  - Colaboración
    - pull requests: revisión de código y comentarios (v.s.)
    - PR desde ramas y forks
    - Proyectos
      - Tableros (Boards)
      - issues y proyectos; milestones
    - Wikis
    - Gists
  - GitHub CLI
  - GitHub Pages
-->
