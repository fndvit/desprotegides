# Desprotegides malgrat tot
Karma Peiró venia de participar —durant 8 mesos— en el projecte #Cuéntalo, on milers de dones havien narrat les seves històries de violència masclista en 140 caràcters. Els drames personals estaven ampliament explicats. Calia posar el focus en com estava encarant l’administració un assumpte de tal dimensió. 

Aquest reportatge s'ha elaborat gràcies al finançament de la Fundació.Cat. L'objectiu és el retiment de comptes (accountability) a l'administració catalana sobre els recursos públics emprats per erradicar la violència masclista. Sempre amb un interès de reparació, de millora de la situació actual.

## Metodologia
A la primera ullada de dades, vam adonar-nos que calia visibilitzar la violència masclista silenciada. Fins i tot quan els mitjans de comunicació informen del tema, sovint no aconseguim mostrar adequadament l’abast, la freqüència i la gravetat de totes les formes de violència contra les dones. Tenim l’esperança de que el llarg *scroll* de dones al principi de l’historia ajudarà el nostre públic a comprendre la magnitud.

Ens vam limitar a la dècada passada —des de que el Parlament va aprovar la Llei sobre el dret de les dones a eradicar la violència masclista. Vam analitzar dades de Mossos, del Consejo General del Poder Judicial, del departament de Salut, de l’Institut Català de les Dones i de múltiples enquestes —les estimacions que utilitzem a l’informe es basen en l’enquesta catalana de 2016—. Vam llegir desenes d’estudis i avaluacions europees, espanyoles i catalanes de programes públics.

Atès que els pressupostos publicats en els portals de transparència no especifiquen les partides destinades a la violència masclista, vam demanar-lo per la Llei de Transparència. Després de l’ajornament d'un mes, l'Institut Català de les Dones va demanar un segon ajornament, després del que hem rebut un recull d'informes prèviament publicats —i que ja eran a la nostra col·lecció de fonts—.

Vam entrevistar a la Raquel qui gairebé va ser assassinada per la seva ex-parella. Ara treballa per ajudar a dones que passan per la mateixa situació. Vam filmar entrevistes amb experts i vam parlar amb més d’una desena d’altres per entendre la xarxa de professionals implicats en casos de violència envers les dones.

Podeu trobar tots aquests [documents](https://github.com/xaquingv/desprotegides/tree/master/documents) i [dades](https://github.com/xaquingv/desprotegides/tree/master/dades) nets a les carpetes corresponents.

## Alerta nerd
Per al segon mapa del gràfic scrollytelling al capítol 3, vam obtenir les zones a menys de 30 minuts amb cotxe del 100 i escaig SIADs fent servir l'API Isochrone de Mapbox. Després les hem fusionat i hem utilitzat el resultat per retallar un raster amb dades de densitat de població (amb nombre de persones per cel·la) per estimar la població en el rang d’un SIAD.

## Sob el disseny
Aquesta és una història sobre la violència contra les dones i un dels pilars que donen suport al patriarcat és la invisibilitat de les contribucions de les dones en tots els camps. Per a la nostra presentació, vam escollir fonts dissenyades per Veronika Burian i Jose Scaglione, fundadors de TypeTogether. Burian és membre fundador de [alphabettes.org](http://www.alphabettes.org/about/), una xarxa per donar suport i promoure el treball de les dones en disseny i tipografia. Si sou un nerd de la tipografia, aquí teniu unes lectures molt macas:
- [The Eye on Design Guide to Women-Designed Contemporary Type](https://medium.com/aiga-eye-on-design/the-eye-on-design-guide-to-women-designed-contemporary-type-d3ddfbfbfc99)
- [Fonts by Women, curated by Ellen Lupton](https://fonts.adobe.com/collections/fonts-by-women)
- [typequality.com](https://www.typequality.com)

Per a la cortina de 75.000 dones del primer gràfic vam utilitzar WeePeople, una font de ProPublica i Alberto Cairo, i vam escollir a l'atzar lletres de la cadena 'abcdefghijklmnopqrs' — amb tots els personatges femenins disponibles a la font.

## L'equip
**Karma Peiró** és una periodista i docent catalana especialitzada en internet i el periodisme de dades. Va ser directora de Nació Digital des del juliol de 2015 fins a l'abril de 2018. Abans va ocupar càrrecs de responsabilitat a ara Web, en.red.ando, Catalunya Ràdio, La Vanguardia Digital i TVE.

**Xaquín G.V.** és un periodista de dades i editor visual gallec. Entre 2014 i 2017, va dirigir l'equip de Visuals de The Guardian a Londres. Abans va treballar a National Geographic, The New York Times, Newsweek i El Mundo (Espanya).

**Rocío Minvielle** és una documentalista audiovisual, productora, activista feminista i part del colectiu insurRECtas.


---

# Unprotected — in spite of everything
Between 2017 and 2018, Karma Peiró had been involved in project #Cuéntalo, which recorded the stories of thousands of women speaking out about their personal experiences with violence in 140 characters.

These were powerful personal dramas, what was the government doing to address violence against women?

The story received funding from Fundació.Cat, a private non-profit that promotes the Catalan language and culture in technology. Our goal was government accountability TK TK.

Our first task was to visualize the real breadth of the issue: even when media outlets report on it, we often fail to properly showcase the reach, frequency, and severity of all forms of violence against women. Hopefully, our long scroll of women helps our audience grasp the magnitude.

## Methodology
We limited our time scope to the past decade — since Parliament passed the Catalan Law on Women's Right to Eradicate Gender Violence. We analyzed data from the regional police, the courts, the health department, the Catalan Institute for Women, and multiple surveys. The estimates we use throughout the report are based on the 2016 Catalan survey.

We read through dozens of European, Spanish and Catalan studies and assessments of public programs. Since the government budget doesn’t classify when an investment is linked to the program to combat and prevent violence against women, we requested that breakdown through the Transparency Law to various departments and, after some extensions, we received a breakdown by department and a collection of reports that had previously been released — and that were already in our cache of sources.

We interviewed Raquel who was almost killed by her ex-partner. She now works helping women going through the same situation.
We filmed interviews with experts and spoke to more than a dozen others to understand the network of professionals involved in cases of violence against women.

You can find all these [documents](https://github.com/xaquingv/desprotegides/tree/master/documents) and clean [datasets](https://github.com/xaquingv/desprotegides/tree/master/dades) in the corresponding folders.

## Nerd alert
For the second map on the scrollytelling graphic, we retrieved the areas within a 30-minute drive from every one of the 100 and some Women’s Support and Information Center (SIADs) using Mapbox’s Isochrone API. We then merged them and used the result to clip a raster dataset with population density (with number of people per cell) to estimate the population in range of a SIAD.

## About the design
This is a story about violence against women and one of the pillars that support patriarchy is the invisibility of women’s contributions in every field. For our presentation, we chose fonts designed by Veronika Burian and Jose Scaglione — founders of TypeTogether. Burian is a founding member of [alphabettes.org](http://www.alphabettes.org/about/), a network to support and promote the work of women in Design and Typography. If you’re a type nerd, here’re some nice reads:
- [The Eye on Design Guide to Women-Designed Contemporary Type](https://medium.com/aiga-eye-on-design/the-eye-on-design-guide-to-women-designed-contemporary-type-d3ddfbfbfc99)
- [Fonts by Women, curated by Ellen Lupton](https://fonts.adobe.com/collections/fonts-by-women)
- [typequality.com](https://www.typequality.com)

For the wall of 75.000 women in the first graphic we used WeePeople, a font by ProPublica and Alberto Cairo, and we randomly chose from the ‘abcdefghijklmnopqrs’ string — which renders all the available female characters in the font. They are: TK TK list from David Sleight TK TK

## The team
**Karma Peiró** is a data journalist and instructor from Catalunya. She was the editor in chief at Nació Digital between 2015 and 2018. Before that, she worked and lead teams at ara Web, en.red.ando, Catalunya Ràdio, La Vanguardia Digital, and TVE.

**Xaquín G.V.** is an interactive, data and visual journalist from Galicia. Between 2014 and 2017, he led the Visuals desk at The Guardian in London. Before that, he worked at National Geographic, The New York Times, Newsweek and El Mundo (Spain).

**Rocío Minvielle** is a documentary filmmaker, producer, and feminist activist. She’s a member of the insurRECtas collective.
  
