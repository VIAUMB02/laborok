# Android 2 - Architektúra és környezet

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.03.24. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Célkitűzés

Jelen labor célja, hogy támogassa az előző labor során elkészült specifikáció alapján az alkalmazás fejlesztésének elkezdését. Cél, hogy az alkalmazás alapvető architektúráját megtervezzük és implementáljuk, úgy, hogy ez a fejlesztés során előjövő igényeket a lehető legjobban kielégítse, és a lehető legkevesebbet változtassunk az alkalmazás alapvető architektúráján. 

Az architektúrára épülve elkezdjük a skeletonnak fejlesztését. A váz fejlesztése során a megfelelő nézetek, és hozzájuk kapcsolódó viewmodelek, repository-k elkészítése a cél, de még tényleges üzleti logika és valós felületi elemek (UI) nélkül. Cél az alkalmazás rétegei közötti interakciók (mit tud a viewmodel elvégezni, mit tud megjeleníteni a view) megfelelő definiálása. 
Ez a gyakorlatban azt jelenti, hogy minden főbb osztályt létre kell hozni, de még az osztályok lehetnek "üresek".

További olvasnivalók a témában:
https://developer.android.com/topic/architecture/recommendations


További cél az alkalmazás fejlesztéséhez használt Git verziókezelő és Continuous Integration rendszer (Github Actions) konfigurálása és használata. 

A fejlesztés kizárólag Kotlin nyelven történhet, Jetpack Compose keretrendszer használatával.


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

    **Elkészült alkalmazás skeleton és architektúra (max. 50 pont):**  
    - Minden nézetre a megfelelő architektúra elemek és repository-k, MVVM, Hilt  

    **Git verziókezelő használata, Git-flow kialakítása (max. 25 pont):**  
    - main, dev, feature branchek legalább 5 committal és egy merge-el

    **Github Actions konfiguráció és futtatás (max. 25 pont):**  
    - legalább 1 sikeres build 