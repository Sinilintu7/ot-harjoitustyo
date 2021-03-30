# Vaatimusmäärittely

## Sovelluksen tarkoitus

Sovelluksessa käyttäjän on mahdollista pelata blackjack-korttipeliä kuvitteellisilla panoksilla.

## Perusversion toiminnallisuus

### Alkuvalikossa

- Käyttäjä voi aloittaa uuden pelin.
- Käyttäjä voi avata tuloslistan, jossa näkyvät aiempien pelien tulokset paremmuusjärjestyksessä.
- Käyttäjä voi sulkea sovelluksen.

### Pelin aikana

- Pelin alussa käyttäjälle annetaan ennalta määritetty määrä pelimerkkejä.
- Jokaisen käden alussa käyttäjä voi joko asettaa haluamansa kokoisen panoksen tai lopettaa pelin.
- Panoksen asettamisen jälkeen käsi etenee blackjackin sääntöjen mukaisesti.
  - Sovelluksen perusversiossa käyttäjä voi ainoastaan pyytää uuden kortin (hit) tai lopettaa korttien nostamisen (stay).
- Pelin aikana kortit nostetaan simuloidusta korttipakasta, joka sekoitetaan pelin alussa, sekä tietyin väliajoin pelin aikana.
- Peli loppuu, jos käyttäjä päättää lopettaa pelin, tai jos käyttäjällä ei ole enää yhtäkään pelimerkkiä.
- Kun peli loppuu, käyttäjälle näytetään, kuinka paljon hänellä oli pelimerkkejä pelin lopussa, minkä jälkeen käyttäjä palautetaan alkuvalikkoon. 
  - Tämä tulos tallennetaan myös tuloslistalle.

## Jatkokehitysideoita

Perusversion jälkeen sovellusta voidaan laajentaa esim. seuraavilla ominaisuuksilla:

- Erityistoiminnot käden aikana (double down, split, surrender).
- Näkymä, jossa käyttäjä näkee tilastoja kaikista aiemmin pelaamistaan peleistä (voitot/tappiot, suurin voitto/tappio yhdessä kädessä, yms.).
- Pelissä käytettävien korttipakkojen määrän muuttaminen.
- Moninpeli (samalla laitteella).
