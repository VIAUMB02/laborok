# Android 1 - Specifikáció

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.03.10. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Bevezetés

A következő öt laboratórium célja hogy végig vezesse a hallgatót egy teljes mobil szoftver tervezés és megvalósítás lépésein. Az érintett részfeladatok a következők lesznek: 

- Specifikáció, actorok, use case-k, user story-k, képernyőtervek készítése 
- Architektúra kialakítása, környezet összeállítása (CI/CD, Git), alkalmazás skeleton készítése 
- Hálózati kommunikáció tervezése és implementálása. Adatmodell és ORM réteg implementálása.  
- Felület implementáció, logikai implementáció, alkalmazás funkcionális befejezése. 
- Analitika (Google Analytics, Crashlytics) hozzáadása, unit tesztek és UI tesztek elkészítése. 

A labor során a jelölt saját ötlet alapján fejleszthet alkalmazást, de a laborvezető is fel tud ajánlani néhány ötletet. Az ötletnek nem kell (nem szabad) túl bonyolultnak lennie, a cél ugyanis az egyes technológiák kipróbálása. 

Az ötlettel szemben támasztott követelmények: 

- Legalább 3 képernyős bonyolultság. Például egy lista/rács nézettel, egy részletes nézet, egy pedig egy logikát nem tartalmazó „About” nézet, 
- szerver oldali adaforrás feltételezése (REST API tervezéshez), minimálisan GET művelethez, 
- offline működés támogatása lokális adatbázis segítségével. 

Érdemes nyílt API-kat használni, aminek segítségével lehet elemeket listázni. Példákat talál a https://github.com/public-apis/public-apis oldalon.   


## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository létrehozása és letöltése

1. Moodle-ben keresd meg a laborhoz tartozó meghívó URL-jét és annak segítségével hozd létre a saját repository-dat.

2. Várd meg, míg elkészül a repository, majd checkout-old ki.

    !!! tip ""
        Egyetemi laborokban, ha a checkout során nem kér a rendszer felhasználónevet és jelszót, és nem sikerül a checkout, akkor valószínűleg a gépen korábban megjegyzett felhasználónévvel próbálkozott a rendszer. Először töröld ki a mentett belépési adatokat (lásd [itt](../../tudnivalok/github/GitHub-credentials.md)), és próbáld újra.

3. Hozz létre egy új ágat `labor01` néven, és ezen az ágon dolgozz.

4. A `neptun.txt` fájlba írd bele a Neptun kódodat. A fájlban semmi más ne szerepeljen, csak egyetlen sorban a Neptun kód 6 karaktere.

## Célkitűzés

Jelen labor célja, hogy támogassa a megvalósítandó alkalmazás specifikálását, a részfeladatok egyértelmű azonosítását, és az elvárt funkcionalitás megfelelő definiálását, valamint, hogy megfelelő alapot nyújtson a további laborokhoz, különösen az architektúra tervezés feladathoz.  

Elsőként az alkalmazás elvárt funkcionalitását fogalmazzuk meg, azonosítsuk az alkalmazás actorait, use-case-eit és user- story-jait, majd ezeket megfelelő részéletességgel specifikáljuk is. Használjunk use-case diagramokat!  

Majd az alkalmazás képernyőit azonosítsuk, és elkészítjük a hozzájuk tartozó képernyőterveket. 

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Tetszőleges képernyőtervező szoftver (pl. Justinmind, Figma, stb.). 
- Tetszőleges UML Diagramrajzoló szoftver (pl. Visio, Lucid Charts, Draw.io, stb.) 

A Mobilszoftver Rendszerek tárgy előadásainak folyamatos követése 

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    Szöveges specifikáció az actorok, use-case-ek és user-story-k leírásával (.pdf, max. 50 pont) 

    Képernyőtervek (.pdf, max. 50 pont) 