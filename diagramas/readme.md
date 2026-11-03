# Diagrames de seqüència UML – Projecte BLOG Flask

En aquest apartat es descriuen els diferents diagrames de seqüència relacionats amb el procés d'inici de sessió de l'aplicació Flaskr.

## 1. Happy Path – Inici de sessió correcte

Mostra el funcionament normal de l'inici de sessió quan l'usuari introdueix correctament el seu nom d'usuari i la contrasenya.

## 2. Contrasenya incorrecta

Representa el cas en què l'usuari introdueix una contrasenya incorrecta i el sistema rebutja l'accés mostrant un missatge d'error.

## 3. Sistema no disponible

Mostra què passa quan el servidor no està disponible i l'usuari no pot accedir a l'aplicació.

## 4. Username incorrecte

Representa el cas en què l'usuari introdueix un nom d'usuari que no existeix i el sistema no permet iniciar la sessió.

## 5. Correu electrònic incorrecte

També s'ha elaborat aquest diagrama com a escenari alternatiu. Tot i això, no s'ha pogut provar a Flaskr perquè el formulari d'inici de sessió només demana el nom d'usuari (Username) i la contrasenya (Password), i no demana cap correu electrònic.
