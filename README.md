# Lærestedsbeskrivelser

Her finner du lærestedsbeskrivelser for forskjellige studiesteder rundt om i verden.


## Rask introduksjon

- **Formål:** Effektivt samarbeid om å lage gode lærestedsbeskrivelser.
- **Open-source:** Jo flere som samarbeider, desto bedre blir det.
- **Kildefiler:** Vi tar vare på kildekode i `.tex` filer for fremtiden, istedet for å kun ta vare på `.pdf`.
- **Kvalitet:** Ved effektiv bruk av LaTeX og en mal får vi veldig høy kvalitet på lærestedsbeskrivelsene.


## Hvordan kan jeg bidra?
Finner du **skrivefeil**, **uklare setninger** eller har **ny** eller **oppdatert informasjon**?
Du kan bidra til å øke kvaliteten på lærestedsbeskrivelsene, og både små og store bidrag mottas med stor takk.
Du har to muligheter når du skal bidra: du kan lage **Issue** eller sende **Pull Request**. 
Du kan også bidra med å lage egne lærestedsbeskrivelser.


## Kom i gang
Her på GitHub lagres alle filene som er delt.
For å gjøre endringer, kan man enten redigere i browser (på egen branch), eller man kan laste ned alt lokalt og gjøre endringer for så å pushe disse opp og merge med resten.


### LaTex [https://www.latex-project.org/get/]
LaTex gjør alle `.tex` filene om til en sexy `.pdf`.
Installeres enkelt via vedlagt link.


### Git
Git er et programm som holder kontroll på filene.
GitHub er en plass hvor vi lagrer filene.
Du må installlere Git for å kunne hente ned filene til datamaskinen din.

For å kunne kjøre LaTex så må filene ned på lokal maskin, så derfor må Git installeres.
For å bruke GitHub må man lage en bruker der.

Hjelp til å komme i gang med Git og GitHub:
https://help.github.com/en/desktop/getting-started-with-github-desktop

Her er en liten intro om hvordan å redigere filer online:
https://guides.github.com/activities/hello-world/


### PDF of Markdown
Kjør LaTex for å generere `.pdf` som pushes opp på GitHub sammen med de nye/endrede `.tex` filene.

Man kan også kjøre følgende kommando i terminal for å lage en markdown som fungerer som en readme i gejeldende mappe. 
Sørg for å være i rett mappe (e.g. "München"). 
Man må også ha Pandoc installert (https://pandoc.org/installing.html).

```shell
pandoc -s index.tex -o README.md
```
Man kan igså generere en `.pdf` online ved å kopiere **linken** til relevant `index.tex` inn her:
https://latexonline.cc/

