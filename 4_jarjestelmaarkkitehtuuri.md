


![Use case diagram](http://users.metropolia.fi/~arttusp/Pyramidi.png)

##Järjestelmäarkkitehtuuri

Ohessa kuvailtu ohjelmiston järjestelmän rakenne

***Lukujärjestys***



Lukujärjestys-tilassa opiskelija/opettaja voi katsoa tietyn päivän omasta lukujärjestyksestä (Oletuksena kyseinen viikonpäivä)
Lukujärjestys-palvelu on yhdistetty lukkarit.metropolia.fi-sivuun, josta henkilön tallennettu lukujärjestys luetaan.

***Navigointi***


Navigointitila voidaan yhdistää joko lukujärjestys- tai vapaat työtilat-tilaan. Navigointi-palvelulla käyttäjä voi navigoida haluamaansa
kohteeseen kampuksen sisällä. Navigointi perustuu langattoman lähiverkon tukiasemien pohjalta tehtyyn tietokantaan, josta kyseisen huoneen/tilan
paikkatieto luetaan.


***Työryhmät***


Työryhmät-tilassa käyttäjä voi koota uusia tai liittyä valmiiseen työryhmään. Työryhmän sisällä voidaan käydä reaaliaikaista viestintää 
pikaviesti ohjelman tavoin. Keskustelu- sekä työryhmä-tietokanta perustuu Tuubin työryhmä tietokantaan ja sen muokkaamiseen.

***Vapaat työtilat***



Vapaat työtilat -tilassa käyttäjä voi etsiä vapaita ATK-/auditointi-huoneita. Järjestelmä perustuu Metropolian Pakki tilanvaraus-järjestelmään,
jonka tietokannasta luetaan tilan varaustilanne. (Huomioitavaa, että ohjelman avulla ei voida varata kyseistä työtilaa.)
Käyttäjä voi halutessaan navigoida kohteeseen ja siirtyä navigointi tilaan
