# h3 Hello Web Server
## Tein harjoituksen kotona 1.2.-2.2.2026. Koneena oli Asus Vivobook 15.
## x) Lue ja tiivistä
- IP- base virtual hosting käyttää IP osoitetta määrittääkseen mikä virtual host palvellaan.
- Name-based virtual hosting luottaa siihen, että asiakasohjelma ilmoittaa isätänimen osana HTTP-otsikoita

- Yleensä on yksi IP osoite joka isännoi montaa nettisivua. Apachen kanssa sinulla voi olla monta verkkotunnusta yhdellä IP osoitteella.

## a)

<img width="634" height="273" alt="image" src="https://github.com/user-attachments/assets/81595ff8-2bf0-4b13-8d93-397aa536d568" />

09:00 webbipalvelin vastaa

## b)

<img width="816" height="218" alt="image" src="https://github.com/user-attachments/assets/e2005ab5-cc8b-403c-b356-c4842860a394" />

09:42 Syötin kuvassa olevan komennon ja tulosteessa näkyy:

-127.0.0.1 on IP-osoite

-[02/Feb/2026:09 :43 :15 +0200] on kellon aika, päivämäärä ja aika vyöhyke

- "GET /favicon.iso HTTP/1.1" ovat HTTP malli, url ja käytetty versio

- 404 on status koodi

- 527 koko bitteinä

- http://localhost/" on osoite

- "merkkien väli" on haku kone ja käyttöjärjestelmä mitä käyttäjä käyttää

Lähde: https://signoz.io/guides/apache-log/

## c)

10:15 Syötin kuvassa olevat komennot

<img width="810" height="518" alt="image" src="https://github.com/user-attachments/assets/c7f44631-9f68-48b6-9ce4-fe5a7316c159" />

Nanoon syöttämäni teksti

<img width="819" height="514" alt="image" src="https://github.com/user-attachments/assets/5f7bdccb-0068-4aa0-a30a-ac9aa2425310" />


- 10:30 sivu toimii

<img width="945" height="469" alt="image" src="https://github.com/user-attachments/assets/32fb33e1-fa0f-41bb-8c02-75f3a15ad328" />

## e) 

11:30 html sivun koodi on valmis

<img width="825" height="516" alt="image" src="https://github.com/user-attachments/assets/0981da08-deaf-444f-a988-83cca95c0c65" />

11:30 sivu näyttää tältä

<img width="1274" height="795" alt="image" src="https://github.com/user-attachments/assets/e2c2e727-4f0d-4d65-ba7d-218c958c3ea0" />

## f)

11:35 curl käytetään siirtämään dataa servereiltä. 

11:00 curl ja sen tuloste. Curl tulostaa osoitteen koko sisällön

<img width="818" height="400" alt="image" src="https://github.com/user-attachments/assets/500a4c99-e124-4fe9-b2dd-7d94e70fc9c9" />


11:40 curl -I ja sen tuloste. Curl -I tulostaa otsakkeet. HTTP/ 1.1 200 ok tarkoittaa, että sivu löytyy ja toimii. Content-Type kertoo millaista dataa sivu sisältää. Tässä tapauksessa html tiedoston. 

<img width="809" height="252" alt="image" src="https://github.com/user-attachments/assets/ea1345d3-0e9c-4452-87eb-97c2982949c8" />


Lähde: https://developer.ibm.com/articles/what-is-curl-command/

# Lähteet

Tero Karvinen, 2024 Linux palvelimet: https://terokarvinen.com/linux-palvelimet/

Tero Karvinen, 2024 Linux palvelimet: https://terokarvinen.com/2018/04/10/name-based-virtual-hosts-on-apache-multiple-websites-to-single-ip-address/

Simran Kumari, 2024 Complete Guide to Apache Logs: https://signoz.io/guides/apache-log/

IBM, 2024 What is cURL and how does it relate to APIs?: https://developer.ibm.com/articles/what-is-curl-command/

