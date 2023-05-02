# Repository di test di compilazione di programma minimo per Pico SDK

Partendo dal repo pico-playground che contiene il programma sine_wave si prova a creare un progetto cmake che contenga solo questo senza tutti gli altri esempi.

E' più che altro un modo per vedere come impostare un file CMake minimale, anche se questo non è proprio l'esempio ottimale in quanto ha delle dipendenze a delle lib aggiuntive esterne dentro pico-extra

## Istruzioni per la compilazione

- clonare il repository da github
- `cd pico-minimal-test`
- `mkdir build`
- `cd build`
- `cmake ..`
- `make`

