# ag

> The Silver Searcher. Podobny do `ack`, ale ma być szybszy.
> Więcej informacji: <https://manned.org/ag>.

- Znajdź pliki zawierające "foo" i wypisz dopasowane linie:

`ag {{foo}}`

- Znajdź pliki zawierające "foo" w określonym katalogu:

`ag {{foo}} {{ścieżka/do/katalogu}}`

- Znajdź pliki zawierające "foo", ale wypisz tylko nazwy plików:

`ag -l {{foo}}`

- Znajdź pliki zawierające "FOO" bez rozróżniania wielkości liter i wypisz tylko dopasowanie, a nie całą linię:

`ag -i -o {{FOO}}`

- Znajdź "foo" w plikach o nazwie pasującej do "bar":

`ag {{foo}} -G {{bar}}`

- Znajdź pliki, których zawartość pasuje do wyrażenia regularnego:

`ag '{{^ba(r|z)$}}'`

- Znajdź pliki o nazwie pasującej do "foo":

`ag -g {{foo}}`
