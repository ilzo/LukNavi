Vaatimukset:
* Funktionaaliset vaatimukset
  * Tarkentavat käyttötapauksia
* Ei-funktionaaliset vaatimukset
  * Esim käytettävyyteen, tietoturvaan, tehokkuuteen, skaalautuvuuteen, hintaan ja prosessimalliin liittyvät vaatimukset

  
  * **Muista esittää vaatimukset jäljitettävässä muodossa, yksiselitteisesti**
* Keskeinen tapa (erityisesti ei-funktionaalisiin vaatimuksiin) yksiselitteisille kuvauksille on vaatimusten **mitattavuus** (software metrics)


pohdittavaa
* kuinka taata järjestelmän helppokäyttöisyys?
* kuinka taata järjestelmän luotettavuus? Listaa mahdolliset 
järjestelmävirheet ja kuinka niistä toivutaan
* järjestelmälläsi on paljon käyttäjiä, kuinka taata että 
järjestelmässä on riittävästi tehoja? Millaisia metriikkoja 
käyttäisit?

Mitä muita ei-funktionaalisia vaatimuksia olisi syytä kuvata?
Millaisia metriikkoja käyttäisit, jotta vaatimukset ovat riittävän yksiselitteisiä?
--------------
Osalle tarttis tehä jotain, osa on liian epätarkkaa ja osa ei varmaa edes kuulu vaatimuksiin T:hans


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
