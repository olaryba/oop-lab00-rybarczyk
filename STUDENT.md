# Moje wykonanie Lab00

- Login GitHub / pseudonim: olaryba
- System i terminal (np. Windows + WSL Ubuntu): Windows 11 + PowerShell + MSYS2 UCRT64
- Edytor / IDE: Visual Studio Code
- Wersja Git: 2.56.0.windows.1
- Wersja kompilatora C++: g++.exe (Rev4, Built by MSYS2 project) 16.2.0
- Wersje java i javac: java 25.0.4.1, javac 25.0.4.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/olaryba/oop-lab00-rybarczyk/pull/1


## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! Author: olaryba
```
Wynik programu Java:
```text
Hello from Java! Author: olaryba
```

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: `cpp/main.cpp:5:59: error: expected ';' before 'return'`
- Przyczyna oraz sposób naprawy: Brakowało średnika `;` na końcu instrukcji `std::cout`. Naprawiłam błąd, dodając brakujący średnik.
- Commit z błędem (SHA lub link): 52e6184
- Czy Actions pokazały błąd, a po naprawie sukces? Tak. Actions pokazały błąd podczas kompilacji C++, a po dodaniu brakującego średnika kontrola zakończyła się sukcesem.


## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje zmiany w lokalnej historii Git. Push wysyła lokalne commity do zdalnego repozytorium na GitHubie.
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Po scaleniu PR zmiany są już na GitHubie, ale moja lokalna gałąź main może ich jeszcze nie mieć. Pull pobiera te zmiany ze zdalnego repozytorium i aktualizuje lokalny main.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Zielony wynik CI potwierdza, że kod przeszedł automatyczne zadania workflow, między innymi kompilację i uruchomienie programów C++ i Java. Nie potwierdza poprawności całego zadania, jakości kodu ani poprawnej konfiguracji mojego komputera.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: Brak
