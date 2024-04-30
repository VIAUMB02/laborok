# Android 5 - Tesztek és analitika

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.05.26. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Célkitűzés

Jelen labor célja, hogy az előző laborok során elkészült alkalmazást ellásuk Google Analytics és Crashlytics analitikai és crash report megoldásokkal, a Firebase BaaS szolgáltatásait használva.

Az analitika pontszám megszerzéséhez szükséges legalább 1 saját analitikai esemény definiálása és erről képernyőkép készítése a Firebase konzolon. (Az analitikai események konzolon való megjelenésének átfutási ideje akár 1 nap is lehet, ezért érdemes a határidő előtt időben elkezdeni.)

A Crashlytics pontszám megszerzéséhez szükséges egy futás idejű összeomlás okozása, majd erről képernyőkép készítése a Firebase konzolon.

Cél továbbá az előző labor végén elkészült alkalmazás Unit tesztelése.  

A sikeres teszt futásokról screenshot készítése és a teszt stratégia dokumentálása szükséges.

Tekintettel a laborok során kapott visszajelzésekre, korrekciókra, valamint az eltérő komplexitású feladatokból fakadó fejlesztési időkre, a UI tesztelés feladata opcionális, viszont a feladatra kapott pontok plusz pontként számítanak.

## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz.

2. A labor végén egy release branchről nyiss egy PR-t a main-re.

## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz.

2. A labor végén egy release branchről nyiss egy PR-t a main-re.

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Android Studio  
- Firebase Console

Amit érdemes átnézni: 

- Mobilszoftver Rendszerek tantárgy előadásainak kapcsolódó anyaga  
- Firebase dokumentáciő (https://firebase.google.com/docs/android/setup#assistant)

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    **Google Analytics integráció (screenshot az eseményekről a kontrol panelen, max. 25 pont)**  

    **Crashlytics integráció (screenshot az összeomlásokról a kontrol panelen, max. 25 pont)**  

    **Kapcsolódó Unit tesztek (legalább 10 db., screenshot a sikeres futásokról, teszt stratégia dokumentációja Readme fájlban, max. 50 pont)**    

    **Espresso UI tesztek, lehetőleg a legtöbb funkcionalitást lefedve (legalább 5 db., screenshot a sikeres futásokról, teszt stratégia dokumentációja Readme fájlban, max. +50 pont)**  