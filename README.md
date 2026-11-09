# Sputtis Laki

**Vapaa-ajan projekti: paikallinen hakupalvelu, joka auttaa tavallista ihmistä löytämään omaan tilanteeseensa liittyvän suomalaisen lakitekstin.**

Tämä sivu on projektin esittely ja tilannekatsaus. Koodia, aineistoja tai testejä ei jaeta täällä. En lupaa säännöllisiä päivityksiä: sivua päivitetään silloin, kun jokin vaihe on valmis.

---

## Miksi

Juridiikkaa ei juuri opeteta koulussa, ja oikeudellinen apu on kallista. Moni nuori ja aikuinen jää siksi epävarmaksi omista oikeuksistaan ja velvollisuuksistaan, esimerkiksi työsuhteessa, vuokra-asumisessa tai viranomaisen päätöksessä.

Tavoitteena on työkalu, jolla kuka tahansa voi turvallisesti selvittää, mitä laki sanoo hänen tilanteestaan, ja ymmärtää paremmin, milloin kannattaa hakea ammattilaisen apua. Työkalusta voisi olla hyötyä myös oikeustieteen opiskelijoille.

## Lupaus käyttäjälle

- **Jokainen näytetty lakiteksti on sanatarkasti Finlexistä**, ja sen versiopäivä näkyy.
- **Tarkistamatonta väitettä ei näytetä.** Jos lähdettä ei löydy, vastaus on **"en löytänyt"**. Arvaamista ei ole.
- **Kysymyksiä ei tallenneta eikä lähetetä verkkoon.** Kaikki käsittely tapahtuu omalla koneella.

**Tämä ei ole oikeudellista neuvontaa.** Työkalu näyttää lain sanamuodon ja lähteet. Se ei korvaa juristia, eikä se tee päätöksiä käyttäjän puolesta. Juristitkin ovat usein eri mieltä siitä, miten lakia sovelletaan, joten työkalu ei voi olla aina oikeassa. Siksi se kertoo rehellisesti, kun se ei löydä vastausta.

## Missä ollaan nyt (marraskuu 2026)

**Valmista:**
- Voimassa olevat lait Finlexin avoimesta datasta, noin 148 000 pykälää. Jokainen pykälä on tarkistettu koneellisesti sanatarkasti alkuperäistä Finlexin aineistoa vasten.
- Haku, joka yhdistää sanahaun ja merkityksen mukaisen haun.
- Lukija, joka näyttää vain sanatarkasti tarkistettuja lainauksia. Automaattisissa mittauksissa keksittyjä lainauksia on ollut 0.
- Automaattinen testisarja, jolla jokainen muutos tarkistetaan ennen käyttöönottoa. Osa testeistä on lukittu, eikä niitä käytetä virittämiseen.

**Tärkeä rajoitus:** kaikki tähänastiset tarkistukset ovat koneellisia. Testisarjan oikeat vastaukset on laatinut tekoäly, ja projektin tekijä on hyväksynyt ne. Juristi ei ole vielä tarkistanut niitä. Siksi mittaustulokset ovat suuntaa antavia, kunnes juridinen ammattilainen on käynyt ne läpi.

**Työn alla:**
- **Haun tarkkuus arkikielisillä kysymyksillä.** Mittausten mukaan haku löytää oikean pykälän usein, mutta järjestää sen liian alas. Joillakin oikeusaloilla, kuten uhkasakko, ulosotto ja oikeudenkäyntimenettely, haku jää vielä heikoksi.
- Parannuksia kokeillaan yksi kerrallaan, ja jokainen mitataan ennen käyttöönottoa.

**Seuraavaksi:**
- Ensimmäinen ihmisen tekemä tarkistus: juridinen ammattilainen käy läpi testisarjan ja arviointiaineiston, jotta parannukset voidaan mitata luotettavasti.

## Haen apua: juristi tai lakimies, myös eläkkeellä oleva

Etsin juridista ammattilaista, joka voisi auttaa arvioinnissa. Työ on käytännössä sitä, että valmiista listasta merkitään, mitkä pykälät oikeasti liittyvät kuhunkin tilanteeseen. Aineisto on julkisia oikeusratkaisuja, eikä siinä ole henkilötietoja.

Aloitetaan noin 10 tapauksen kokeilulla, joka vie arviolta 1–2 tuntia. Sen jälkeen nähdään, kuinka paljon aikaa yksi tapaus todella vie, ja voit päättää, jatkatko ja kuinka paljon. Pienikin apu on arvokasta: jokainen tarkistettu tapaus vie projektia eteenpäin ja antaa sille mahdollisuuden kehittyä oikeasti toimivaksi. Työn voi tehdä omaan tahtiin.

Projekti on vapaaehtoinen, eikä minulla ole rahaa maksaa työstä. Autan mielelläni vastineeksi esimerkiksi käytännön töissä, joista sovitaan erikseen.

## Pitkän aikavälin toive

Paras tilanne olisi, että ihminen kävisi läpi kaikki vaikeat tapaukset ja jokaisen uuden lisäyksen. Kone voi tarkistaa, että lakiteksti on sanatarkka, mutta vain juridinen ammattilainen voi arvioida, liittyykö pykälä oikeasti tilanteeseen.

Jos työkalusta tulee toimiva ja hyödyllinen, toiveeni on, että sen kehittämistä voitaisiin joskus tukea myös julkisesti. Silloin esimerkiksi oikeustieteen opiskelijat voisivat tehdä tarkistustyötä kesätöinä tai harjoitteluna. Se tekisi työkalusta luotettavamman ja antaisi opiskelijoille käytännön kokemusta. Tämä on toive eikä suunnitelma, eikä mikään taho ole sitoutunut siihen.

## Ota yhteyttä ja ehdota ideoita

Voit jättää viestin tai ehdotuksen tämän sivun **Issues**-osioon.

**Älä kirjoita sinne omaa oikeudellista asiaasi tai henkilötietojasi.** Viestit näkyvät kaikille. Ehdotukset, palaute ja yhteydenotot avusta ovat tervetulleita.

---

Lakitekstien lähde: Finlex (oikeusministeriö), avoin data.

---

**In English:** Sputtis Laki is a personal, non-commercial project: a local search tool that helps ordinary people find the Finnish law text relevant to their situation. Every quoted law text is verbatim from Finlex; if no source is found, the answer is "not found". All checks so far are automated; no legal professional has reviewed the test answers yet. Questions are processed locally and never stored or sent online. This is not legal advice. Code is not shared here. I'm looking for a Finnish legal professional, retirees welcome, to help evaluate search results on a volunteer basis.
