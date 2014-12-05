


![Use case diagram](http://users.metropolia.fi/~arttusp/Pyramidi.png)

##Järjestelmäarkkitehtuuri

Ohessa kuvailtu ohjelmiston järjestelmän rakenne

***Lukujärjestys***



Lukujärjestys-tilassa opiskelija/opettaja voi katsoa tietyn päivän omasta lukujärjestyksestä (Oletuksena kyseinen viikonpäivä)
LukNavin Lukujärjestys-palvelu suorittaa käyttäjän tietoihin perustuvan lukujärjestyksen kyselyn Tuubi-portaalin Lukkarikoneelta.

***Navigointi***


Navigointitila suoritetaan painamalla oppituntien tai työtilojen ikkunoiden yhteydessä esiintyviä Navigointi/Nuoli-ikoneja. Navigointi-palvelulla käyttäjä voi navigoida haluamaansa
kohteeseen kampuksen sisällä. Navigointi perustuu langattoman lähiverkon tukiasemien pohjalta tehtyyn tietokantaan, josta kyseisen huoneen/tilan
paikkatieto luetaan. Karttanäkymään approksimoidaan käyttäjän mobiililaitteen lähettämän signaalin perusteella käyttäjän paikkakoordinaatit kartalla, ja lasketaan 
lyhin mahdollinen reitti käyttäjän valitsemaan määränpäähän.


***Työryhmät***


Työryhmät-tilassa käyttäjä voi perustaa uusia ryhmiä tai liittyä olemassaoleviin ryhmiin. Työryhmän sisällä jäsenet voivat lähettää reaaliaikaisia pikaviestejä toisilleen. 
Keskustelu- sekä työryhmä-tietokanta perustuu Tuubin työryhmä tietokantaan ja sen muokkaamiseen.

***Vapaat työtilat***



Vapaat työtilat -tilassa käyttäjä voi etsiä vapaita ATK-/auditointi-huoneita. Järjestelmä perustuu Metropolian Pakki tilanvaraus-järjestelmään,
jonka tietokannasta luetaan tilan varaustilanne. (Huomioitavaa, että ohjelman avulla ei voida varata kyseistä työtilaa.)
Käyttäjä voi halutessaan navigoida kohteeseen siirtymällä Navigointi-tilaan Navigointi/Nuoli-ikonia painamalla.
