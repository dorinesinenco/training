## Prelucrarea datelor introduse de utilizator
Sa presupunem ca urmatoarele 3 variabile isi iau valorile din campurile unui formular de inregistrare

  ```php
  <?phpsha
    $username_input = "user@mymail.local";
    $password_input = "myp@ss123";
    $confirm__input = "myp@ss123";
    // ... ???
  ?>
  ```

Sa se scrie continuarea acestui fragment de cod in asa mod incat:
  * Sa se afiseze "registration complete" doar in cazurile in care:
    1. Toate trei campurile au fost completate (au cel putin 3 simboluri fiecare)
    2. Parola este egala cu parola confirmata
    3. Numele de utilizator este o adresa de email (exista simbolul "@" si "." anume in ordinea indicata)
  * In toate celelalte cazuri, sa se afiseaza mesajul "registration failed"
  * BONUS: In toate celelalte cazuri, sa se specifice printr-un mesaj ce anume s-a incalcat
  * BONUS: Exista sansa ca un utilizator ne-experimentat sa introduca spatii din neatentie la inceputul sau sfarsitul valorii in camp
    spre ex. " myp@ss123   ", cum veti proceda in asa caz pentru a citi valoarea corecta?
---

acest exemplu presupune lucrul cu tipul de date "string", structurile "if/else" si operatori de
comparare si logici
