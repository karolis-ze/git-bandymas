# Kas yra DevOps

DevOps yra būdas, kaip programuotojai ir sistemų administratoriai dirba kartu kaip viena komanda. Pagrindinis tikslas – 
automatizuoti visą procesą, kad naujas kodas kuo greičiau ir saugiau pasiektų vartotoją. Komandos nariai kartu prižiūri 
projektą nuo pat sukūrimo iki veikimo serveryje. Dėl to atnaujinimai išleidžiami dažniau, o klaidos ištaisomos greičiau.

## Kur gali lūžti

1. **Testavimo metu:** Jei testai nepastebi klaidos, sugedęs kodas patenka tiesiai vartotojams.
2. **Įkeliant į serverį:** Jei serveryje trūksta kokių nors nustatymų ar programų, svetainė po atnaujinimo gali tiesiog 
nebeveikti.

## Kodėl DevOps

DevOps padeda komandai greičiau išleisti naujoves ir išvengti rankinio darbo klaidų. Be to, sugedus sistemai, visi kartu 
problemą išsprendžia daug greičiau.

## Git

Komanda `git branch -d` (mažąja raide) saugiai ištrina šaką tik tada, kai jos pakeitimai jau perkelti į pagrindinę šaką. 
Komanda `git branch -D` (didžiąja raide) ištrina šaką priverstinai, net jei joje liko neperkeltų pakeitimų.

**Kas yra merge commit?** Tai specialus įrašas istorijoje, kurį Git sukuria sujungdamas dvi atskiras šakas, kai abiejose buvo 
padaryta naujų pakeitimų.
