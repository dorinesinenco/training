# Exercitii cu tipuri de date, valori si variabile

1. Exercitiu
### Fiind dat urmatorul fragment de cod
```php
<?php
  $version_old    = "1.0.0";
  $version_new    = "2.0.0";
  // ... ???
?>
```
Sa se scrie continuarea acestuia in asa mod in cat:
  * Sa se dea raspuns la intrebrea "care din versiuni este mai noua ?" (if/else)
  * Sa se indice daca diferenta dintre versiuni este una majora sau minora (o schimbare majora este atunci cand prima cifra difera, minora, cand se schimba doar cifra a doua)
---
acest exemplu presupune lucrul cu tipul de date "string"
pentru cei ce doresc sa afle mai multe despre ["versiunea semantica"](http://semver.org/)

2. Exercitiu
### Sa presupunem ca urmatoarele 3 variabile isi iau valorile din campurile unui formular de inregistrare

  ```php
  <?php
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
---

acest exemplu presupune lucrul cu tipul de date "string", structurile "if/else" si operatori de
comparare si logici
