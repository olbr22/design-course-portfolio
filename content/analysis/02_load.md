---
Title: Load time and Usability
Description: Evaluate websites' loading time and usability
---
Utvärdera webbplatsers laddningstid och användbarhet
=======================
Jag skall välja ut ett antal olika webbplateser och testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag valde tre webbplatser, som enligt min åsikt tillhör olika kategorier. Mitt val bygger på nyfikenhet att välja olika branscher som riktar sig till olika målgrupper och jämföra dem. Den första webbplatsen är www.zalando.se. Zalando är ett modeföretag från Berlin som säljer livsstilsprodukter och modekläder på nätet. [1] Den andra webbplatsen är internetstiftelsen.se. Internetstiftelsen är en oberoende, affärsdriven och allmännyttig organisation. [2] Och den tredje webbplatsen är www.sj.se. SJ AB är ett svenskt järnvägsföretag för persontrafik helägt av svenska staten som verkar under marknadsmässiga villkor och krav. [3]

Metod
-----------------------
Jag mäter sidornas laddningstid, antal resurser och sidornas totala storlek med verktyget DevTools och fliken Network. För varje sida genomförs mätningen tre gånger och tas snittet av mätvärdena. Mätningarna sparas i [ett Excel-ark](https://docs.google.com/spreadsheets/d/1_hWjBX3PUx8hopcDvgb2CkX6Lpgr2jpPnVVWmrtDqOg/edit#gid=0). För att mäta eventuella brister i användarupplevelse använder jag verktyget [PageSpeed Insights](https://pagespeed.web.dev/). PageSpeed Insights (PSI) rapporterar om användarupplevelsen av en sida på både mobila och stationära enheter och ger förslag på hur sidan kan förbättras.

Resultat
-----------------------
## Zalando
<a href ="../image/zalando_full_size_sshot.png">
<img src="../image/zalando.png" alt="Zalando printscreen" class="analysis-img" width="250" height="250">
</a>
p.s. Tryck på bilden för att få den större.

### Sidor som mäts med Google PageSpeed Insights
1. https://www.zalando.se/damklader/
2. https://www.zalando.se/herrklader/
3. https://www.zalando.se/barn-klader/

Läs om PageSpeed Insights mätvärden [här](https://developers.google.com/speed/docs/insights/v5/about#distribution).
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6X3UX0543gJpMJhS4XzPgAiR05vddDP-egH-j5-iVRcjq1jzCn1rJ9H-eNgYcbmWv0_-ikhjKJF68/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

### Förbättringsförslag
Enligt PageSpeed Insights kan sidan bli bättre på:
1. Redusera oanvänd JavaScript.
2. Minska den initiala serverns svarstid.
3. Leverera kritisk JS/CSS inline och skjuta upp alla icke-kritiska JS/stilar.
4. Lägga till beskrivande länktext.
5. Interaktiva element som knappar och länkar bör vara tillräckligt stora (48x48px) och ha tillräckligt med utrymme runt dem.

## Internetstiftelsen
<a href ="../image/internetstiftelsen_full_size_sshot.png">
<img src="../image/internetstiftelsen.png" alt="Zalando printscreen" class="analysis-img" width="250" height="250">
</a>
p.s. Tryck på bilden för att få den större.

### Sidor som mäts med Google PageSpeed Insights
1. https://internetstiftelsen.se/domaner/
2. https://internetstiftelsen.se/kunskap/
3. https://internetstiftelsen.se/motesplatser/

Läs om PageSpeed Insights mätvärden [här](https://developers.google.com/speed/docs/insights/v5/about#distribution).
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6X3UX0543gJpMJhS4XzPgAiR05vddDP-egH-j5-iVRcjq1jzCn1rJ9H-eNgYcbmWv0_-ikhjKJF68/pubhtml?gid=188033972&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

### Förbättringsförslag
Enligt PageSpeed Insights kan sidan bli bättre på:
1. Redusera oanvänd JavaScript.
2. Redusera oanvänd CSS.
3. Använda bildformat som WebP och AVIF. Dessa ofta ger bättre komprimering än PNG eller JPEG, vilket innebär snabbare nedladdningar och mindre dataförbrukning.
4. Leverera kritisk JS/CSS inline och skjuta upp alla icke-kritiska JS/stilar.
5. Inte använda föråldrade API:er.

## Järnvägsföretag SJ
<a href ="../image/sj_full_size_sshot.png">
<img src="../image/sj.png" alt="sj.se printscreen" class="analysis-img" width="250" height="250">
</a>
p.s. Tryck på bilden för att få den större.

### Sidor som mäts med Google PageSpeed Insights
1. https://www.sj.se/sv/vi-erbjuder.html
2. https://www.sj.se/sv/reseinfo.html
3. https://www.sj.se/sv/kundservice.html

Läs om PageSpeed Insights mätvärden [här](https://developers.google.com/speed/docs/insights/v5/about#distribution).
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6X3UX0543gJpMJhS4XzPgAiR05vddDP-egH-j5-iVRcjq1jzCn1rJ9H-eNgYcbmWv0_-ikhjKJF68/pubhtml?gid=964000597&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

### Förbättringsförslag
Enligt PageSpeed Insights kan sidan bli bättre på:
1. Redusera oanvänd JavaScript.
2. Minifiera JavaScript.
3. Redusera oanvänd CSS.
4. Använda bildformat som WebP och AVIF. Dessa ofta ger bättre komprimering än PNG eller JPEG, vilket innebär snabbare nedladdningar och mindre dataförbrukning.
5. Avända lazy-loading av bilder.
6. Leverera kritisk JS/CSS inline och skjuta upp alla icke-kritiska JS/stilar.
7. Inte använda föråldrade API:er.

Analys
-----------------------
Samtliga analyserade webbplatser fick några gemensamma förbättringsförslag att redusera oanvänd JavaScript samt att leverera kritisk JS/CSS inline och skjuta upp alla icke-kritiska JS/stilar. Internetstiftelsen och SJ fick ett förslag på att använda bildformat som WebP och AVIF. WebP och AVIF ofta ger bättre komprimering än PNG eller JPEG, vilket innebär snabbare nedladdningar och mindre dataförbrukning. Föråldrade API:er drar laddningstiden ner och rekomenderas att tas ur bruk eller ersättas. Webbplatsen Zalando fick även några förslag på att förbättra serverns svarstid.

Baserat på mätvärdena tar webbplatsen Internetstiftelsen första plats med sidornas laddningstid på strax över en sekund. Mätvärderna för varje sida - ```1.35s, 1.34s, 1.2s```. Enligt PageSpeed Insights tar Internetstiftelsen även här första plats. Mätvärdena visar på att kvaliteten på användarupplevelser tillfredsställs effektivt.

Webbsidan Zalando tar andra plats med sidornas laddningstid på strax över två sekunder. Mätvärderna för varje sida - ```2.09s, 2.43s, 1.62s```. Enligt PageSpeed Insights visar mätvärdena på att mätvärde Interaction to Next Paint (INP) bör förbättras. INP värde visar att sidan hade måttliga svårigheter med att konsekvent svara snabbt på alla eller de allra flesta av användarinteraktioner (klick-, tryck- och tangentbordsinteraktioner).

Webbsidan SJ tar tredje plats. Sidornas laddningstid varierar ganska mycket för varje undersökt sida. Mätvärderna för varje sida - ```4.34s, 5.23s, 2.77s```. PageSpeed Insights visar på att mätvärdena Interaction to Next Paint (INP) och Time to First Byte (TTFB) bör förbättras. TTFB hjälper att identifiera när en webbserver svarar för långsamt på förfrågningar.

Gräns för absolut laddningstid
-----------------------
En studie, där 5 miljoner dator- och mobilsidor var undersökta för faktorer som påverkar sidhastigheten [4], visat att den genomsnittliga tiden det tar att ladda en webbsida helt är 10.3 sekunder på dator och 27.3 sekunder på mobil.
Jag uppfattar en webbsida som långsam då dess laddningstid överstiger 3 sekunder. Med det jag menar att jag vill se första bild, text eller liknande laddas på sidan inom 3 sekunder. En webbsida som jag uppfattar som snabb, laddar första bild, text eller liknande på tid under 3 sekunder. Jag upplever samtliga undersökta sidor som snabba.

Referenser
-----------------------
1. Wikipedia. 2022. Zalando. https://sv.wikipedia.org/wiki/Zalando (Hämtad 2022-11-22).
2. Internetstiftelsen. https://internetstiftelsen.se/ (Hämtad 2022-11-22).
3. Wikipedia. 2022. SJ. https://sv.wikipedia.org/wiki/SJ (Hämtad 2022-11-22).
4. Backlinko. 2019. WE ANALYZED 5.2 MILLION DESKTOP AND MOBILE PAGES
Here’s What We Learned About Page Speed. https://backlinko.com/page-speed-stats (Hämtad 2022-12-14).

Övrigt
-----------------------
Mitt namn är Olha Bruce. Analysen är mitt självständiga arbete.