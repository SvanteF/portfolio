---
Title: Prestanda
Description: This is my report page
Template: report
---

Prestanda
=======================

Tre olika webbplatser ska väljas ut och testas med avseende på prestanda. Författaren ska avgöra hur snabbt de laddas samt redogöra för om de kan förbättras med tanke på laddningstid och användbarhet.

<br>

Urval
-----------------------

De tre webbplatserna som valdes ut är, några av författaren, de mest använda under hösten 2024. Dessa är: [dbwebb.se](https://dbwebb.se/), [di.se](https://www.di.se/) och [coinmarketcap.com](https://coinmarketcap.com/). Det är tre mycket olika sidor vilket eventuellt kan ge intressanta resultat.

<br>

Metod
-----------------------

[Google Pagespeed](https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect) (både för mobil och dator) och devtools (nätverk) har använts för att mäta webbplatsernas prestanda. Google pagespeed bedömer Prestanda, Tillgänglighet, Best Practice och SEO. Devtools bedömer antalet använda resurser, total storlek samt laddningstid. I dessa försök ska tre tester utföras och ett medelvärde för laddningstiden presenteras. 

<br>

Resultat
-----------------------
### [dbwebb.se](https://dbwebb.se/)

![Image of dbwebb](../image/dbwebb.png){.news-image}

<br>

Sidorna som testats är [dbwebb.se](https://dbwebb.se/), [dbwebb.se/kurser/webtec-v2](https://dbwebb.se/kurser/webtec-v2) samt [dbwebb.se/kurser/design-v3](https://dbwebb.se/kurser/design-v3).

<br>

<iframe class="measurements" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTW-yi-04086kjfSIWB0lCm-KwPc-8MCbJOWATXmjLXqWEDRltpfDcSDUVTDTaOXOrpBP7ckqO-brAb/pubhtml?widget=true&amp;headers=false"></iframe>


<br>

[dbwebb.se](https://dbwebb.se/) uppvisar relativt goda resultat med godkända betyg avseende prestanda, tillgänglighet, best practice och SEO. Även laddningstiden, i genomsnitt 1.22 sekunder, är acceptabel. Gällande de övriga två sidorna är det något annorlunda. Mycket låg prestanda rapporteras för båda samt att sidorna aldrig laddar färdigt. Detta beror på beroende av tredje part, den inbäddade spelaren från Youtube i detta fall. "https://www.youtube.com/youtubei/v1/log_event?alt=json" slutar aldrig att köra. Implementationen av inbäddade spelare bör därför ses över.

<br>

★ 

<br>

### [di.se](https://www.di.se/)

![Image of dagens industri](../image/di.png){.news-image}

<br>

Sidorna som testats är [di.se](https://www.di.se/), [di.se/bors](https://www.di.se/bors/) samt [di.se/digital](https://www.di.se/digital/).

<br>

<iframe class="measurements" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ_PS6telgTLiQhvIAYaV-3g1lJebc9CisQM1s0c87TcYYZux4WdqqG5mTYfwB644syhx8Gk7zS7vov/pubhtml?widget=true&amp;headers=false"></iframe>

<br>

Samtliga testade sidor på Dagens industri uppvisar låga omdömen avseende prestanda, framför allt på mobil. Laddningstiden för [di.se/digital](https://www.di.se/digital/) är hela 1.85 sekunder i genomsnitt och de övriga är enbart något bättre. Även här kan beroendet av tredje part minskas samt även arbetsbelasningen på modertråden orsakad av hantering av en mängd javascript. 

<br>

★ 

<br>

### [coinmarketcap.com](https://coinmarketcap.com/)

![Image of coinmarketcap](../image/cmc.png){.news-image}

<br>

Sidorna som testats är [coinmarketcap.com](https://coinmarketcap.com/), [coinmarketcap.com/currencies/bitcoin](https://coinmarketcap.com/currencies/bitcoin/) samt [coinmarketcap.com/dexscan](https://coinmarketcap.com/dexscan/trending/all/).

<br>

<iframe class="measurements" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS6KgyeJDzAuazxFqTmbkFU_QSuS50DuNR7uyUM2-e3m0KNK3LDpoppr6Xn2K5uaCtKKPC1xPwoaNs8/pubhtml?widget=true&amp;headers=false"></iframe>

<br>

[coinmarketcap.com](https://coinmarketcap.com/) uppvisar klart längst laddningstider av de testade webbplatserna med hela 3.79 sekunder i snitt. Den har också låga prestandaomdömen, framför allt på mobil. Likt Dagens industri är modertråden hårt belastad hantering av javascript. 

<br>

Analys
-----------------------

Det var, för författaren, överraskande långa laddningstider för de testade webbplatserna. Särskilt för [coinmarketcap.com](https://coinmarketcap.com/). Det hanteras av att sidan ritas upp mycket snabbt för att sedan uppdatera datan. Det gör att författaren inte upplever sidan som så långsam som den verkligen är. 

<br>

De vanligaste förbättringsåtgärderna som föreslås av [Google Pagespeed](https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect) handlar uteslutande om att förbättra prestandan, främst på mobil som genomgående uppvisar lägre resultat än på dator. Inom området prestanda är det främst användandet av javascript och beroende av kod från tredje part som drar ner betygen.

<br>

[dbwebb.se](https://dbwebb.se/) uppvisar både bäst betyg och kortast laddningstider, särskilt för huvudsidan. [di.se](https://www.di.se/) har lägre prestanda men klart godkänt inom de övriga kategorierna. Laddningstiderna är något högre än [dbwebb.se](https://dbwebb.se/). [coinmarketcap.com](https://coinmarketcap.com/) är klart sämst med överlag låga betyg och överlägset längst laddningstider. 

<br>

Baserat på uppmätna testresultat placerar sig webbplatserna enligt nedan:

<br>

1. [dbwebb.se](https://dbwebb.se/)
2. [di.se](https://www.di.se/)
3. [coinmarketcap.com](https://coinmarketcap.com/)

<br>

Vad som är en bra laddningstid uppfattar författaren beror mycket på vilken information som presenteras i vilken ordning. Numera behöver en användare klicka flera gånger för att ens komma in på en webbplats, i och med GDPR, så laddningstiden är inte alltid det som mest påverkar användarupplevelsen. Generellt sett är under 2 sekunder knappt märkbart enligt författaren, sedan upplevs laddningstiden snabbt som långsam efter det. 

<br>

Övrigt
-----------------------

Författare: Svante Fahlström
