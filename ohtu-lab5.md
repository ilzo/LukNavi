## Harjoitus 5: Käyttöliittymän suunnittelu

#### 1. Selitä seuraavat käsitteet:

  1. Näkymä (view)
    - Jokin käyttäjälle näkyvä osa sovelluksen käyttöliittymästä, esim. etusivuikkuna, päävalikko, yms.
  
  2. Wireframe
	- Sivuston tai sovelluksen pohjakaaviokuva, luuranko. Karkea rautalankamalli.
  3. Mockup
	- Luonnos käyttöliittymänäkymästä joko piirrettynä paperille tai tietokoneen piirtotyökalulla.
  4. Prototyyppi
	- Varhainen malli tai versio sovelluksesta, joka sisältää joitakin toiminnallisuuksia.
	  Prototyyppi on demoversio, jonka on mahdollista jollakin tasolla vuorovaikuttaa käyttäjän kanssa,
	  mutta ei sisällä kaikkia mahdollisia toiminnallisuuksia mitä lopullinen malli. 

#### 2. Käyttöliittymän näkymät (User interface, views), oma projektiaihe. Voi tehdä pienryhmissä. 

1. Miten käyttötapaukset ja käyttöliittymät voisi yhdistää toisiinsa vaatimusmäärittelydokumentaatiossa? Perustele
vastauksesi.
	- Käyttötapaukset ovat lyhyitä ja selkeitä kuvauksia, mitä sovelluksella on mahdollista pystyä tekemään. 
      Yksittäisiä käyttötapauksia voi hyödyntää käyttöliittymän vaatimusmäärittelyssä siten, että tietty 
	  käyttötapauksen kuvaama ominaisuus tai toiminto on löydyttävä ja oltava todennettavissa käyttöliittymästä.	

2. Listaa järjestelmän käyttöliittymän olennaisimmat näkymät
	- Kirjautumissivu
	- Päävalikko/Hakusivu
	- Karttanäkymä
	- Lukujärjestys
	- Ryhmienhallintasivu (onko ryhmächat-ikkuna samalla sivulla vai omalla?)


3. Kuvaile näkymät *sanallisesti*: mitä näkymällä tehdään ja mitä siinä näkyy. Pyri määrittelemään tässä näkymät
*toiminnallisesta näkökulmasta*, älä niinkään ajattele miltä ne näyttävät
	- Kirjautumissivu: Käyttäjä/Opiskelija kirjautuu tässä ikkunassa sovellukseen omilla tuubi-käyttäjänimellään 
	ja salasanallaan, ja painamalla "Kirjaudu" -painiketta. 
	
	- Päävalikko/Hakusivu: Tälle näkymälle sijoittuu tiedot oppilaan seuraavaksi alkavasta oppitunnista omaan tietoikkunaan
	  sivun ylälaitaan. Tietoikkunan oikeassa alakulmassa on kompassi-painike, josta siirrytään karttanäkymään. Tietoikkunan
	  alapuolella on painikkeet "Lukujärjestys", "Vapaat työtilat" ja "Työryhmät". 
	- Karttanäkymä: Kaksiulotteinen pohjakartta koulun sisätiloista, jossa käyttäjää edustaa punainen nuoli.
	Riippuen mitä oppituntia tai työtilaa haetaan, käyttäjä ohjataan määränpäähän reittiviivalla. Reittiviiva 
	ja karttanäkymä päivittyvät ruudulla sitä mukaan kun käyttäjä liikkuu.

4. Määritä näkymien väliset siirtymät korkealla tasolla, mistä näkymästä pääsee minnekin? Millä tavoin visualisoisit tilasiirtymät?
	- Päävalikosta löytyy painike "Lukujärjestys", jota painamalla siirrytään Lukujärjestys -näkymään. 
	  Päävalikosta löytyy painike "Vapaat työtilat", joka avaa erillisen ikkunan, jossa varaamattomat työtilat lueteltuina.
	  Jokaisen työtilan vieressä on Kartta/Kompassi -painike, jota painamalla siirrytään karttanäkymään.
	  Päävalikossa on painike "Omat työryhmät", jota painamalla siirrytään ryhmienhallintasivulle.
5. Listaa jokaista näkymää kohti tieto siitä, millaista tietosisältöä tai data käyttöliittymässä näytetään.

#### 3. Visualisoi listaamasi näkymät ja niihin liittyvät siirtymät

- vähintään 3 näkymää
- Voit käyttää Painttia, Visiota tai esimerkiksi [Moqupsia](https://moqups.com/). 

**Palauta linkki projektinne tiedostoon (Github), mistä löytyvät vastaukset tehtäviin. Vaikka teitte työn ryhmätyönä, jokainen palauttaa linkin Tuubiin henkilökohtaisesti.**