# SOI

### Repo do przetrzymywania kodów z systemów operacyjnych, bo zaczęły mi się już mieszać wersje

 Zad1 - implementacja algorytmu szeregowania procesów Round Robin (algorytm karuzelowy) dla procesów użytkownika 
w systemie minix (UNIX)   
Symulowane są 3 kolejki o różnych priorytetach, każdy proces dostaje standardowy kwant czasu 100ms, po czym jest wywłasczany  
Przykład: kolejka 0 ma procesy: A, B, C, kolejka 1: D, E, kolejka 2: F  
Procesy będą uruchamiane w kolejności: A B C D A B C E F A B C D A ....  
