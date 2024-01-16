# Házi feladat információk

A tárgyból házi feladat készítése nem kötelező, de ajánlott. 
Házi feladat készítésével a vizsgát kiváltva megajánlott 4-es vagy 5-ös szerezhető. 
A házi feladatra maximum 40 pont kapható, amiből a megajánlott jegyhez minimum 25 pontot el kell érni. 
Akinek nem sikerül ezt a pontszámot megszerezni, az a vizsgára vihet maximum 20 pontot.

## Követelmények

-	Legalább 5 technológia használata pl.:
	-	UI (Jetpack Compose + MVVM),
	-	komplexebb lista (Jetpack Compose),
	-	perzisztencia, 
	-	hálózat, 
	-	Firebase,
	-	pozíciómeghatározás, 
	-	animáció, 
	-	stílusok/témák (komplex, teljes alkalmazásra kiterjedő kinézet),
	-	Service, 
	-	BroadcastReceiver, 
	-	Content Provider, 
	-	stb.
-	Az alkalmazás felhasználói felületéhez Jetpack Compose-t kell használni.
-	Kotlin nyelven kell készülnie.
-	Önálló alkalmazás legalább 3-4 képernyővel/nézettel.
-	Bármilyen külső könyvtár használható a fejlesztéshez, hogy még látványosabb alkalmazások készüljenek:
	-	[https://github.com/wasabeef/awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)
	-	[https://github.com/nisrulz/android-tips-tricks](https://github.com/nisrulz/android-tips-tricks)
	-	[https://foso.github.io/Jetpack-Compose-Playground](https://foso.github.io/Jetpack-Compose-Playground)
	-	[https://www.jetpackcompose.app/compose-catalog](https://www.jetpackcompose.app/compose-catalog)


!!!tip "Néhány példa alkalmazás"
	-	Kiadás/bevétel nyomkövető figyelmeztető funkcióval és grafikonokkal
	-	Turisztikai látványosságokat gyűjtő alkalmazás
	-	Raktár kezelő alkalmazás
	-	Számla kezelő megoldás
	-	Recept kezelő alkalmazás
	-	Napló készítő alkalmazás fényképekkel
	-	Sport tracker alkalmazás
	-	Készülék esemény naplózó alkalmazás
	-	Apróhirdetés alkalmazás
	-	Találkozó szervező alkalmazás
	-	Sportfogadó megoldás
	-	Szaki kereső alkalmazás
	-	Játék alkalmazás, pl. aknakereső, shooter, stb.
	-	Valamilyen REST API-t használó alkalmazás, például valuta váltás, tőzsdei infók, stb:
		-	[https://github.com/toddmotto/public-apis](https://github.com/toddmotto/public-apis)
		-	[https://github.com/Kikobeats/awesome-api](https://github.com/Kikobeats/awesome-api)
		-	[https://github.com/abhishekbanthia/Public-APIs](https://github.com/abhishekbanthia/Public-APIs)
	-	A házi feladat használhat felhő megoldást is, pl. Firebase, Amazon, stb.

## Beadás módja

A házi feladat beadásának platformja a laborokhoz hasonlóan a Github Classroom. A meghívó a Moodle oldalon található.

!!!danger "neptun.txt"
	Az első és legfontosabb, hogy az eddigiekhez hasonlóan töltsd ki a neptun.txt fájlt, hogy a rendszer azonosítani tudjon.

### Specifikáció

A specifikáció beadás határideje a **9. hét vége (2023. november 5. 23:59)**.
A specifikáció elkészítése közben a "**spec**" branchen dolgozz. Erre az ágra akárhány kommitot tehetsz.
Sablont a README.md fájl tartalmaz, azt kell kiegészíteni, és feltölteni a repóba a megadott határidőig.
A beadás akkor teljes, ha a "spec" branch-en megtalálható a README.md fájlban a specifikáció. A beadást egy pull request jelzi, amely pull requestet a laborvezetődhöz kell rendelned.
A specifikáció elkészítése előfeltétele a házi feladat elfogadásának.

### Házi feladat

A házi feladat beadás határideje a **13. hét vége (2023. december 3. 23:59)**.
A házi feladat elkészítése közben a "**hf**" branchen dolgozz. Erre az ágra akárhány kommitot tehetsz. 
A projektet mindenképpen ebbe a repository-ba hozd létre, a fejlesztést végig itt végezd.
A beadás akkor teljes, ha a "hf" branch-en megtalálható a projekted teljes forráskódja. A beadást egy pull request jelzi, amely pull requestet a laborvezetődhöz kell rendelned.
A házi feladathoz mindenképpen tartozik **házi feladat védés** is. Ennek ideje a beadást követően 14. heti laboron van.

### Házi feladat pótlás - fizetésköteles!

A pótbeadás határideje a **pótlási héten, laborvezetővel egyeztetve**.
A házi feladat pótlása közben a "**pothf**" branchen dolgozz. Erre az ágra akárhány kommitot tehetsz. 
A beadás akkor teljes, ha a "pothf" branch-en megtalálható a projekted teljes forráskódja. A beadást egy pull request jelzi, amely pull requestet a laborvezetődhöz kell rendelned.
A házi feladat pótlásához mindenképpen tartozik **pót házi feladat védés** is. Ennek módjáról és idejéről egyeztess a laborvezetőddel.

## Dokumentáció

A házi feladatot a specifikáción túl dokumentálni is kell a README.md fájlba. (A specifikáció után.) Ebben röviden ismertetni kell az elkészült alkalmazás funkcionalitását és az érdekesebb megoldásokat.

!!!tip "Androidalapú szoftverfejlesztés + Mobil- és webes szoftverek közös házi feladat"
	Ha valaki mind a két tárgyat hallgatja a félévben, van lehetőség közös házi feladat írására, DE:
	- Ezt mindenképpen egyeztetni kell mindkét laborvezetővel.
	- Ugyanaz a házi csak úgy adható le mindkét tárgyon, ha a nehezebb követelményeket (vagyis az Androidalapú szoftverfejlesztését) felülteljesíti. Tehát az Androidalapú szoftverfejlesztés követelményei szerint nem 5, hanem 6-7 technológiát kell használni. Ennek mennyiségéről és a feladat komplexitásáról a laborvezetők döntenek.