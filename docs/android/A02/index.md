# Android 2 - Architektúra és környezet

# FRISSÍTÉS ALATT - NEM VÉGLEGES VERZIÓ

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.04.14. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Célkitűzés

Jelen labor célja, hogy támogassa az előző labor során elkészült specifikáció alapján az alkalmazás fejlesztésének elkezdését. Cél, hogy az alkalmazás alapvető architektúráját megtervezzük és implementáljuk, úgy, hogy ez a fejlesztés során előjövő igényeket a lehető legjobban kielégítse, és a lehető legkevesebbet változtassunk az alkalmazás alapvető architektúráján. 

Az architektúrára épülve elkezdjük a skeletonnak fejlesztését. A váz fejlesztése során a megfelelő nézetek, és hozzájuk kapcsolódó viewmodelek, repository-k elkészítése a cél, de még tényleges üzleti logika és valós felületi elemek (UI) nélkül. Cél az alkalmazás rétegei közötti interakciók (mit tud a viewmodel elvégezni, mit tud megjeleníteni a view) megfelelő definiálása. 
Ez a gyakorlatban azt jelenti, hogy minden főbb osztályt létre kell hozni, de még az osztályok lehetnek "üresek".

További olvasnivalók a témában:
https://developer.android.com/topic/architecture/recommendations  
Példaalkalmazások követendő architektúrával:  
https://github.com/skydoves/DisneyCompose

??? info "Skeleton példa"
        - data
            - dao
                - ...
            - datasource
                - ...
            - entities
                - ...
            - TodoDatabase.kt
        - domain
            - ...
        - feature
            - todo_list
                - TodoListScreen.kt
                - TodoListViewModel.kt
            - todo_details
                - TodoDetailsScreen.kt
                - TodoDetailsViewModel.kt
            - todo_create
                - TodoCreateScreen.kt
                - TodoCreateViewModel.kt
        - navigation
            - NavGraph.kt
            - Screen.kt
        - network
            - ...
        - ui
            - common   
                - ... (több helyen használt Composable-k)
            - model
                - ... (UI model osztályok)
            - theme 
                - ... (generált téma Kotlin fájlok)
            - util
                - ... (util osztályok)
        - MainActivity.kt
        - MainApplication.kt

További cél az alkalmazás fejlesztéséhez használt **Git verziókezelő** és **Continuous Integration rendszer (Github Actions)** konfigurálása és használata.   

A fejlesztés során a Git Flow-t szükséges használni:  
https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

??? info "Github Actions példa"

    Build folyamat:

    ```yaml
    name: Build
    on:
        pull_request:
        push:
            branches:
                - main
    jobs:
        build:
            runs-on: ubuntu-latest
            steps:
            - name: Checkout the code
              uses: actions/checkout@v2
            - name: Build the app
              run: ./gradlew build
    ```

A fejlesztés kizárólag Kotlin nyelven történhet, Jetpack Compose keretrendszer használatával.


## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz a Git Flow szerint.

2. A labor végén egy release branchről nyiss egy PR-t a main-re.

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Android Studio
- Git

A Mobilszoftver Rendszerek tárgy előadásainak folyamatos követése 

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    **Elkészült alkalmazás skeleton és architektúra (max. 50 pont):**  
    - Minden nézetre a megfelelő architektúra elemek és repository-k, MVVM és Hilt használatát feltételezve  

    **Git verziókezelő használata, Git-flow kialakítása (max. 25 pont):**  
    - main, dev, feature branchek legalább 5 committal és egy merge-el

    **Github Actions konfiguráció és futtatás (max. 25 pont):**  
    - legalább 1 sikeres build 