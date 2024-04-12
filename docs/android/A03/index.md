# Android 3 - Hálózat és adatbázis

# FRISSÍTÉS ALATT - NEM VÉGLEGES VERZIÓ

!!!danger "HATÁRIDŐ"
	A labor beadásának határideje (Githubon Pull Request nyitás + assign): **2024.04.28. 23:59**  
    Labvez Github userek: AttilaHideg (Hideg Attila), kpomazi (Pomázi Krisztián), siktdavid (Sik Dávid)

## Célkitűzés

A labor elején a hálózati kommunikáció megtervezése (kapcsolódó API hívások definiálása) a feladat. 

Ezt követően, erre épülve, a cél a hálózati hívások implementálása (opcionálisan kódgenerátor felhasználásával), ezek megfelelő bekötése az repositorykhoz, preferáltan Retrofit kliens segítségével.

A hálózati hívások elkészítése után a következő feladat az ORM réteg implementálása, erre a Room a preferált technológia.

Az elvégzett munkát dokumentálni is szükséges a repo Readmejében.

## Előkészületek

A feladatok megoldása során ne felejtsd el követni a [feladat beadás folyamatát](../../tudnivalok/github/GitHub.md).

### Git repository használata

1. Az első labor során létrehozott repository-ban dolgozz.

2. A labor végén egy release branchről nyiss egy PR-t a main-re.

## Előfeltételek 

A labor elvégzéséhez szükséges eszközök: 

- Android Studio

Amit érdemes átnézni:  

- Mobilszoftver Rendszerek tantárgy előadásainak kapcsolódó anyaga
- Room dokumentáció  
- Retrofit dokumentáció  

!!!example "ELVÁRT EREDMÉNYEK - BEADANDÓ" 

    **Hálózati hívások API leírása (.yaml leírás, max. 20 pont)**  

    **Hálózati réteg elkészítése (max. 40 pont)**:  
    - Model, API Service és Retrofit osztályok elkészítése/inicializációja  
    - Repositoryk létrehozása, hálózati hívások bekötése  
    - DI keretrendszer használata fenti lépések elvégzéséhez  
    - Dokumentáció: Melyik osztályokat hoztad létre és mik a felelősségeik?  

    **ORM adatréteg elkészítése (max. 40 pont)**:  
    - Entity, DAO, Database osztályok elkészítése/inicializációja  
    - Repositoryk létrehozása, adatműveletek bekötése  
    - DI keretrendszer használata fenti lépések elvégzéséhez  
    - Dokumentáció: Melyik osztályokat hoztad létre és mik a felelősségeik?  