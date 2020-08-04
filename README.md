# git-tutorial

## Konfiguracja danych użytkownika

````
git config --global user.name "Imię Nazwisko”
git config --global user.email moj@email.com      
````
weryfikacja: 
````
git config user.name  
git config user.email 
````

## Git przepływ pracy w trakcie nagrania:

````
touch README.md
git init
git status
git add README.md
git status
git add .
git commit -m "added readme"
git log
git checkout -b featur-section
git branch
git add .
git log
git checkout master
git merge feature-section
git branch -d feature-section
git branch
````

#### Sprawdzenie wersji
````
git version 
````

#### Inicjalizacja pustego repozytorium 
````
git init
````

#### Sprawdzenie stanu plików
````
git status
````

#### Dodanie pliku/zmian w pliku README.md
````
git add README.md
````
#### Dodanie plików/zmian w plikach w danym katalogu
````
git add .
````

#### Zapisanie zmian do repozytorium
````
git commit -m "added readme"
````

#### Wyświetleni commitów
````
git log
````

#### Utworzenie gałęzi feature-section i przełączenie
````
git checkout -b featur-section
````

#### Wyświetlenie gałęzi
````
git branch
````

#### Połączenie gałęzi feature-section z masterem
````
git merge feature-section
````

#### Usunięcie gałęzi feature-section
````
git branch -d feature-section
````
