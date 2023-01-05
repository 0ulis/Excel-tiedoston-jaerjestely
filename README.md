# .xlsx-tiedoston-muokkaus
Tätä koodia voidaan käyttää yritykselle, joka haluaa muokatun sekä puhdistetun datatiedoston, joka sisältää työntekijöidensä kyselyvastaukset. Ohjelma alkaa tuomalla tarvittavat kirjastot ja lukemalla datatiedostoon pandan read_excel-funktiolla. Sitten se luo tiedoista kopion varmuuskopiointia varten ja poistaa tietyt sarakkeet, jotka sisältävät yksityisiä tietoja.

Seuraavaksi ohjelma käyttää sulatustoimintoa datan muokkaamiseen sekä tehdäkseen siitä visuaalisesti houkuttelevamman. Se myös tuo erillisen tiedoston, joka sisältää kyselyssä esitetyt kysymykset ja yhdistää sen päätietotiedostoon yhdistämistoiminnolla.

Lopuksi ohjelma nimeää osan sarakkeista uudelleen kuvaavammiksi nimiksi ja hylkää kaikki jäljellä olevat rivit, jotka sisältävät nolla-arvoja. Sitten se tallentaa muokatut tiedot uuteen Excel-tiedostoon käyttämällä to_excel-funktiota.

Kaiken kaikkiaan tämä ohjelma on hyödyllinen kyselytietojen puhdistamisessa sekä järjestämisessä luettavampaan muotoon, mikä voi auttaa yritystä analysoimaan ja ymmärtämään työntekijöidensä vastauksia.
