# git add

> Aggiungi file nuovi o modificati all'area di stage.
> Maggiori informazioni: <https://git-scm.com/docs/git-add>.

- Aggiungi un file all'area di stage:

`git add {{percorso/del/file}}`

- Aggiungi tutti i file (tracciati e non tracciati):

`git add {{[-A|--all]}}`

- Aggiungi solo i file già tracciati:

`git add {{[-u|--update]}}`

- Aggiungi anche i file ignorati:

`git add {{[-f|--force]}}`

- Aggiungi parti di un file in modo interattivo:

`git add {{[-p|--patch]}} {{percorso/del/file}}`
