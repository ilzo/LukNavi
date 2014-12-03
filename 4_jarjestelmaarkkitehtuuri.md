


![Use case diagram](http://users.metropolia.fi/~arttusp/Pyramidi.png)

###Järjestelmä arkkitehtuuri

Ohessa kuvailtu ohjelmiston järjertelmän rakenne

***Lukujärjestys***
![Use case diagram](http://users.metropolia.fi/~arttusp/lukkari.png)


Lukujärjestys tilassa opiskelija/opettaja voi katsoa tietyn päivän lukujärjestyksensä (Oletuksena kyseinen viikonpäivä)
Lukujärjestys palvelu on yhdistetty lukkarit.metropolia.fi sivuun, josta henkilön tallennettu lukujärjestys luetaan.

***Navigointi***

![Use case diagram](http://users.metropolia.fi/~arttusp/kartta2.png)
Navigointi tila voidaan yhdistää joko lukujärjestys- tai vapaat työtilat-tilaan. Navigointi palvelulla käyttäjä voi navigoida haluamaansa
kohteeseen kampuksen sisällä. Navigointi perustuu langattoman lähiverkon tukiasemien pohjalta tehtyyn tietokantaan, josta kyseisen huoneen/tilan
paikkatieto luetaan.


***Työryhmät***
//Kuva käyttäliittymän työryhmät tilasta

Työryhmät tilassa käyttäjä voi koota uusia tai liittyä valmiiseen työryhmään. Työryhmän sisällä voidaan käydä realiaikaista viestintää 
pikaviesti ohjelman tavoin. Keskustelu sekä työryhmä tietokanta perustuu tuubin työryhmä tietokantaan ja sen muokkaamiseen.

***Vapaat työtilat***

//Kuva käyttäliittymän vapaat työtilat tilasta

Vapaat työtilat tilassa käyttäjä voi etsiä vapaita ATK-/auditointi-huoneita. Järjestelmä perustuu Metropolian Pakki tilanvaraus-järjestelmään,
jonka tietokannasta luetaan tilan varaustilanne. (Huomioitavaa, että ohjelman avulla ei voida varata kyseistä työtilaa.)
Käyttäjä voi halutessaan navigoida kohteeseen ja siirtyä navigointi tilaan
