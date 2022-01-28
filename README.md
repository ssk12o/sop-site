Strona jest używa generatora Hugo w wersji 0.80 (niewykluczone, że inne wersje też działają, nie testowałem).

Żeby zbudować stronę do katalogu public/ wystarczy odpalić `hugo` bez argumentów. Z użyciem `hugo server` mozna uruchomić serwer dostarczający stronę.

`hugo deploy` na razie nie jest skonfigurowany. Docelowo pewnie będzie to jakiś rsync na serwer mini.

Do konwersji htmli wykopiowanych z drupala (kopiuję tylko ten fragment z pola edycji strony, a nie całość strony razem z dodatkami typu menu) na markdowna używam `pandoc -f html -t gfm --wrap=none`. W przypadku tutoriali do lab nie konwertowałem, bo trzeba było zrobić milion ręcznych poprawek -- to skomplikowany kod. Inne rzeczy (np. wykłady) przechodzą raczej gładko. Trzeba tylko zaktualizować linki i pokopiować zasoby typu pdf ze slajdami.
