# Zadania z Programowania interfejsu użytkownika

Szablon repozytorium na zadania z kursu *Programowanie interfejsu użytkownika*
(HTML, CSS i JavaScript bez frameworków).

## Jak zacząć

1. Kliknij **Use this template → Create a new repository** i nazwij repozytorium `piu-labs`.
   (Na zajęciach repozytorium tworzy się automatycznie po zaakceptowaniu zadania –
   wtedy ten krok pomiń.)
2. Sklonuj swoje repozytorium na komputer i otwórz folder w VS Code.
3. Uruchom stronę przez rozszerzenie **Live Server** (`Go Live` na pasku statusu).

## Struktura

Każdy rozdział kursu ma własny folder:

```
piu-01/   Wprowadzenie                 (formularze)
piu-02/   Responsywność                (flexbox, grid, galeria)
piu-03/   Zmienne i animacje           (karta produktu)
piu-04/   JavaScript w przeglądarce    (kanban)
piu-05/   Moduły i stan                (kształty)
piu-06/   Asynchroniczność             (biblioteka Ajax)
piu-07/   Web Components               (komponenty, sklep)
```

W folderach są pliki startowe tam, gdzie przewiduje je treść zadania.
Strona `index.html` w katalogu głównym prowadzi do wszystkich rozdziałów.

## Commity

Commit zamykający zadanie nazwij tak, jak podaje strona zadań:
`piu-` + numer rozdziału + nazwa zadania, np.

```
piu-01 Formularze
piu-02 Grid
```

## Publikacja na GitHub Pages

1. Na stronie swojego repozytorium otwórz **Settings → Pages**.
2. W sekcji **Build and deployment**:
   - **Source:** `Deploy from a branch`,
   - **Branch:** `main`, folder **/ (root)**,
   - kliknij **Save**.
3. Po chwili strona będzie dostępna pod adresem
   `https://twoj-login.github.io/piu-labs/` (adres widać w **Settings → Pages**).

Projekt można też otworzyć lokalnie – przez Live Server albo bezpośrednio z pliku
`index.html` (moduły JavaScript wymagają jednak serwera, więc od rozdziału 05 – tylko
przez Live Server).
