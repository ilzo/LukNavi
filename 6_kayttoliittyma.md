## Käyttöliittymä

###Järjestelmän käyttöliittymän olennaisimmat näkymät
- Kirjautumissivu
- Päävalikko/Hakusivu
- Karttanäkymä
- Lukujärjestys
- Ryhmienhallintasivu (onko ryhmächat-ikkuna samalla sivulla vai omalla?)

###Näkymien väliset siirtymät korkealla tasolla
- Päävalikosta löytyy painike "Lukujärjestys", jota painamalla siirrytään Lukujärjestys -näkymään. 
	  Päävalikosta löytyy painike "Vapaat työtilat", joka avaa erillisen ikkunan, jossa varaamattomat työtilat lueteltuina.
	  Työtilaikkunoiden kohdalla on Navigointi/Nuoli -painike, jota painamalla siirrytään karttanäkymään.
	  Päävalikossa on painike "Omat työryhmät", jota painamalla siirrytään ryhmienhallintasivulle.

	  
###Näkymien tapahtumat ja toiminnot

- Kirjautumissivu: Käyttäjä kirjautuu tässä ikkunassa sovellukseen omilla tuubi-käyttäjänimellään 
	ja salasanallaan, ja painamalla "Kirjaudu" -painiketta. !(Login-kuva](https://raw.githubusercontent.com/ilzo/LukNavi/master/kuvat/Kirjautuminen_v2.png)
	
- Päävalikko/Hakusivu: Tälle näkymälle sijoittuu tiedot oppilaan seuraavaksi alkavasta oppitunnista omaan tietoikkunaan
	  sivun ylälaitaan. Tietoikkunan oikeassa alakulmassa on Navigointi/Nuoli-painike, josta siirrytään karttanäkymään. Tietoikkunan
	  alapuolella on painikkeet "Lukujärjestys", "Vapaat työtilat" ja "Työryhmät". 
	
- Karttanäkymä: Kaksiulotteinen pohjakartta koulun sisätiloista, jossa käyttäjää edustaa punainen nuoli.
	Riippuen mitä oppituntia tai työtilaa haetaan, käyttäjä ohjataan määränpäähän reittiviivalla. Oman ryhmän jäseniä paikannettaessa, käyttäjää ohjataan
    henkilön luokse reittiviivalla, ja paikannettavaa henkilöä edustaa kartalla vihreä piste/pallo.	Reittiviiva 
	ja karttanäkymä päivittyvät ruudulla sitä mukaan kun käyttäjä liikkuu.
	
- Työryhmät: Tällä sivulla opiskelija voi perustaa oman työryhmän, hakea muita käyttäjiä nimellä, hakea olemassaolevia ryhmiä ja lähettää 
  pikaviestejä omien työryhmien jäsenille. Ryhmiä haetaan valitsemalla Hakukentän vieressä oleva Ryhmähakupainike aktiiviseksi ja kirjoittamalla ryhmän nimi 
  Hakukenttään. Vastaavasti yksittäisiä henkilöitä haetaan valitsemalla Henkilöhakupainike aktiiviseksi ja kirjoittamalla henkilön nimi Hakukenttään. Sivun 
  keskiosassa näytetään oletuksena omat työryhmät, ja ryhmiä haettaessa hakutulokset. Ryhmiin liitytään lähettämällä ryhmän perustajalle pyyntö. 
  Vastaavasti perustaja voi liittää työryhmäänsä uusia jäseniä hakemalla käyttäjiä ja lähettämällä heille kutsun ryhmään. 
  Hakukentän vieressä sijaitsevalla "+"-painikkeella käyttäjä siirtyy perustamaan uuden ryhmän. Tällöin näkymään avautuu ikkuna, jossa käyttäjää pyydetään 
  syöttämään hakukenttään perustettavan ryhmän nimi. Mikäli käyttäjän valitsema ryhmän nimi on jo olemassa, tapahtumaa ei voida suorittaa ja käyttäjä saa 
  tästä ilmoituksen. Valitsemalla sivun keskiosasta oman ryhmän, avautuu keskusteluikkuna, jossa on mahdollista lähettää pikaviestejä ryhmän muille jäsenille,
  tai navigoida ryhmän jäsenten luo. Henkilön paikantaminen on mahdollista ainoastaan jos paikannettava henkilö on samassa ryhmässä ja kirjautuneena sovellukseen.    

- Lukujärjestys: Tältä sivulta käyttäjä voi katsoa päivän oppitunnit. Viikonpäivää voi vaihtaa vetämällä sormella haluamaansa suuntaan vasemmalle tai oikealle.
  Painamalla yksittäistä oppituntia, avautuu näkymään ikkuna valitun oppitunnin tarkempine tietoineen. Lisäksi avattu ikkuna sisältää Navigointi/Nuoli-painikkeen,
  josta siirrytään karttanäkymään paikantamaan valitun oppitunnin työtila.   


----------------
* listaa käyttöliittymän näkymät
* niiden keskinäiset suhteet
* kuvaile mitä näkymässä tapahtuu / tehdään
