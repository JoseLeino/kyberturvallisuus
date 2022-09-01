# Tietotuvan määritelmä

Tietoturvan klassiseen määritelmään kuuluu 3 osa-aluetta:
1. Luottamuksellisuus (Confidentality)
2. Eheys (Integrity)
3. Käytettävyys (Availability)

Nykyisin ajatellaan, että näiden lisäksi on huolehdittava myös

4. Pääsynvalvonnasta (Access control)
5. Kiistämättömyydestä (Nonrepudiation)

## Luottamuksellisuus
Tiedot ovat vain niihin oikeutettujen henkilöiden käytössä. -> käyttöoikeuksien hallinta

## Eheys
Tiedot ovat paikkaansa pitäviä ja liittyvät toisiinsa oikealla tavalla.

## Käytettävyys
Tiedot ovat tarvitsijan saatavilla järjellisessä ajassa. Tiedot eivät pääse häviämään tai yhteydet tietovarastoihin eivät katkea liian pitkäksi ajaksi.

## Pääsynvalvonta
Ulkopuoliset henkilöt eivät pääse luvatta käyttämään laitteistoja tai tietoverkkoja.

## Kiistämättömyys
Tiedetään kuka tietojärjestelmiä käyttää ja voidaan osoittaa kuka teki muutoksia tietoihin tai katseli niitä -> lokijärjestelmät ja sähköinen tunnistus eli autentikaatio (authentication).

# Riskienhallinta
Tietoturvallisuuden ylläpito on osa riskienhallintaa. Siihen kuuluu riskien tunnistaminen (etsiminen, assesment), niiden vaikutusten arviointi (mitä vaikuttaa, jos vahinko tapahtuu, evaluation) sekä miten riskeihin reagoidaan (counter measures).

## Riskikartoitus
Mitä vahinkoja on tapahtunut ja mitä voisi tapahtua -> realisoituneet riskit ja potentiaaliset riskit sekä tulevaisuus eli uhkakuvat

## Vaikutusten arviointi
Mitä vahingon tapahtuminen aiheuttaa organisaatiolle. Luokitus apuna:

* Hyväskyttävä riski -> ei vaikutusta toimintaan
* Tavanomainen riski -> haittaa toimintaa, taloudellisia menetyksiä
* Sietämätön riski -> toiminta keskeytyy tai päättyy kokonaan, suuria taloudellisia menetyksiä, kenties konkurssi

Luokitus voi olla moniportainen tai yksinkertaistettu, kuten edellä.

## Riskin realisoitumisen todennäköisyys
Miten usein riski todennäköisesti realisoituu esim.

* Aärimmäisen harvoin 1 pistettä
* N. viiden vuoden sisällä 2 pistettä
* Vuoden-parin välein 3 pistettä
* Useammin 4 pistettä

![Riskienevaluointitaulukko](https://user-images.githubusercontent.com/24242044/187872500-7091f8b2-996d-4195-a302-d80596b08bb1.png)

Organisaation ylin johto määrittelee hyväksyttävän riskin rajat eli kuinka yleinen tai vaikutuksiltaan suuri riski voidaan hyväksyä.

## Riskeihin varautuminen

Riskeihin voi (ainakin ISO standardien mukaan) reagoida ainoastaan 3:lla tavalla

* Hyväksytään riski, otetaan tietoisesti riski, koska vahinko on vaaraton tai äärimmäisen harvinainen
* **Pienennetään riskiä**, tehdään varotoimenpiteitä, ettei vahinkoa sattuisi -> varaudutaan
* Siirretään riski jonkun muun kannettavaksi -> ulkoistaminen tai vastuuvakuutukset

# RASEKO:n tietojärjestelmät

Rasekolla on n. 400 yksittäistä työasemaa, joitakin omia palvelimia sekä pilveen sijoitettuja tietojärjestelmiä. RASEKO:n tietotekniset palvelut ylläpitävät kampusalueen verkkoja. Internet-yhteyksistä vastaa 3 vuoden välein kilpailutettava operaattori.

![RasekonTietojärjestelmät](https://user-images.githubusercontent.com/24242044/187894893-96e393a7-317a-46b0-b465-35eef771e86a.png)
