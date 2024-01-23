# Android 5 - Tesztek és analitika

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.??.??. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Célkitűzés

Jelen labor célja, hogy az előző laborok során elkészült alkalmazást ellátsuk, mind Google Analytics, mind Crashlytics (Fabric) analitikai és crash report megoldásokkal. 

Cél, továbbá az előző labor végén elkészült hálózati és adatbázis réteget tesztelését elősegítő mock hálózati réteg elkészítése, majd a hálózati hívások és adatbázis réteg Unit tesztelése.  

Tekintettel a laborok során kapott visszajelzésekre, korrekciókra, valamint az eltérő komplexitású feladatokból fakadó fejlesztési időkre, a UI tesztelés feladata opcionális, viszont a feladatra kapott pontok plusz pontként számítanak.


## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz.

2. A labor végén a dev branchről nyiss egy PR-t a main-re.

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Android Studio
- Google Play Console 

A Mobilszoftver Rendszerek tárgy előadásainak folyamatos követése 

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    Google Analytics integráció (screenshot az eseményekről a kontrol panelen, max. 25 pont)  

    Crashlytics integráció (screenshot az összeomlásokról a kontrol panelen, max. 25 pont)

    Kapcsolódó Unit tesztek (lehetőleg minden funkcionalitást fedjen le, ne csak a hálózati hívásokat, mind sikeresen fusson le, max. 50 pont)    

    Espresso UI tesztek, lehetőleg a legtöbb funkcionalitást lefedve (az összes teszt fusson le, max. +50 pont)  