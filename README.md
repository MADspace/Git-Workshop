Git Workshop
============
Door: Paul Wagener

Deelnemers:




Versie beheer systeem
-----------
Waarom zou je een versie beheer systeem willen gebruiken? Als je lang genoeg aan een project werkt maak je fouten en die zijn er niet altijd gemakkelijk weer uit te halen zijn. Het is dus handig om elke keer als we een versie hebben die _wel_ werkt om dit te kunnen op te slaan. Dat kunnen we natuurlijk doen door elke keer een kopie van het project te maken, maar dat resulteert al snel in een chaos van mapjes.

![Alt text](project-chaos.png)

Dat moet makkelijker kunnen!

Met een versie beheer systeem kunnen we wijzigingen aan een project vastleggen. Elke keer als we een wijziging hebben gedaan die werkt kunnen we een _commit_ doen. Daarmee leggen we vast hoe het project er op dat moment uit ziet. Als later het project niet meer werkt of als je per ongeluk iets verwijderd kan je altijd terug naar de versie die wel werkt.

### Andere versie beheer systemen

Er zijn meerdere versie beheer systemen beschikbaar, elk met hun plus- en minpunten. Populaire systemen zijn CVS, Subversion, Mercurial en Git. In deze workshop gaan we Git gebruiken.

**Voor mensen die alleen met Subversion hebben gewerkt:** Als je alleen nog maar met CVS en Subversion hebt gewerkt gaan een aantal dingen je verwarren. Bij Subversion ben je gewend om altijd op een centrale server te committen. Bij git commit je naar een lokale repository die je vervolgens synchroniseert. Bij Subversion ben je gewend om bijna nooit te branchen, want na een tijdje moet je mergen en mergen leid tot een hele dag conflicten oplossen. Bij git kan je branchen zonder dat je bang hoeft te zijn voor een pijnlijke merge later.

Installatie
------------------

Download: http://git-scm.com/download

We gaan Git alleen op de command prompt/terminal gebruiken. Er zijn ook onofficiele GUI's maar die verschillen per besturingssysteem.

We gaan eerst wat instellingen van Git veranderen

    git config --global color.ui auto
    
    git config --global --add alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit --all"

De eerste regel voegt kleurtjes toe aan de output van elke command. Met de tweede regel voegen we een commando toe die we later gaan gebruiken

We moeten ook nog aangeven wie we zijn zodat we later kunnen zien wie welke commit heeft gemaakt. Vul je eigen naam in in onderstaande commando's en voer ze uit.

    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com

Mijn eerste Git repository
-----------


    git init


Committen & Branchen
-----------

    git add .
    git commit

Concepten
-----------
SHA1