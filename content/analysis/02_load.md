02 Load
=======================

Analys av tre webbsidors laddningstider.

Urval
-----------------------

Jag valde att fortsätta analysera de webbplatser jag tog fram i färganalysen, alltså **penstore.se**, **skapamer.se** och **artistica.nu**.

Metod
-----------------------

För att utföra analysen använde jag mig av verktygen *Pagespeed insights* och fliken "Network" i *devtools*. Med hjälp av dessa verktyg kunde jag se laddningstider för varje webbplats, vad som tog längst tid att ladda på webbplatsen och så vidare.

Resultat
-----------------------

För google pagespeed har tre olika sidor på varje webbplats mätits, där Speed desk 1 i kalkylarket står för "Google pagespeed mätning av länk 1 desktop", och så vidare. Det som antecknats är om betyget för "Test av viktiga webbvärden" är godkänt eller inte. Där ingår saker som "Time to first byte" (3), "First input delay" (4) och "Cumulative layout shift" (5). Länkarna finns under varje rubrik nedan.

Förstasidan har mätits 3 gånger i devtools där medelvärdet finns i kalkylarket.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSkdLxJ1Sj0oITdPxgn9YhZJnqMpNRtUdueDzdiUG0qK0C39H8-l3K7yXWa8qASf8-uTKubqSQPfjYZ/pubhtml?widget=true&amp;headers=false" class="kalkyl"></iframe>

&nbsp;

**Penstore.se:**
<img src="%assets_url%/img/penstore.png" class="no-hue-rotation" alt="">

&nbsp;


Google pagespeed utvalda länkar:
1. https://penstore.se/
2. https://penstore.se/konstn%C3%A4rsmaterial
3. https://penstore.se/lukas/akrylf%C3%A4rg-cryl-terzia-500-ml


&nbsp;


Det som verkar dra ner webbplatsens betyg i *Google pagespeed* är dess CLS, dvs att webbplatsen kan hoppa på grund av hur den laddas eller på grund av DOM element som laddas ovanför existerande innehåll -- så det kan förbättras.

**Skapamer.se:**
<img src="%assets_url%/img/skapamer.png" class="no-hue-rotation" alt="">

&nbsp;


Google pagespeed utvalda länkar:
1. https://skapamer.se/
2. https://skapamer.se/kontorsmaterial/
3. https://skapamer.se/gummisnoddsmapp-natur-a4-1/


&nbsp;


Trots många godkända betyg överlag i Google pagespeed så var prestanda-poängen låga för mobil, vilket webbplatsen kan förbättra.

**Artistica.nu:**
<img src="%assets_url%/img/artistica.png" class="no-hue-rotation" alt="">

&nbsp;

Google pagespeed utvalda länkar:
1. https://artistica.nu/
2. https://artistica.nu/farg/
3. https://artistica.nu/farg/akrylfarg/akrylfarg-rosa-studio-75ml/akrylfarg-rosa-studio-titanium-white-401-75ml.html


&nbsp;


Denna webbplats skulle kunna förbättra sin mobilversion då alla tre sidor fick betyget inte godkänt och låga prestanda-poäng.

Analys
-----------------------
Någonting som webbplatserna har gemensamt är låga prestanda-poäng för mobilversionen. Så där finns det förbättringspotential för samtliga webbplatser. Penstore.se hade också övergripande dåliga resultat för CLS, att innehållet på sidan kan hoppa. Detta känns som att det kan gå väldigt fel i just en webbshop, där man inte vill råka klicka fel och till exempel råka köpa en produkt som inte var meningen att köpa.

Vinnaren av denna mätning blir *artistica.nu* som fick 3/6 godkända betyg och snabbast laddningstid för både DOM och Load. Visserligen är webbplatsen den minsta av de tre och ändå inte så mycket snabbare än *penstore.se*, men eftersom att penstore hade 1/6 godkända betyg i *Google pagespeed* blir artistica vinnaren. 

En gräns för snabb laddningstid anser jag, baserat på påståendet att "40 % av användarna lämnar en hemsida om den tar mer än 3 sekunder att ladda" (1), ligger vid ungefär 3 sekunder. Baserat på samma källa laddar en snabb webbplats på under 2 sekunder. Med detta som grund innebär det att en av de analyserade webbplatserna går strax över gränsen, medan restande håller sig under gränser för en snabb webbplats. Jag upplever också att den långsammare webbplatsen, skapamer.se, känns lite segare att klicka sig igenom. De andra två känns mer lika varandra. 


Referenser
-----------------------

1. https://viseo.se/blogg/snabb-hemsida/
2. https://pagespeed.web.dev/
3. https://web.dev/ttfb/
4. https://web.dev/fid/
5. https://web.dev/cls/


&nbsp;

Övrigt
-----------------------

Analys gjord av Melissa Johansson.
