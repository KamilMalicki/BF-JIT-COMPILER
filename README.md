# Brainfuck JIT Compiler

Prosty i szybki kompilator JIT dla języka **Brainfuck**.

---

## Co to jest?

Program, który zamienia kod Brainfuck bezpośrednio na natywny kod maszynowy i od razu go wykonuje.  
Dzięki temu działanie jest dużo szybsze niż w klasycznych interpreterach.

---

## Do czego to służy?

- Uruchamianie programów Brainfuck szybko i efektywnie.
- Bez zapisywania pośrednich plików czy ręcznej kompilacji.
- Proste narzędzie do eksperymentów i nauki Brainfucka.

---

## Jak korzystać?

1. Skopiuj plik `bf_jit` do swojego systemu (ważne aby to był linux!!!).  
2. Przygotuj plik z kodem Brainfuck, np. `program.bf`.  
3. W terminalu uruchom:  

```bash
./bf_jit program.bf
