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



Installatie
------------------

Download: http://git-scm.com/download

    git config --global color.ui auto
    git config --global --add alias.lol "log --graph --decorate --pretty=oneline --abbrev-commit --all"

-

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