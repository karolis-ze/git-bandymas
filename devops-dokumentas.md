# Kas yra DevOps

DevOps yra programinės įrangos kūrimo ir IT operacijų komandų bendradarbiavimo kultūra bei praktikų visuma. Pagrindinis jos 
tikslas – pagreitinti ir automatizuoti kodo kelią nuo jo parašymo iki pateikimo galutiniam vartotojui. Užuot dirbus atskirai, 
programuotojai ir sistemų administratoriai kartu atsako už visą produkto gyvavimo ciklą. Tai leidžia dažniau išleisti 
atnaujinimus, greičiau pastebėti klaidas ir užtikrinti stabilesnį sistemų veikimą.

## Kur gali lūžti

1. **Automatinio testavimo etapas:** Jei testai parašyti prastai arba neapima svarbių scenarijų, į produkciją gali patekti 
kritinių klaidų turintis kodas.
2. **Diegimo (Deployment) procesas:** Netinkamai sukonfigūruoti serverio aplinkos kintamieji ar trūkstamos priklausomybės 
gali sustabdyti visos sistemos veikimą atnaujinimo metu.

## Kodėl DevOps

DevOps padeda komandai greičiau reaguoti į vartotojų poreikius ir išvengti ilgų, stresą keliančių rankinio diegimo procesų. 
Dėl glaudesnio bendradarbiavimo ir automatizacijos sumažėja klaidų skaičius, o iškilusias problemas galima išspręsti žymiai 
operatyviau.

## Git

Komanda `git branch -d` (mažąja raide) saugiai ištrina šaką tik tada, kai visi jos pakeitimai jau yra sujungti su pagrindine 
šaka. Komanda `git branch -D` (didžiąja raide) ištrina šaką priverstinai, net jei joje liko nesujungtų pakeitimų.

**Kas yra merge commit?** Tai specialus sujungimo taškas (commit), turintis du tėvinius commit'us, kurį Git sukuria tuomet, 
kai dvi šakos išsiskyrė ir abiejose buvo atlikti nauji pakeitimai, todėl jas reikia apjungti į vieną bendrą istoriją.
