# Android 2 - Architektúra és környezet

## Célkitűzés

Jelen labor célja, hogy támogassa az előző labor során elkészült specifikáció alapján az alkalmazás fejlesztésének elkezdését. Cél, hogy az alkalmazás alapvető architektúráját megtervezzük és implementáljuk, úgy, hogy ez a fejlesztés során előjövő igényeket a lehető legjobban kielégítse, és a lehető legkevesebbet változtassunk az alkalmazás alapvető architektúráján. 

Az architektúrára épülve elkezdjük a skeletonnak fejlesztését. A váz fejlesztése során a megfelelő nézetek, és hozzájuk kapcsolódó viewmodelek, repository-k elkészítése a cél, de még tényleges üzleti logika és valós felületi elemek (UI) nélkül. Cél az alkalmazás rétegei közötti interakciók (mit tud a viewmodel elvégezni, mit tud megjeleníteni a fragment) megfelelő definiálása. 

További cél az alkalmazás fejlesztéséhez használt Git verziókezelő és Continuous Integration rendszer (Github Actions) konfigurálása és használata. 

A fejlesztés kizárólag Kotlin nyelven történhet. 


## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz.

2. A labor végén a dev branchről nyiss egy PR-t a main-re.

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Android Studio
- Git

A Mobilszoftver Rendszerek tárgy előadásainak folyamatos követése 

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    Elkészült alkalmazás skeleton és architektúra (minden nézetre a megfelelő architektúra elemek és repository-k, MVVM, Hilt, projekt .zip, max. 50 pont)  

    Git verziókezelő használata, Git-flow kialakítása, main, dev, feature branchek legalább 5 commital és egy merge-el. (pdf-ben a log screenshot és rövid leírás, Github link, max. 25 pont)  

    Github Actions konfiguráció és futtatás (legalább 1 sikeres build, screenshot, .pdf, max. 25 pont) 