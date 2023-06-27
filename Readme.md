# Git verziókezelés (Markdown segédlet)

- helyi REPO inicializálása:
    > git init
- a helyi REPO ellenőrzése
    >git status
- előkészítése a verzió kezelésre egy ideiglenes tárolásra, felteszük a szÍnpadra (Stage), indekszeltük:
    >git add .(mindent állományra vonatkozik)
- a verzió létrehozása
    .git commit -m "FirstCommit"
     . git status
- Távoli REPO létrehozása (a github oldalon):
Összekapcsoljuk a távoli REPOT a helyivel:
    >tokken@git remote add origin https://github.com/MalyiZsuzsanna/TextRepo.git (legelső alkalommal)
- Melyik ágba teszük (Branch) az ágat a távoli Repo-ban:
    >git push -u master (legelső alkalommal kell ezt)
    >git push (további alkalomkor)
- Token használata (ezzel azonosítjuk magunkat a GitHub-on) (másoljuk a tokenünkből és a commanderrben jobb egérgomb és enter )

## Publikálás

- A publikálandó file nev index.html
- a settings > Pages > Branch: nonból kiválasztottuk a master > save
- Actionban láthatjuk a publikálási folyamatot
- minden commit után automatikusan újra "deploy" az oldallal.