# h2 komentaja pingviini
## Tein harjoituksen kotona 24.01.-26.01.2026. Koneena oli Asus Vivobook 15.
## Command line basics revisited - tiivistelmä
- PWD eli print working directory tekee nimensä mukaisen komennon.
- '#' käytetään kommentoimiseen
- ls listaa mitä tidostoja on kansioissa
- cd eli change directory tarvitsee jonkun kansion mihin siirtyä
- cd.. menee "taakse päin" kansioissa

Teksti editoreita ovat pico ja nano
- Kansioita luodaan komennolla mkdir (uusikansionimi)
- cp -r poistaa tyhjän kansion ja rmdir poistaa tiedoston
- rm poistaa kansion ja sen sisällön!

Ohjelmien asennus
- sudo apt-get  update= hakee ilmeisimmin uusimmat päivitykset muttei asenna niitä?

## Komentaja Pingviini
- 16:35 Aloitin asentamalla micron, komennolla "sudo apt install micro". Syötin salasanan ja terminal alkoi lataamaan ohjelmaa. Tarkisitin toimiiko micro komennolla "micro". - Onnistui

<img width="903" height="646" alt="image" src="https://github.com/user-attachments/assets/c0654d53-c94b-4df1-9616-da0539ca7108" />

 <img width="1275" height="787" alt="image" src="https://github.com/user-attachments/assets/8f149ad6-72ad-4d00-8982-5df4e0b91ab0" />

- 16:48 Etsin netistä TUI ja CLI terminaaliohjelmia ja valitsin tree nano ja htop, koska tunnistin treen ja nanon tunnilta. Käytin komentoa "sudo apt install tree nano htop", jotta kaikki kolme latautuisivat kerralla. Nano oli jo asennettu, mutta htop ja tree latautuivat. - Onnistui
Lähteet: https://github.com/rothgar/awesome-tuis

<img width="1100" height="722" alt="image" src="https://github.com/user-attachments/assets/3d55c8e7-ed5f-4cc9-b534-140b43ebd79a" />

- 16:50 Päätin ladata wget nimisen CLI- Onnistui

<img width="817" height="511" alt="image" src="https://github.com/user-attachments/assets/4b29ec54-1569-497e-b710-e47210073921" />

- 10:40 Raportin tekeminen jatkuu.

- 10:44 Tein kuvissa näkyvät komennot

<img width="822" height="515" alt="image" src="https://github.com/user-attachments/assets/34ab158f-5996-470f-9280-d067faf3f766" />

<img width="825" height="362" alt="image" src="https://github.com/user-attachments/assets/9a77755f-628f-46c4-a322-868ba0974db2" />

11:15 Etsin netistä grep- komentoja ja koitin selvittää niiiden käyttö tarkoitusta. https://www.redhat.com/en/blog/how-to-use-grep
11:19 Syötin komennot mitkä näkyvät alla olevassa kuvassa.

<img width="823" height="516" alt="image" src="https://github.com/user-attachments/assets/04fac451-ffcf-4638-9bc1-090bfdc4f788" />

11:25 alla olevassa kuvassa esimerkki putkesta

<img width="826" height="508" alt="image" src="https://github.com/user-attachments/assets/0747a920-a03c-4b9c-acca-97d0c5dcf522" />

11:32 syötin komennon "sudo lshw -short -sanitize" ja terminal tulosti kuvassa olevan taulukon.

<img width="1048" height="756" alt="image" src="https://github.com/user-attachments/assets/5e9ad350-d912-45ac-b1bc-71e1a5333f85" />

11:33 Raudan analysointi:

System on Virtualbox eli virtuaalikone, ei fyysinen kone. Muistin koot ovat minun asettamia arvoja koneen asennusvaiheessa. 67GB on minun asettama kiintolevy koko. Prosessorina toimii minun fyysisen koneen prosessori, koska virtuaali kone tarvitsee prosessorin toimiakseen isäntäkoneella. Multimedia viittaa virtuaalikoneen äänen kuulumiseen mikä mahdollistaa esim. videoiden mahdollisen pyörittämisen. 

# Lähteet

Tero Karvinen, 2024 Linux palvelimet: https://terokarvinen.com/linux-palvelimet/

Tero Karvinen, 2024 Linux palvelimet: https://terokarvinen.com/2020/command-line-basics-revisited/?fromSearch=command%20line%20basics%20revisited

arimxyer and claude, 2026 Awesome TUIs: https://github.com/rothgar/awesome-tuis
