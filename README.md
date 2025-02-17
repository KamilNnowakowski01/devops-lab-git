﻿#Podstawowe komendy Git i GitHub:

git config --global user.name "Your Name"
Ustawia nazwę użytkownika dla wszystkich repozytoriów na danym komputerze.

git config --global user.email "your_email@example.com"
Ustawia email użytkownika, który będzie przypisany do commitów.

git init
Inicjalizuje nowe lokalne repozytorium Git w bieżącym katalogu.

git clone <url>
Klonuje zdalne repozytorium na lokalny komputer.

git status
Wyświetla status repozytorium: zmodyfikowane, nowe, usunięte pliki itp.

git add <file>
Dodaje konkretny plik do staging area.

git add .
Dodaje wszystkie zmodyfikowane i nowe pliki do staging area.

git commit -m "Commit message"
Zatwierdza zmiany z opisem (wiadomością) commita.

git log
Wyświetla historię commitów w repozytorium.

git branch <branch_name>
Tworzy nowy branch (gałąź).

git checkout <branch_name>
Przełącza się na istniejący branch.

git checkout -b <branch_name>
Tworzy nowy branch i od razu na niego przełącza.

git merge <branch_name>
Scala wybrany branch z bieżącym branchem.

git branch -d <branch_name>
Usuwa lokalny branch.

git push origin <branch_name>
Wypycha zmiany z lokalnego brancha na zdalne repozytorium.

git pull
Pobiera i scala zmiany z zdalnego repozytorium do lokalnego.

git fetch
Pobiera zmiany z zdalnego repozytorium, ale ich nie scala.

git diff
Wyświetla różnice między plikami w staging area a ostatnim commitem.

git checkout -- <file>
Przywraca ostatnią zapisaną wersję pliku.

git rm <file>
Usuwa plik z repozytorium i systemu plików.

git mv <old_name> <new_name>
Zmienia nazwę pliku w repozytorium.

git tag <tag_name>
Tworzy tag (np. do oznaczenia wersji oprogramowania).

git push origin <tag_name>
Wypycha tag na zdalne repozytorium.

git tag -d <tag_name>
Usuwa tag lokalnie.

git reset --hard
Resetuje wszystkie zmiany w lokalnym repozytorium do ostatniego commita.

git stash
Tymczasowo zapisuje zmiany bez commitowania.

git stash apply
Przywraca zmiany zapisane w stash.

git stash list
Wyświetla listę wszystkich zapisanych stash.

git commit --amend
Modyfikuje ostatni commit (np. poprawia wiadomość).

git remote -v
Wyświetla informacje o zdalnych repozytoriach.
