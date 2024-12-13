Laddningstider
=======================

Denna sidan analyserar tre olika webbplatser och testar deras laddningstid och användbarhet.

Urval
-----------------------

Till denna analysen har jag valt ut tre helt olika webbplatser.

- [SVT Play](https://www.svtplay.se)

- [SAS](https://www.sas.se)

- [Booking.com](https://www.booking.com)

Metod
-----------------------

Till denna rapporten har jag använt Google PageSpeed Insights för att mäta varje sidans prestanda och i Firefox har jag 
använt devtools för att mäta sidans laddningstid. Jag har valt ut tre sidor för varje webbsida som jag ska mäta med Pagespeed. Min data sparar jag i  Google Kalkylark.


Resultat
-----------------------

<h2>SVT Play</h2>

![SVT Play](../assets/img/svtplay.png)

<div class="excel-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRlWpLgMhWmGlmUJgvPYRs7z2bOQ1hUyc9IM5a5HVuW0X3PMblbJIB8vb2qnRZvBeRUEaIXUzc8OqVB/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" title="Prestanda 1">>
    </iframe>
</div>

- [Startsidan](https://www.sas.se)

- [Programsidan](https://www.svtplay.se/program)

- [Kanalsidan](https://www.svtplay.se/kanaler)

SVT Play får inte godkänt av PageSpeed Insights på mobil men får godkänd på desktop.

SVT Plays hemsida får bättre poäng på desktop än på mobilen. Poängen på desktop ligger mellan 62 till 89 medan på mobil ligger den runt 60. För att förbättra prestandan kan SVT Play minska JavaScript-exekversingstid och optimera bilder. De kan också minska oanvänd CSS och JavaScript, och för att förbättra serverns svarstid och användarupplevelse behehöver serverns svarstid och huvudtrådsarbete minskas.

<h2>SAS</h2>

![SAS](../assets/img/sas.png)

<div class="excel-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRlWpLgMhWmGlmUJgvPYRs7z2bOQ1hUyc9IM5a5HVuW0X3PMblbJIB8vb2qnRZvBeRUEaIXUzc8OqVB/pubhtml?gid=1915103166&amp;single=true&amp;widget=true&amp;headers=false" title="Prestanda 2">
    </iframe>
</div>

- [Startsidan](https://www.sas.se/)

- [Login-sidan](https://auth.flysas.com/u/login?state=hKFo2SBKeHZJbzYyQlRqY2dIRXVrRGFoZnk0bGpxT1JmSm1rcaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIG5JV3lnYWFBQ3dyRDhIVy1XcEYwLTVod2ZNRUEzWjdQo2NpZNkgZmNvN2doYml5N1lsaGhGaWZnOHAweWNjQm9JY3RKYko&ui_locales=sv)

- [Checkin-sidan](https://www.sas.se/checkin/)

SAS får godkänt av PageSpeed Insights både på mobil och desktop.

På SAS hemsidan får desktop lite bättre poäng än på mobil, dock får checkin-sidan på desktop mycket högre poäng jämfört med de andra sidorna både på desktop och mobil. SAS kan förbättra sin prestanda genom att JavaScript-exekveringstiden och huvudtrådsarbetet minskas, och bilderna optimeras. Oanvänd CSS och JavaScript borde reduceras och för att förbättra laddningstider och användarupplevelse borde påverkan från tredjepartsprogramvara minskas.

<h2>Booking.com</h2>

![Booking.com](../assets/img/booking.png)

<div class="excel-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRlWpLgMhWmGlmUJgvPYRs7z2bOQ1hUyc9IM5a5HVuW0X3PMblbJIB8vb2qnRZvBeRUEaIXUzc8OqVB/pubhtml?gid=634917972&amp;single=true&amp;widget=true&amp;headers=false" title="Prestanda 3">>
    </iframe>
</div>

- [Startsidan](https://www.booking.com/)

- [Login-sidan](https://account.booking.com/sign-in?op_token=EgVvYXV0aCL6AgoUdk8xS2Jsazd4WDl0VW4yY3BaTFMSCWF1dGhvcml6ZRo1aHR0cHM6Ly9zZWN1cmUuYm9va2luZy5jb20vbG9naW4uaHRtbD9vcD1vYXV0aF9yZXR1cm4qmQJVck1CRXRlQWJDc1BRS1pQMUNDaUlKOGR0c0Yxa0tkRzBNMnhrZHZfdktNZXA4a2c4N2JmTXBBMkxEMFpiS0tYYUtMQ0hRUW5kcEdBM3hqd2JMZGpNR1RzTllmUEJoR0ZJc2IxaTJXNlNKOV9DaHJoUTlyc1d5ZmtWQkR1d0JDT0J3TEdpV2MxNWpPS29lSzM0TE5rbFNRdXd6bEpsb0RFNFNrM0gyVnFYX2RwajlmNEljSlloXzF2RV9XUmNBN0Zubl9DRmJCamxhWFh6NUwwdXc4R3J5NXVUbnh6OWdGQkZUN0F1SGp2ZFdyUjNKVkJDWDA9KmV5SnBaQ0k2SW5SeVlYWmxiR3hsY2w5b1pXRmtaWElpZlE9PUIEY29kZSoyCI7IEjCQ2ZPUjbUnOgBCAFjE0I7EuTKSARB0cmF2ZWxsZXJfaGVhZGVymgEFaW5kZXg)

- [Boka flyg-sidan](https://www.booking.com/flights/index.en-us.html?adplat=www-index-web_shell_header-flight-missing_creative-Gb4r72eZQWGF5rT3YFetP&aid=304142&client_name=b-web-shell-bff&etStateBlob=EAUIuf7ZGc3s3EJq4eZMNwZ4YCCov-XwKRL1Fe5bGnpvKEL8Q-Q-J6-zVp15u5uFpIwquyhKpY5Q&distribution_id=Gb4r72eZQWGF5rT3YFetP)

Booking.com får inte godkänt av PageSpeed Insights på mobile eller desktop.

Booking.com får ganska dålig poäng på mobil där det ligger mellan 31 och 47. Desktop får bättre poäng som ligger på 70 och 81, dock får startsidan en väldig dålig poäng på 39. Laddningstiderna på Booking.com är också mycket längre jämfört med de andra webbplatserna i denna analys. För att förbättra Booking.com kan huvudtrådens arbetsbelastning och JavaScript-exekveringstid minskas, tredje partens kod och oanvänd JavaScript borde också minskas. Man kan också optimera CSS, eliminera render-blockerande resurser, och minska den överfködiga DOM-storleken för att få bättre ladningstider.

Analys
-----------------------
Analysen av de tre webbplatserna visar att de vanligaste förbättringsåtgärden handlar om att optimera bilder, minska JavaScript-exekveringstider och att minska onödiga resurser såsom oanvänd CSS och JavaScript. För att förbättra laddningstiderna behöver webbplatserna oftast minska antalset resurser som laddas och att optimera serverresponsen. 

SVT Play har snittbetyg 67, SAS har 57, och Booking.com har 53.

Kollar man på snittbetygen har SVT Play den bästa poängen. Dock har SAS, jämfört med de andra två webbsidorna, de snabbaste laddningstiderna, lägsta resursanvändning och de minsta sidstorleker. SAS startsida laddar på bara 4.29 sekunder, medans SVT Play laddar på 18.02 sekunder och Booking.com på 32.06 sekunder. Booking.com får inte godkänt av PageSpeed Insight varken på desktop eller mobil, detta tyder på att webbsidan har prestanda- och optimerasproblem. SVT Play får godkänt på desktop men inte på mobil, vilket indikerar att mobilversionen behöver förbättras. SAS har fått godkänt på både mobil och desktop, vilket tyder på att utav alla dessa tre webbplatser är den bäst optimerad för både mobil och desktop. Kollar man på webbsidans mätvärden och poängen från PageSpeed Insights har då SAS den bästa webbsidan och är vinnaren i testet.

Personligen tycker jag en snabb laddningstid är 4 sekunder eller under, medans en långsam laddningstid är på 6 sekunder eller mer. I mitt urval av webbsidor klarar SVT Play min laddningstid gräns på under 4 sekunder, förutom startsidan som är lite långsammare på 18 sekunder. SAS klarar mina gräns, medans Booking.com som har väldigt långsamma laddningstider gör inte det.

Referenser
-----------------------
[PageSpeed Insights](https://pagespeed.web.dev/)


Övrigt
-----------------------

Michelle Tammi