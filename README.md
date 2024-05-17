# Git-oppimispaivakirja

Tämä on Haaga-Helian kurssin Git-versionhallinta - SOF011AS2A-3001 oppimispäiväkirja. Kurssin laajuus on 1 op.

Oppimispäiväkirja koostuu kolmesta eri osasta:
1. Paikallinen git [Päiväkirja 1](../blob/main/paivakirja1)
2. Hajautettu git [Päiväkirja 2](../blob/main/paivakirja2)
3. Git projektissa [Päiväkirja 3](../blob/main/paivakirja3)

*Opiskelija: Linnea Soini*

## Osa 1: Paikallinen git

__Mitä uutta opin osiossa? Miten voisin hyödyntää oppimaani käytännössä?__

Opin paljon muutosten ja tallennuksien peruuttamisesta ja ymmärsin että committeja kannattaa tehdä usein sillä mikään (tai melkein mikään) ei ole peruutettavissa. 

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Osiossa oli paljon entuudestaan tuttuja komentoja ja mikään harjoitus ei tuntunut erityisen vaikealta. Päivä kirjan täyttöä varten piti tosin palata taaksepäin tarkistamaan mitä kaikkia komentoja tulikaan käytettyä. 

### Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | luo tyhjän repositorion |
| git clone | kopioi olemassa olevan repositorion |
| git status  | tarkista työhakemiston git-tilan |
| git add	test.txt | lisää tiedoston seuraavaan tallennukseen |
| git commit -m "first commit" | tallentaa ja kirjaa "" sisällä olevan kommentin |
| git log | commit historia |
| git log --stat | commit historia käänteisessä järjestyksessä lisätiedoilla |
| git rm test.txt | poistaa tiedoston työhakemistosta ja versionhallinnasta |
| git mv hello.html index.html | nimeää tiedoston uudestaan |
| git mv index.html hello | siirtää tiedoston hakemistoon |
| git reset h3.txt | peruttaa tietyn tiedoston add komennon |
| git reset | peruttaa add komennon |
| git restore test2.txt | peruuttaa tallentamattomat muutokset tiedostoista |
| git revert 1517f30 | peruuttaa kokonaisen commitin |
| git branch tyylit | commit historia |
| git branch | näyttää missä haarassa olet tällä hetkellä |
| git switch tyylit | vaihtaa nimettyyn haaraan |
| git merge tyylit | yhdistää haaran main haaraan |


## Osa 2: Hajautettu git

__Mitä uutta opin osiossa? Miten voisin hyödyntää oppimaani käytännössä?__

Opin etärepositoriosta ja eri haarojen käytöstä. Opin myös uusia komentoja.

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Materiaalit ja omat muistiinpanot auttoivat oppimaan.

### Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote -v | näyttää git remote tiedot lisätiedoilla |
| git remote add origin https-osoite | asettaa ja nimeää etärepositorion |
| git push origin main | vie paikallisrepositorion tiedot etärepositorioon |
| git branch -r | listaa etärepositorion haarat |
| git fetch | lataa etärepositorion tiedot paikalliseen repositorioon |
| git checkout origin/main | vaihtaa haaraa |


## Osa 3: Git projektissa

__Mitä uutta opin osiossa? Miten voisin hyödyntää oppimaani käytännössä?__

Viimeisessä osiossa sain harjoitella aikaisemmin opittuja taitoja. Opin että tallennuskommenttiin voi lisätä lisätietoja.

__Millaiset talletuskommentit ovat mielestäsi hyödyllisiä muille projektin jäsenille? Tarkastele kurssilla laatimiasi talletuskommentteja ja arvioi niitä.__

Selkeitä, informatiivisia mutta silti lyhyitä.

__Osallistut 3-4 hengen ohjelmistoprojektikurssille, ja olet saanut tehtäväksesi järjestää projektitiimin versionhallinnan. Kerro, miten tekisit sen. Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Uudet toiminnallisuudet tehdään omiin feature haaroihin. Valmiit toiminnollisuudet katselmoidaan ja hyväksytään yhdessä.
Päähaaraan yhdistetään vain toimivia, testattuja ja hyväksyttyjä feature-haaroja. Feature haara poistetaan kun se on yhdistetty päähaaraan.
Tallennuskommenttien kieli on englanti.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli sisällöltään ja materiaaliltaan todella informatiivinen. Olisin kaivannut juuri tällaista toteutusta opintojen alkuvaiheessa, toisella tai viimeistään kolmannella lukukaudella. En täysin ymmärtänyt loppupalautuksen tehtävänantoa. 
