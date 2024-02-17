# mad_libs_generator

Acest cod prelucrează un fișier text, înlocuind cuvintele marcate între "<" și ">" cu cuvinte furnizate de utilizator. Funcționalitățile sale:

Deschiderea fișierului: Se deschide fișierul "story.txt" în modul citire.

Citirea conținutului: Se citește conținutul fișierului într-o variabilă numită "story".

Inițializarea setului de cuvinte: Se inițializează un set gol pentru a stoca cuvintele care trebuie înlocuite.

Căutarea cuvintelor între paranteze unghiulare: Se parcurge fiecare caracter din conținutul fișierului.
--> Dacă se găsește un caracter "<", se marchează începutul unui cuvânt.
--> Dacă se găsește un caracter ">", iar un cuvânt a început anterior, se extrage cuvântul între parantezele unghiulare și se adaugă la setul de cuvinte.

Preluarea răspunsurilor de la utilizator: Se solicită utilizatorului să furnizeze un cuvânt pentru fiecare cuvânt găsit între parantezele 
unghiulare.
--> Răspunsurile utilizatorului sunt stocate într-un dicționar, asociind fiecare cuvânt din setul de cuvinte cu răspunsul corespunzător.

Înlocuirea cuvintelor în poveste: Se parcurge fiecare cuvânt din setul de cuvinte.
--> Se înlocuiește fiecare apariție a cuvântului din poveste cu răspunsul furnizat de utilizator.

Afișarea poveștii actualizate: Se afișează povestea actualizată, în care cuvintele marcate au fost înlocuite cu răspunsurile utilizatorului.
