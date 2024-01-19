# Captcha solver

A Captcha Solver egy kiegészítő az NVDA képernyőolvasóhoz, amely kényelmes módot biztosít bármely captcha felismeréséhez a rucaptcha.com szolgáltatás használatával.

## Beállítás és használat

A bővítmény telepítése után kövesd az alábbi lépéseket:
* Regisztrálj a rucaptcha.com weboldalon, és töltsd fel egyenleged bármilyen módon.
* Másold ki a 32 számjegyű API-kulcsot [Erről az oldalról](https://rucaptcha.com/setting/)
* Nyisd meg az NVDA menü → Eszközök → Captcha Solver → Beállítások menüpontot, azt követően az "API kulcs" mezőbe illeszd be az előző lépésben kapott kulcsot, majd kattints az OK gombra.
* Nyisd meg az NVDA menü → Beállítások → Beviteli parancsok, és a Captcha Solver-hez tartozó menüben rendelj hozzá egy tetszőleges billentyűparancsot a Felismerési folyamat elkezdéséhez. Továbbá ajánlott az egyenleg lekéréséhez is egy billentyűkombinációt rendelni.
Ezután az NVDA elemnavigációja segítségével pozícionáld a kurzort a captcha képet tartalmazó objektumra (általában ez egy grafikus elem). Indítsd el a felismerési folyamatot az előzőleg beállított kombinációval. A captcha kép sikeres elküldéséről szóló üzenet után 10-15 másodpercet kell várni az eredményre, és ha minden jól megy, akkor az NVDA tájékoztat erről, majd a felismert szöveg megjelenik a vágólapon. A bővítmény a klasszikus captchák felismerésére készült, a képen egysoros karakterekkel. A cirill betűs captchákat is gond nélkül felismeri.

## Letöltés

A kiegészítő elérhető a [projekt hivatalos oldalán](https://github.com/kvark128/CaptchaSolver)
illetve újabb NVDA verziók esetében az NVDA Addon store-ban.
