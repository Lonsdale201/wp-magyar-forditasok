# WordPress bővítmény fordítások
WordPress bővítmények - magyar közösségi fordítások


### Bevezető

Ebben a Github repóban gyűjtjük azokat a magyar nyelvű fordításokat, melyek azon bővítményekhez készültek, amik nincsenek benne a hivatalos WordPress repóban, tehát nem ingyenes bővítmények.
Minden fordításnál találsz egy **cred-olvasdel.txt** fájl-t. Itt tudsz információt szerezni a fordítóról, elérhetőségéről, és maga a fordított bővítményről. Vannak szabályok amiket fontos betartania azoknak, akik csatlakoznak a fordítói közösséghez, és fordításokat készítenek / osztanak meg.

A fordításokat több helyről is el lehet érni a jövőben. Az egyik központi elérhetősége a Github lesz.

### Közösségi információ

Kezdeném azzal, hogy mi **nem vagyunk** a hivatalos WordPress fordító tagjai. Ez egy általam (Soczó Kristóf), indított közösségi kezdeményezés, melynek célja, hogy magyar nyelvű fordításokkal járuljunk hozzá a WordPress magyarországi közösségéhez. A közösségi fordítók ettől függetlenül kötelezettséggel rendelkeznek a saját munkájuk iránt.


### Hogyan lehet csatlakozni a közösséghez?

Ez egy nyitott "projekt", azaz szabadon lehet hozzá csatlakozni, mint fordító. A fordítónak kötelezettsége van saját munkája iránt, valamint szabályok melyeket bekell tartani.
Nincsenek előfeltételek, és nem szükséges az angol nyelvvizsga sem. Mindenkit szivesen látunk, aki veszi a fáradstágot, és beszáll a fordításokba. 

> Fontos! Azon bővítmények, amik megtalálhatóak a WordPress hivatalos bővítmény tárában, ide nem kerülnek fel. Ha ingyenes plugin-t fordítasz azt tedd a hivatalos úton / módon!


### Szabályok a fordítók számára

- Kerüld a Google Fordítót. Szabadon lehet használni segédeszközöket, de ilyenkor válasszunk okosan. Használj DeepL-t vagy akár maga a ChatGPT.
- Ne fordíts úgy, hogy nem ismered a bővítményt. Aranyszabály!
- Ne támaszkodj az AI-ra, vagy komplett DeepL fordításra 100%-ban. Ez alatt azt értem, hogy ne add be a rendszernek a teljes anyagot fordításra, mert tízszer annyi idő lesz kijavítani, mint manuálisan megcsinálni.
- Kövesd a **hivatalos fordítók** általi WordPress magyar megnevezéseket / szabványokat. Ha a Trash Lomtár, akkor nem fordítjuk kukának.
- Kövess populárisabb bővítményekben megtalálható magyar fordításokat alapoknak. Például az **Elementor** stilisztikai fordításai már köztudatban vannak, és elfogadottak, ezért jobb ezen sémákat követni.
- Egyeztess más fordítókkal, vagy ellenőrizd át a munkájukat ha olyan bővítmény magyarosítását végzed ahol több plugin ütközés is megtalálható. Ha nem vagy magadban biztos egyeztess velünk!
- Döntsd el, hogy magázol vagy tegezel. Ha magázva kezded a fordítást tartsd magad ahhoz.
- Felelősséggel kell lenned a fordításod iránt. Csak úgy tölthetsz fel fordítást, ha csatolsz mellé **cred-olvasdel.txt** ahol megadod az alapvető információkat, mind magadról mind a bővítményről.
- 50% alatti fordítást nem töltünk fel, csak abban az esetben ha komplexebb a fordítás és kísérleti jellegű kiadást kívánsz kiadni. Ezt fel kell tüntetni a **cred-olvasdel.txt** fájlban.
- Ügyelj a helyesírásra.
- Eltérő fordítást csak abban az esetben alkalmazz, ha az adott szöveg nem egyértelmű, vagy nincs rá megfelelő magyar kifejzés. Ezt csak akkor javasoljuk, ha a fordítandó bővítményt alaposan ismered.
- Ne fordíts le bizonyos szakszavakat. Shortcode, widegts stb.. Egyes esetekben vannak olyan stringek amik nem igénylik hogy keressünk magyar megfelelőt, mert magától értendő.
- Elementor, és egyéb page builder kiegészítő fordításoknál a widget neveit nem feltétlen célszerű magyarosítani. Ne akarj a CTA rövidítésnek magyar megfelelőt írni, mert felesleges.
- Ha túl sok jelentést kapsz a fordításodra levesszük. Ha kijavítást követően ismét túl sok report érkezik, levesszük, és megszüntetjük a jogosultságodat arra, hogy fordításokat küldj be.
- Ha hibát jeleznek a fordításodban a legjobb tudásod szerint köteles vagy azt javítani. Ha a jövőben nem lesz rá kapacitásod, egyeztess más fordítóval, hogy ha lehetséges vegye át a fordításod.
- Csatlakozást követően figyeld aktívan ennek a repónak az **Issue** szekcióját, hogy minél hamarabb értesülj az esetleges hibákról.
- Ne használd a cred-olvasdel.txt arra, hogy egyéb szolgáltatásaidat promózd. Csak a szükséges adatokat add meg, és ha indokolt kapcsolódó kiegészítést hozzá.

### Hogyan töltsd ki fordítóként a cred-olvasdel.txt fájlt

Kövesd a meglévő **cred-olvasdel** fájlokat referenciaként. Ebbe a txtben kell tárolnod néhány kapcsolódó információt a fordításról. A bővítmény neve, verziószáma (amihez készítetted a fordítást) bővítmény link, utolsó mdosítás dátuma, továbbá elérhetőség / a neved. Ezen felül további egyéb extra információt is megadhatsz ha szükségesnek érzed.


### Szabály a felhasználók számára

- Tartsd tiszteletben a fordítók munkáját. Ne mond, hogy te készítetted, ha tudod, hogy nem te voltál.
- Ne zaklasd a fordítót. Tartsd tiszteletben a **cred-olvasdel.txt-ben** leírtakat.
- Ha hibát találtál a legjobb ha itt Githubon az ISSUE részlegen jelented.



## Hogyan tudok fordítást "telepíteni"?

A fordítási fájlokat fel kell töltened. Bővítmény használata esetében a **Loco Translate** segítségével néhány kattintással megoldható. Ha nem kívánsz plugint használni hozzá, akkor manuálisan kell telepítened.
FTP, SSH vagy egyéb módon (pl cpanel fájl kezelő) el kell tudnod érni a **wp-content** mappádat. Itt ha még nincs, hozz létre egy **languages** nevű mappát, azon belül pedig egy **plugins** mappát. Ezután nincs más dolgod mint a Plugins mappába feltölteni a megfelelő fájlokat. *(wp-content/languages/plugins)* A fordítások minden esetben úgy vannak elnevezve, hogy azok a bővítmény, és a WordPress számára azonosítható legyen, így ezeket a fájlokat nem szabad átnevezdned letöltést követően, és akkor sem, amikor felteszed őket a szerverre!

Nagyon ritka esetben a nyelv fájlokat a bővítmény megköveleti, hogy a saját mappájába telepítsd egy **languages** mappába. Ám ez nagyon kis százalékban szükséges.

Loco Translate bővítmény esetében mennyj a Loco Translate / Plugins menüpontba. A listában keresd meg azt a bővítményt amihez fel kívánod tölteni a fordítást, majd kattints rá. A következő ablakban kattints a PO Feltöltése gombra. A **Válasszon helyet** alatt a rádió gomboknál válaszd ki az **egyedi-t**, majd a feltölteni kívánt fájl-t, és kattints a Feltöltés gombra.

![image](https://github.com/Lonsdale201/wp-magyar-forditasok/assets/23199033/8908d090-c9d2-46bf-96c9-9d6cdeefa82a)

## Hogyan tudok fordítást feltölteni / beküldeni?

Ha jártas vagy a Github használatában, akkor forkold a repómat magadhoz, majd pullold a feltöltésedet. 24 órán belül elfogadásra kerül. / feltétel saját github fiók
Ha a Github világa ismeretlen számodra, akkor a fordításodat elküldheted nekem Emailben, vagy Discordon. Az elérhetősegeket lentebb fogod látni.
A repómhoz kollaborációs lehetőség is van, de ehhez javasolt némi github ismeret a részedről. (nem akadály, ha nincs, de szeretnél csatlakozni, segítek) / feltétel saját github fiók

*Ha a háttérben maradnál, de szeretnél fordításokat adni arra is van lehetőség, ilyenkor egyéni módon beszéljük át a menetét.*

### Hol tudok információt szerezni a fordítások frissítéséről, vagy új fordításokról? 

A legjobb módja ennek, ha csatlakozol Discord közösségünkhöz. Github tracker, és fordítási társalgó csatornákat biztosítunk, ha pedig új fordítást töltünk fel, egyből pingelünk.

Discord szerver elérhetőség: https://discord.com/invite/hellowp
