# Diagrames de seqüència UML – Projecte BLOG Flask

En aquest apartat es mostren els diagrames de seqüència del procés d'autenticació de l'aplicació Flaskr.

## 1. Happy Path – Inici de sessió correcte

Aquest diagrama mostra el procés d'inici de sessió quan l'usuari introdueix correctament el seu nom d'usuari i la seva contrasenya. El sistema valida les credencials i permet accedir a la pàgina principal.

![Happy Path](diagrams/happy-path.png)

[Veure diagrama Happy Path](diagrams/happy-path.png)

## 2. Contrasenya incorrecta

Aquest diagrama representa el cas en què l'usuari introdueix una contrasenya incorrecta. El sistema rebutja les credencials i mostra el missatge d'error «Incorrect password».

![Contrasenya incorrecta](diagrams/password-incorrecta.png)

[Veure diagrama de contrasenya incorrecta](diagrams/password-incorrecta.png)

## 3. Sistema no disponible

Aquest diagrama mostra què passa quan el servidor Flaskr està aturat i l'usuari intenta accedir a l'aplicació. El navegador no pot establir la connexió i mostra l'error `ERR_CONNECTION_REFUSED`.

![Sistema no disponible](diagrams/sistema-no-disponible.png)

[Veure diagrama de sistema no disponible](diagrams/sistema-no-disponible.png)

## 4. Username incorrecte

Aquest diagrama representa el cas en què l'usuari introdueix un nom d'usuari que no existeix. El sistema no troba l'usuari a la base de dades i rebutja l'inici de sessió.

![Username incorrecte](diagrams/username-incorrecto.png)

[Veure diagrama de username incorrecte](diagrams/username-incorrecto.png)
