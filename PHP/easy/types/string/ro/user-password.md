## Prelucrarea datelor introduse de utilizator

Presupunand ca urmatorul fragment de cod captureaza datele introduse de utilizator
in campul "password"

```php
<?php
  $password = "Mypassword321";
  // ... ?
```
Sa se scrie continuarea acestui cod in asa mod incat sa se dea o apreciere nivelului de securizare a parolei asa incat:
* Se va afisa "Your password is SECURE" in cazul in care:
  1. Parola are cel putin 8 simboluri si
  2. Parola contine cel putin o litera majuscula si
  3. Parola contine cel putin o litera mica si
  4. Parola contine cel putin o cifra
* Se va afisa "Your password is OK" in cazul cand:
  1. Parola are intre 5 si 8 caractere lungime sau
  2. Parola nu contine cel putin o litera majuscula sau
  3. parola nu contine nici o cifra
