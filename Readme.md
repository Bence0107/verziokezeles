# Verziókezelés git

- helyi repo létrehozása:
    > git init
- ellenőrzés: milyen fájlok változtak(az előző verzióhoz képest)
    > git status
- előkészítjük (stage=színpad) az új verziót, minden fájlt amiben történt módosulás:
    > git add .
- ellenőrzünk:
    > git status
- felhasználó név beállítása:
    > git config user.name ...
- emial cím beállítása:
    > git config user.email ...
- az új verzió megszületése:
    > git commit -m "first commit"

- távoli repo létrehozása(Github)
- a helyi repo és a Github repo összekapcsolása, úgy hogy PAT történjen a hitelesítés(token@):
    > git remote add origin https://token@github.com/...
- az első push:
    > git push -u origin master
- további push:
    > git push