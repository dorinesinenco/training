## Prelucrarea textelor formatate
Fiind dat urmatorul fragment de cod
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
