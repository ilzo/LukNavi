## Käyttötapaukset

Sovelluksen ensisijaiset loppukäyttäjät ovat Metropolia Ammattikorkeakoulun opiskelijoita.
Toissijaiset loppukäyttäjät ovat opettajia. Opettajien ja oppilaiden käyttötapaukset ovat hyvin 
samankaltaisia.

Ohessa käyttötapauskaavio keskeisine käyttötapauksineen:

![Use case diagram](http://users.metropolia.fi/~ilariju/UseCase_Diagram1.png)


###Käyttötapausskenaariot

Ohessa on listattu tärkeimpien käyttötapauksien käyttötapausskenaariot:

**Hae valitun luokan/työtilan sijainti kartalta**

- Alkutila: Opiskelija on sisäänkirjautuneena sovelluksen päävalikossa ja huomaa ylälaidassa olevasta 
tietoikkunasta oppitunnin alkavan pian. Opiskelija ei tiedä missä tilassa tunti pidetään, ja haluaa 
selvittää tämän siirtymällä karttanäkymään.

- Normaali kulku: Opiskelija painaa seuraavaksi alkavan oppitunnin tietoikkunan alakulmassa olevaa 
kompassi-ikonia, joka avaa karttanäkymän. Karttanäkymässä opiskelija näkee itsensä punaisena nuolena.
Kartta laskee opiskelijalle lyhyimmän mahdollisen reitin määränpäähän, ja välimatka piirretään kartalle 
vihreänä reittiviivana. Opiskelija kävelee kartan opastamaan suuntaan ja reitti sekä kartan keskitys 
päivittyvät karttanäkymään opiskelijan siirtymän mukaan. 

- Lopputila: Opiskelija saapuu määränpäähänsä ja sulkee karttanäkymän puhelimen peruutus -painikkeesta

- Mikä voi mennä pieleen: Yksittäiseen koulun wi-fi-tukiaseman vioittuessa tai signaalihäiriöiden sattuessa
tapahtuu virheitä karttanäkymän päivityksessä.

- Vaihtoehtoiset tapahtumat: 
	- Opiskelija painaa vahingossa kompassi-ikonin sijaan tietoikkunaa, ja avaa sivun jossa on tarkennettua 
	  informaatiota kurssista.
	- Opiskelija sulkee karttanäkymän vahingossa painamalla puhelimen peruutus-painiketta.
	- Opiskelija hakee myöhemmin alkavan oppitunnin lukujärjestyksestä ja siirtyy kompassi-ikonilla 
	  karttanäkymään hakemaan reitin kyseisen oppitunnin työtilaan. 
    




--------------
* Määritä tänne järjestelmän loppukäyttäjät
* Käyttötapauskaavio, jossa järjestelmän keskeiset käyttötapaukset
* Kuvaile tärkeimmät käyttötapauksista käyttötapausskenaarioina mallipohjaan perustuen
  * mallipohja: määritä alkutila (initial state), normaali kulku (normal flow), lopputila (end state)
  * kerro myös kuinka normaali kulku voi mennä pieleen sekä
  * mahdolliset vaihtoehtoiset kulut (alternate flow)