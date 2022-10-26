# Inleiding
Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. 

Voor het vak Web typografie hebben we de opdracht gekregen om een video visueel vorm te geven voor een dove doelgroep. Dus eigenlijk closed captions maar dan veel visueler en extremer, waardoor de doelgroep een nieuwe experience krijgt tijdens het bekijken bij een film/ video. 

## Leerdoelen
- Je kan de kennis over vormgeving die je hebt opgedaan tijdens de minor technisch toepassen met behulp van CSS
- Je kan verborgen nuance uit een audiotrack overtuigend vertalen naar visuele (typografische) beelden
- Je kan je typografische keuzes onderbouwen.
- Je hebt de exclusive design principles gebruikt.


## Design principes
Tijdens het ontwerpen van de filmfragmenten moeten we rekening houden met de volgende design principes:

- Study situation
- Ignore Conventions
- Prioritise Identity
- Add Nonsense

## Oplevering
- Je levert een werkende versie op, gemaakt met HTML, CSS en JavaScript. Deze staat op Github. In een duidelijke readme documenteer en onderbouw je je ontwerpkeuzes. Je developmentgeschiedenis is terug te vinden op GitHub.

- Documentatie en proces hiervan in je readme.

- Je levert ook een *screen recording* met audio op van je fragment. Dit is een video van de definitieve versie, gemaakt van jouw browserscherm.

- De beoordeling is mondeling en volgt [de rubric uit het beoordelingsformulier](web-typografie-beoordeling.pdf).


# Proces
We kregen eigenlijk gelijk als tip van Vasilis om gewoon te beginnen met coderen. Zo doe je lekker inspiratie op en krijg je along the way ideeën. Dus dit deed ik. Ik vond dit super fijn werken, want in het begin dacht ik echt wat ga ik in hemelsnaam maken. Maar toen ik gewoon begon met coderen vloeide de ideeën binnen.

## Typografische keuzes
Ik heb gekozen voor het brenner lettertype omdat er zoveel opties zijn binnen het font. Dit leek me erg handig om dit toe te passen op de verschillende personages. Ieder personage krijgt zo zijn eigen font zodat de doelgroep beter kan onderscheiden dat het gaat om verschillende personen.

## Personages
### Personage 1: De man die vragen stelt
dnjw
### Personage 2: Hoofdpersonage

### Personage 3: Persoon die vloekte

### Personage 4: You can pick up your bonus





# Voortgangsgesprekken
## Voortgang 1
## Voortgang 2
## Feedback



# Bronnen









## Typografische restricties

Je *moet* een van deze twee opties kiezen, en je keuze moet je onderbouwen. In je readme staat een uitleg over je overwegingen om de ene of de andere restrictie te kiezen.

### Optie 1: Systeemfont

De eerste optie is dat je gebruik maakt van het zogenaamde *systeemfont* van degene die naar jouw werk kijkt. Dit font verschilt per operating system, en het verschilt soms zelfs per versie van het operating system. Het is ook aan te passen door de gebruiker zelf. 

Je hebt dus geen controle over welk lettertype er precies gebruikt wordt. Het levert dus een onzeker, en beperkt typografisch palet op. Je hebt geen *light* versies, of *extrabold*. En ook geen serif en sans-serif versie van dezelfde familie. In dit geval heb je alleen de beschikking over normal, **bold** en _italic_. Dit heeft natuurlijk ook zijn voordelen!

### Optie 2: Brenner

Je kan er ook voor kiezen om gebruik te maken van de complete Brenner familie. Dit is een zeer uitgebreid en uiterst flexibel font. [Hier kan je je verdiepen in dit font](https://www.typotheque.com/blog/brenner_an_unusual_typeface_family_with_distinct_voices). Als je kiest voor dit font dan heb je de beschikking over een *sans serif*, een *condensed*, een *serif*, een *monotype*, een *slab*, een *display* en een *script* versie. En veel van deze versies hebben varianten van *light* tot *bold*, en allemaal zowel *bold* als *italic*.

Met Brenner zijn er natuurlijk veel en veel meer mogelijkheden dan met systeemfonts. Dat kan zowel een voordeel als een nadeel zijn. 

Voor een overzicht, zie [de brenner.pdf](brenner.pdf).

### Tijdens het afspelen

Tijdens het afspeelen wordt er een class `on` op de caption gezet als hij moet verschijnen, en een class `off` als hij klaar is. *Zowel class `on` als class `off` blijft op de caption staan!*

De timimg van de captions kan je aanpassen in [closed-captions/captions.js](closed-captions/captions.js).

Er verschijnen ook classes op de body op momenten dat er geluiden worden afgespeeld, zoals `sound1` en `sound2`. Je kan geluiden toevoegen in [closed-captions/sounds.js](closed-captions/sounds.js).

*let op,* de geluiden zijn niet compleet, dit zal je zelf moeten aanvullen.
