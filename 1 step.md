# Zadanie nr. 2 - [AWS](https://aws.amazon.com/) - Github - CLI
## Realizacja zadania nr. 2 w ramach laboratorium Programowanie full-stack w chmurze obliczeniowej.
 
### Operacje na repozytorium - Github - Lokalne repozytrium

> Komendy realizowane za pomocą narzędzia Git bash - z przedrostkiem WINPTY - zezwalającym na interakcję, pomiędzy użytkownikiem a kreatorem w systemie Windows

```
    $ winpty gh auth login
    $ git init
    $ winpty gh repo create
```
> Prezentacja interakcji z konsolą - repozytrium - Github 
```
    ? What would you like to do? Push an existing local repository to GitHub
    ? Path to local repository (.)

    ? Path to local repository .
    ? Repository name (Zadanie 2 - AWS)

    ? Repository name Zadanie 2 - AWS
    ? Description (Zadanie 2 - AWS)

    ? Description Zadanie 2 - AWS
    ? Visibility Public
    ✓ Created repository KacperKi/Zadanie-2---AWS on GitHub
    ? Add a remote? Yes
    ? What should the new remote be called? (origin)

    ? What should the new remote be called? origin
    ✓ Added remote git@github.com:KacperKi/Zadanie-2---AWS.git
```

> Lokalne repozytorium - przesłanie na Github - pierwsze commit
```
    git branch -M main
    git add .
    git commit -m "Pierwszy komit"
    git push --set-upstream origin main
```

> Narzędzie dostępne pod - [Git bash](https://gitforwindows.org/)</br>

> Repozytoria autora - GitHub.com - [KacperKi](https://github.com/KacperKi)

## Weryfikacja utworzonego repozytorium na liście repozytrium 
> ℹ️  W celu filtracji wyników - użyj polecenia `grep 'param'` - wyszkując w ten sposób określone repozytroium.
```
gh repo list
```