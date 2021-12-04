# Echipe & parola
Echipa noastra: power rangers<br />
Echipa adversa: c0d3 8234k325<br />

**Parola adversari: zjxZjR3axM**

# Utilizare script-uri
**encrypt : python encrypt.py parola input.txt output<br />**
**decrypt : python decrypt.py parola output input_recuperat.txt<br />**
**getpass : python getpass.py input.txt output pass.txt**

# Problema 1
Este suficient sa rulam getpass.py cu argumentele cerute.<br />
Script-ul citeste 30 de caractere din input.txt si output si face xor litera cu litera.<br />
Pentru a afla parola, luam primele doua secvente alaturate de la inceput, de forma ***parola[0:x]*** si ***parola[x:2x]*** (x = range(10, 16))<br />
Daca sunt egale, am aflat parola de lungime x.
