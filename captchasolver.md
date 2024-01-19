# Captcha solver

A Captcha Solver egy kiegészítő az NVDA képernyőolvasóhoz, amely kényelmes módot biztosít bármely captcha felismeréséhez a rucaptcha.com szolgáltatás használatával.

## Beállítás és használat

A bővítmény telepítése után kövesd az alábbi lépéseket:
* Regisztrálj a rucaptcha.com weboldalon, és töltsd fel egyenleged bármilyen módon.
* Másold ki a 32 számjegyű API-kulcsot [Erről az oldalról](https://rucaptcha.com/setting/)
* Nyisd meg az NVDA menü → Eszközök → Captcha Solver → Beállítások menüpontot, azt követően az "API kulcs" mezőbe illeszd be az előző lépésben kapott kulcsot, majd kattints az OK gombra.
* Nyisd meg az NVDA menü → Beállítások → Beviteli parancsok, és a Captcha Solver-hez tartozó menüben rendelj hozzá egy tetszőleges billentyűparancsot a Felismerési folyamat elkezdéséhez. Továbbá ajánlott az egyenleg lekéréséhez is egy billentyűkombinációt rendelni.
Ezután az NVDA elemnavigációja segítségével pozícionáld a kurzort a captcha képet tartalmazó objektumra (általában ez egy grafikus elem). Indítsd el a felismerési folyamatot az előzőleg beállított kombinációval. A captcha kép sikeres elküldéséről szóló üzenet után 10-15 másodpercet kell várni az eredményre, és ha minden jól megy, akkor az NVDA tájékoztat erről, majd a felismert szöveg megjelenik a vágólapon. A bővítmény a klasszikus captchák felismerésére készült, a képen egysoros karakterekkel. A cirill betűs captchákat is gond nélkül felismeri.

## Előfizetés

Alapból a weboldal a megnyitást követően elképzelhető, hogy oroszul jelenik meg, erre sajnos nincs ráhatásom. Annak érdekében, hogy angolul, nemzetközi úton lehessen előfizetni, a következőket kell tenni:
* Keresd meg a "Looking for international version of our service? Go to" szöveget. Ez az oldal alján található. Közvetlenül utána egy linket látsz, a biztonság kedvéért [ezt a linket](https://2captcha.com/enterpage)
* Ezután már angol nyelven jelenik meg a felület. Aki valamilyen úton-módon befejezte a regisztrációs folyamatot az orosz verzió használatával, nem kell új felhasználót készítenie. Az API ugyanaz, ezért a nemzetközi oldalról lekérhető API kulcs is tökéletes a kiegészítő használatához.
* Amint beléptél, már látod is a feltöltési lehetőséget. Nekünk az első opcióra lesz szükségünk. Innentől kezdve egy már talán ismerősebb, banki rendszer fogad minket, angol nyelven.
További segítségért bátran fordulhat hozzám bárki a főoldalon megadott elérhetőségek valamelyikén.

## Letöltés

A kiegészítő elérhető a [projekt hivatalos oldalán](https://github.com/kvark128/CaptchaSolver)
illetve újabb NVDA verziók esetében az NVDA Addon store-ban.
