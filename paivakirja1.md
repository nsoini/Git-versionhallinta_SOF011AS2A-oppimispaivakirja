# Oppimispäiväkirja: Paikallinen git

__Mitä uutta opin osiossa? Miten voisin hyödyntää oppimaani käytännössä?__

Opin paljon muutosten ja tallennuksien peruuttamisesta ja ymmärsin että committeja kannattaa tehdä usein sillä mikään (tai melkien mikään) ei ole peruutettavissa. 

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Osiossa oli paljon entuudestaan tuttuja komentoja ja mikää harjoitus ei tuntunut erityisen vaikealta. Päivä kirjan täyttöä varten piti tosin palata taaksepäin tarkistamaann mitä kaikkia komentoja tulikaan käytettyä. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | luo tyhjän repositorion |
| git clone | kopioi olemassa olevan repositorion |
| git status  | tarkista työhakemiston git-tilan |
| git add	test.txt | lisää tiedoston seuraavaan tallennukseen |
| git commit -m "first commit" | tallentaa ja kirjaa "" sisällä olevan kommentin |
| git log | commit historia |
| git log --stat | commit historia käänteisessä järjestyksessä lisätiedoilla |
| git rm test.txt | poistaa tiedoston työhakmistosta ja versionhallinnasta |
| git mv hello.html index.html | nimieää tiedoston uudestaan |
| git mv index.html hello | siirtää tiesdoston hakistoon |
| git reset h3.txt | peruttaa tietyn tiedoston add komennon |
| git reset | peruttaa add komennon |
| git restore test2.txt | peruutta talletamattomat muutokset tiedostista |
| git revert 1517f30 | peruuttaa kokonaisen commitin |
| git branch tyylit | commit historia |
| git branch | näyttää missä haarassa olet tällä hetkellä |
| git switch tyylit | cvaihtaa nimettyyn haaraan |
| git merge tyylit | yhdistää haaran main haaraan |