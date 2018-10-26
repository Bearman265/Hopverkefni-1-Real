# Hopverkefni-1-RealHópverkefni 1
Verkefnið felst í því að smíða vef eftir forskrift.

Gefnar eru fyrirmyndir í 500px, 800px og 1500px með grind ásamt 1500px án grindar og yfirliti yfir virkni vefs í utlit/video.mp4.

Síður
Gögn fyrir síður eru í viðeigandi textaskrám (t.d. forsida.txt) undir efni/. Myndir fyrir síður eru gefnar undir img/. Afrita þarf öll gögn á milli síðna, ekki er krafa um að setja upp sameiginlegan haus/fót á síðum með einhverju kerfi eða forritun.

Efni síðu skal ekki vera breiðara en 1200px. Litir í haus og fæti skulu fylla út í allt lárétt pláss.

Síður hafa allar sama haus og sama fót. Vöruflokkar í fæti skulu allir vísa á pages/products.html.

Grunn leturstærð er 16px og fylgja allar aðrar leturgerðir eftirfarandi skala: 12 14 16 18 21 24 36 48 60.

Litapalletta fyrir vef er #000000, #ffffff, #afb281, #cee8ff, #fcffd2 og #cc9694.

Letur fyrir meginmál er Open Sans eða helvetica, arial eða sans-serif letur. Letur fyrir fyrirsagnir er Oswald, Verdana eða serif letur.

Flest allt er sett upp í 12 dálka grind með 20px gutter.

Öll bil eru hálft, heilt, tvöfalt eða þrefalt margfeldi af gutter. Hægt er að nota reglustiku tól (t.d. http://www.arulerforwindows.com/ eða http://www.pascal.com/software/freeruler/) til að finna nákvæmar stærðir en mestu skiptir að lausn svipi til en sé ekki nákvæmlega eins og fyrirmynd.

Allar hreyfingar gerast á 300ms með ease-in-out hröðunarfalli.

Ekki þarf að útfæra neina virkni fyrir takka eða form.

Hópavinna
Verkefnið skal unnið í hóp með þremur einstaklingum. Hafið samband við kennara ef ekki er mögulegt að vinna í hóp.

Notast skal við Git og GitHub. Engar zip skrár með kóða ættu að ganga á milli í hópavinnu, heldur á að „committa“ allan kóða og vinna gegnum Git.

Lýsing á verkefni
README.md skrá skal vera í rót verkefnis og innihalda:

Upplýsingar um hvernig keyra skuli verkefnið
Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við
Upplýsingar um alla sem unnu verkefni
Leyfilegt er að halda eftir þessari verkefnalýsingu en hún skal þá koma á eftir ykkar lýsingu
Tæki og tól
Setja skal upp Sass og stylelint fyrir verkefnið. Gefin er styles.scss skrá með grunn upplýsingum.

Gefin er .stylelintrc skrá sem segir til um hvernig lint fyrir scss skrár skuli háttað.

Í .gitignore er styles.css hunsað sem þýðir að það verður ekki checkað inn. Það er gert vegna þess að það er búið til af sass út frá styles.scss

Gefnar skrár
Eftirfarandi er sett upp í verkefni:

.stylelintrc með upplýsingum um hvernig stylelint eigi að haga sér. Setja þarf upp stylelint-config-primer pakkann
.gitignore sem hunsar algengar skrár, sjá nánar
.gitattributes sem kemur í veg fyrir ósamræmi sem geta komið upp þegar unnið er á milli stýrikerfa
.editorconfig sem samræmir notkun á tabs og spaces, bilum og fleira
index.html með vísun í styles.css og grid.css ásamt tómum skrám fyrir products.html, about.html og cart.html undir pages/, halda skal þessu skipulagi
grid.css til að sjá grid sem fyrirmynd er unnin eftir
Setja þarf upp package.json og sækja viðeigandi pakka til að tæki og tól sem verkefnið á að nýta virki.


Samstarfsmenn:
Eiríkur Egill Gíslason,
Hrafnkell Þráinsson,
Þorri Harðarson

Ekki tókst að útfæra þetta í scss, en gerð var tilraun til þess að færa kóðann úr css yfir á scss form.
