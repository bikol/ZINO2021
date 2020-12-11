# Zadanie domowe Git - Instrukcja obsługi
Polega na grupowym opracowaniu krótkiego opisu kluczowych komend Gita.


Wymagania:
 * opracowanie ma mieć formę jednoplikowej strony HTML
 * wszystkie komendy z poniższej listy muszą zostać opisane (co robią i do czego mogą być przydatne + przykład użycia)
 * całość powinna być poprawna pod kątem językowym
 
Sposób pracy:
 * Każdy student tworzy własną kopię repozytorium (fork)
 * Dokonuje tam zmian (najlepiej w modelu branch per feature)
 * Następnie wysyła zgłoszenie Pull Request do oryginalnego repozytorium
 
Zadanie zaliczą te osoby, które łącznie:
 * dokonają istotnego wkładu merytorycznego w opracowanie (dodanie opisu komendy, modyfikacja istniejącego pisu, code review)
 * stworzą własne repozytorium (fork)
 * prześlą Pull Request do oryginalnego repozytorium
 
 
 Lista komend do opisania:
 
  * Wszystkie grupy
    * git config --global user.name ""
    * git reset HEAD
    * gitk -all
    * git branch --merged
    * git branch "branch" "commit hash"
    * git pull "remote" "branch"
    * git config --global user.email ""
    * git diff --staged
    * git checkout -b "branch"
    * git log --graph --all
    * git branch -d "branch"
    * git fetch "remote" "branch"
    * git config --global color.ui true
    * git commit "filename"
    * git branch -v
    * git push "remote" "branch"
    * git log "branch" --not "branch"
    * git bisect (start, bad, good, reset)
    * git commit -a -m ""
    * git add .
    * git checkout "branch"
    * git remote add "remote_name" "git url"
    * git blame -C "filename"
    * git branch "name"
