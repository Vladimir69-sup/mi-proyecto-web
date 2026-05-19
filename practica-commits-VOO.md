# Práctica de commits — Git · ENP6 UNAM

Cada nivel te pide un cambio concreto en este archivo.  
Edita → `git add practica-commits.md` → `git commit -m "..."`

---

## Nivel 1 · Preséntate

**Qué hacer:** Llena los campos con tus datos.  
**Commit:** `feat(perfil): agrega presentación de [tu nombre]`

```
Nombre     : Vladimir Ortiz Ochoa
GitHub     : https://github.com/Vladimir69-sup/mi-proyecto-web.git
Algo sobre mí : Me encantan las películas y el jazz, es por ello que La La Land siempre será un ícono para mi.
```

---

## Nivel 2 · Lo que ya sabes hacer

**Qué hacer:** Agrega al menos tres cosas que sabes hacer (no tienen que ser de programación).  
**Commit:** `feat(habilidades): agrega lista de habilidades`

- Soy bueno al momento de organizar un equipo
- Me gusta y soy bueno al momento de expresarme en público
- Tengo nociones artisticas, me gusta el diseño 3D y la música

---

## Nivel 3 · Corrige los errores

**Qué hacer:** El párrafo de abajo tiene **cuatro errores**. Corrígelos todos en un solo commit.  
**Commit:** `fix(convenciones): corrige errores en descripción de Git`

> Git es un sistema de control de versiones creado en 2005 por Linus Torvalds
> para reemplazar a BitKeeper, que era de licencia y dejó de darse gratis al proyecto Linux.
> Cada commit guarda una fotografía de todos los archivos del repositorio en ese momento,
> identificada con un hash SHA-1 único. Para subir cambios al servidor usamos `git push`.

---

## Nivel 4 · Qué aprendí hoy

**Qué hacer:** Escribe tres cosas concretas que aprendiste en esta sesión.  
**Commit:** `docs(aprendizaje): agrega notas de la sesión`

1. Aprendí la historia detrás de la creación de Git por parte de Linus Torvalds
2. Apredí las diferencias, funcionamientos y diferencias de Git, GitHub y GitLab
3. Aprendí como crear un repositorio y como subir un archivo a tal repositorio.

---

## Nivel 5 · Tabla de comandos

**Qué hacer:** Completa las celdas vacías de la tabla.  
**Commit:** `docs(comandos): completa tabla de referencia`

| Comando | ¿Qué hace? |
|---------|------------|
| `git init` |Inicializa el repositorio|
| `git status` |Otorga la información respectiva al estado de los archivos localizados en el repositorio. Principalmente nos indican los archivos que han sufrido modificaciones y que aún no han sido registrados|
| `git add .` |Rastrea de manera específica un archivo, hace pasar de working phase a staging phase|
| `git commit -m "..."` |Guarda todos los cambios realizados en el archivo. Se ocupa siguiendo una regla concreta que permita distinguir de manera eficaz el tipo de cambio que haya sido realizado|
| `git log --oneline` |Nos da el historial de commits utilizando una sola linea para cada uno de ellos|
| `git push` |Manda los archivos y sus commit de nuestro repositorio remoto al localizado en la nube en GitHub|

---

## Nivel 6 · Marca tu avance

**Qué hacer:** Cambia `[ ]` por `[x]` en cada punto que ya dominas.  
**Commit:** `chore(practica): actualiza checklist de avance`

- [x] Hice `git init` sin ayuda
- [x] Entiendo para qué sirve el Staging Area
- [x] Escribí un mensaje de commit con formato Conventional Commits
- [x] Puedo ver el historial con `git log`
- [x] Completé todos los niveles de esta práctica

---

## Referencia rápida

| Tipo | Cuándo |
|------|--------|
| `feat` | Agrego algo nuevo |
| `fix` | Corrijo un error |
| `docs` | Solo toco documentación o notas |
| `style` | Formato, sin cambiar contenido |
| `refactor` | Reorganizo sin cambiar el resultado |
| `chore` | Tareas de mantenimiento |
