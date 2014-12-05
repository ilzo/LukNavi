##Vaatimukset


**Funktionaaliset**
  * Järjestelmän voitava kirjautua Metropolian palvelimelle hakeakseen opiskelijatietoja
  * Järjestelmän on havainnollistettava käyttäjän sijainti rakennuksen sisällä huoneen/tilan tarkuudella
  * Järjestelmä laskee reitin käyttäjän nykyisestä sijainnista haluttuun luokkatilaan ja esittää reitin kartalla
  * Järjestelmä hakee lukujärjestykset ja vapaat tilat Metropolian valmiista järjestelmästä
  * Yhteydenpitoon palvelimen kanssa käytetään salattua yhteyttä 


  
**Ei-funktionaaliset**
  * Käytettävyys oltava helppoa: käyttäjätestejä&kyselyitä pitkin projektin etenemistä
  * Ulkonäkö laadukas: Käyttäjäkyselyissä myös ulkonäköön liittyviä kysymyksiä
  * Sovelluksesta aiheutuva dataliikenne ei saa kuormittaa Metropolian wlan-yhteyksiä liiaksi
    - stressitesti?
  * Mikäli näyttö on "suljettuna", dataa ei lähetetä turhaan taustalla vaan sijainti haetaan uudelleen näytön "lähtiessä käyntiin"
    * muutaman minuutin "varoaika" ehkä mahdollinen
