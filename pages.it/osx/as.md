# as

> Assembler GNU portabile.
> Progettato principalmente per assemblare l'output di `gcc` ed utilizzarlo con `ld`.
> Maggiori informazioni: <https://keith.github.io/xcode-man-pages/as.1.html>.

- Assembla un file, scrivendo l'output su a.out:

`as {{percorso/del/file.s}}`

- Assembla l'output nel file dato:

`as {{percorso/del/file.s}} -o {{percorso/del/out.o}}`

- Genera l'output più velocemente saltando gli spazi e senza preprocessare i commenti. (Questo comando dovrebbe essere utilizzato solo con compilatori fidati):

`as -f {{percorso/del/file.s}}`

- Includi un percorso dato alla lista delle directory in cui cercare i file specificati nelle direttive `.include`:

`as -I {{percorso/della/directory}} {{percorso/del/file.s}}`
