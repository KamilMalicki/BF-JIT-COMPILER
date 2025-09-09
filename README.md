# Kompilator JIT dla Brainfuck

Prosty i szybki kompilator JIT (Just-In-Time) dla języka **Brainfuck**,
autorstwa Kamila Malickiego.

---

## Czym jest kompilator JIT?

Kompilator JIT dla Brainfuck to program, który bezpośrednio tłumaczy kod źródłowy na natywny kod maszynowy, a następnie natychmiast go wykonuje. Dzięki temu działanie jest znacznie szybsze niż w przypadku tradycyjnego interpretera, który przetwarza i uruchamia kod linijka po linijce.

---

## Główne cechy i zastosowania

To narzędzie zostało zaprojektowane z myślą o wydajności i łatwości użytkowania, co czyni je idealnym do:

- **Szybkiej egzekucji:** Uruchamiaj programy Brainfuck ze znacznym wzrostem wydajności.
- **Uproszczonego przepływu pracy:** Kompiluj i uruchamiaj kod bez tworzenia pośrednich plików czy wymagania ręcznej kompilacji.
- **Narzędzia edukacyjnego:** Proste narzędzie do eksperymentowania i nauki języka Brainfuck.

---

## Jak używać?

Aby rozpocząć, po prostu wykonaj te kroki na systemie Linux:

1.  **Pobierz plik wykonywalny:** Skopiuj plik wykonywalny `bf_jit-linux-{arch}` do swojego systemu. Pamiętaj, że ten kompilator jest przeznaczony specjalnie dla systemu Linux.
2.  **Przygotuj swój kod:** Utwórz plik zawierający kod Brainfuck, na przykład `program.bf`.
3.  **Uruchom z terminala:** Wykonaj kompilator, podając ścieżkę do swojego pliku jako argument w terminalu:

    ```bash
    ./bf_jit-linux-{arch} program.bf
    ```

Kompilator natychmiast przetłumaczy i uruchomi Twój program.
```eof
