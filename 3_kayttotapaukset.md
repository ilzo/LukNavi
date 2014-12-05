## Käyttötapaukset

Sovelluksen ensisijaiset loppukäyttäjät ovat Metropolia Ammattikorkeakoulun opiskelijoita.
Toissijaiset loppukäyttäjät ovat opettajia. Opettajien ja oppilaiden käyttötapaukset ovat hyvin 
samankaltaisia.

Ohessa käyttötapauskaavio keskeisine käyttötapauksineen:

![Use case diagram](http://users.metropolia.fi/~ilariju/Ohjelmistotuotanto/UseCase_Diagram2.png)


###Käyttötapausskenaariot

Ohessa on listattu muutamien keskeisten käyttötapausten käyttötapausskenaariot:

**Hae valitun luokan/työtilan sijainti kartalta**

- Alkutila: Käyttäjä on sisäänkirjautuneena sovelluksen päävalikossa ja huomaa ylälaidassa olevasta 
tietoikkunasta oppitunnin alkavan pian. Käyttäjä ei tiedä missä tilassa tunti pidetään, ja haluaa 
selvittää tämän siirtymällä karttanäkymään.

- Normaali kulku: Käyttäjä painaa seuraavaksi alkavan oppitunnin tietoikkunan alakulmassa olevaa 
Navigointi/Nuoli-ikonia, joka avaa karttanäkymän. Karttanäkymässä käyttäjä näkee itsensä punaisena nuolena.
Kartta laskee käyttäjälle lyhyimmän mahdollisen reitin määränpäähän, ja välimatka piirretään kartalle 
vihreänä reittiviivana. Käyttäjä kävelee kartan opastamaan suuntaan ja reitti sekä kartan keskitys 
päivittyvät karttanäkymään käyttäjän siirtymän mukaan. 

- Lopputila: Käyttäjä saapuu määränpäähän ja sulkee karttanäkymän puhelimen peruutus -painikkeesta.

- Mikä voi mennä pieleen: Yksittäiseen koulun wi-fi-tukiaseman vioittuessa tai signaalihäiriöiden sattuessa
tapahtuu virheitä karttanäkymän päivityksessä.

- Vaihtoehtoiset tapahtumat: 
	- Käyttäjä painaa vahingossa Navigointi/Nuoli-ikonin sijaan oppitunnin tietoikkunaa, ja avaa sivun jossa on tarkennettua 
	  informaatiota opintojaksosta. Käyttäjä painaa avautuneella sivulla sijaitsevaa Navigointi/Nuoli-ikonia siirtyäkseen navigointitilaan
      karttanäkymään.
	- Käyttäjä sulkee karttanäkymän vahingossa painamalla puhelimen peruutus-painiketta.
	- Käyttäjä hakee myöhemmin alkavan oppitunnin lukujärjestyksestä ja siirtyy Navigointi/Nuoli-ikonilla 
	  karttanäkymään hakemaan reitin kyseisen oppitunnin työtilaan. 
    
**Perusta oma työryhmä**

- Alkutila: Käyttäjä on sisäänkirjautuneena sovelluksen päävalikossa, ja haluaa perustaa oman työryhmän
  paikantaakseen opiskelutoverinsa ja pitääkseen heihin yhteyttä sovelluksen kautta. 

- Normaali kulku: Käyttäjä siirtyy Ryhmienhallintasivulle painamalla päävalikossa "Työryhmät"-painiketta. 
  Työryhmät-sivulla käyttäjä pääsee perustamaan uuden ryhmän painamalla sivun ylälaidassa olevaa 
  "+"-painiketta. Käyttäjä syöttää avautuvaan tekstikenttään ryhmän nimen ja painaa enter. Käyttäjä
  hakee ystäviään painamalla Hakukentän vieressä olevan Henkilöhakupainikkeen aktiiviseksi ja kirjoittamalla henkilön nimen
  Hakukenttään. Kun haettu henkilö palautetaan järjestelmästä sivun keskiosaan hakutuloksiin, käyttäjä valitsee haetun henkilön ja 
  lähettää tälle kutsun liittyä perustamaansa työryhmään. Saapuneet kutsut näytetään huutomerkki-ilmoituksina vastaanottajan päävalikon Työryhmät-
  painikkeen kohdalla. 
  
- Lopputila: Hyväksyttyään kutsut, käyttäjän ystävät kuuluvat tämän perustamaan ryhmään,
  ja ryhmän jäsenet voivat paikantaa toisiaan koulualueella ja kommunikoida ryhmächatissa keskenään niin 
  kauan kuin ovat sisäänkirjautuneena sovellukseen ja heillä on puhelimien verkkoyhteydet aktiivisina.

- Mikä voi mennä pieleen: Käyttäjä ei voi luoda ryhmää, koska hänen nimeämä ryhmä on jo olemassa.   

- Vaihtoehtoiset tapahtumat: Käyttäjä luo työryhmän nimellä "SuomenSuurinProjekti", jonka myöhemmin huomaa olevan 
  epäsovelias työryhmän kokoonpanoon ja tavoitteisiin nähden. Hän poistaa äskettäin luodun ryhmän järjestelmästä, ja 
  luo uuden ryhmän nimellä "EspoonSuurinProjekti".


**Lähetä pikaviesti ryhmälle**

- Alkutila: Käyttäjä on sisäänkirjautuneena sovelluksen päävalikossa, ja haluaa lähettää pikaviestin oman ryhmänsä jäsenille.

- Normaali kulku: Käyttäjä siirtyy Ryhmienhallintasivulle painamalla päävalikossa "Työryhmät"-painiketta. Työryhmät-sivulla käyttäjä valitsee 
  haluamansa ryhmän luettelosta sivun keskiosasta. Painettuaan haluamaansa työryhmää, näkymään avautuu ryhmän keskusteluikkuna. Keskusteluikkunassa 
  käyttäjä kirjoittaa viestinsä tekstinsyöttökenttään ja painaa vieressä olevaa "Lähetä" -painiketta, jolloin viesti lähetetään keskusteluikkunan 
  Chat-kenttään. 

- Lopputila: Viestin lähetettyään käyttäjä poistuu keskusteluikkunasta painamalla puhelimen peruutus-painiketta, ja edelleen Ryhmienhallintasivulta
  painamalla puhelimen peruutus-painiketta.

- Mikä voi mennä pieleen: Mahdollisten yhteyshäiriöiden takia käyttäjän lähettämää viestiä kuljettavat datapaketit korruptoituvat tai putoavat matkan 
  varrelta, ja näin ollen viesti ei tallennu järjestelmään eikä tulostu keskusteluikkunan Chat-kenttään. 

- Vaihtoehtoiset tapahtumat: Käyttäjä kirjoittaa viestejä keskusteluikkunassa ryhmälleen, ja haluaa löytää ryhmän jäsenen sijainnin kartalta. Käyttäjä 
  valitsee keskusteluikkunan oikeasta laidasta jäsenluettelosta ryhmän jäsenen, ja tämän jälkeen painaa "Lähetä"-painikkeen vieressä olevaa Navigointi/Nuoli-painiketta.
  Käyttäjä siirtyy karttanäkymään navigoimaan valitun ryhmän jäsenen luokse.   


