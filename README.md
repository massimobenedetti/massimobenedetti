# Model

Het staat model voor digitale tuintjes welke bij 'Het web is voor iedereen' door studenten worden gemaakt.

## Learning Log

test

### Sprint 1 - Wo: WS5

ZIEK DUS NOG INVULLEN

### Sprint 1 - Ma: WS4 + Bi-weekly geek 1

1. Leg uit wanneer een website 'lelijk' wordt en geef voorbeelden wat je kan doen om deze 'lelijke' onderdelen te fixen?
   Een website kan snel lelijk worden doordat deze niet voorbereid is op verschillende schermgroottes. Dit kan door een simpele regel in code wel responsive gemaakt worden.

2. Vertel welke volgende stap je neemt om je website responsive te maken.
   Ik heb de volgende regel toegepast in mijn code:

/_ LAYOUT LAPTOP FORMAAT _/
@media (width > 40em) {
.timeline-item {
grid-template-columns: 19fr 15fr;
align-items: center;
}

/_ MOBIEL FORMAAT _/

@media (width <= 40em) {
.page{
width: 100%;
padding: 1.2em 1em 2em;
}

.intro {
margin-bottom: 2.5em;
}

.intro h1 {
font-size: 12vw;
}

.timeline-item {
grid-template-columns: 1fr;
gap: 1em;
margin-bottom: 2em;
padding: 0.7em 0.7em 1em;
border-radius: 0.8em;
}

.text h2 {
font-size: 13vw;
letter-spacing: 0.04em;
}

.text p {
font-size: 3.2vw;
line-height: 1.3;
}

.timeline-item > img {
width: 100%;
aspect-ratio: 16/9;
border-radius: 0.7em;
}

.images {
grid-template-columns: 1fr 1fr;
gap: 0.5em;
}

.images img {
aspect-ratio: 1/1;
border-radius: 0.7em;
}
}

3. Kun je het ontwerp en de bouw van je eigen Garden (zo uit je hoofd) onderbouwen in Webby vocabulair?
   Mijn Garden gebruikt een constante stijl (vormen en lettertype) en een overzichtelijke layout. Ook heb ik de website responsive gemaakt voor meerdere schermen.

### Sprint 1 - Vr: WS3 + Voortgang

Welke feedback heb je gehad?
Mijn idee voor mijn website heeft potentie, ik moet dit alleen nog gaan uitwerken in HTML/CSS. Ook ben ik geholpen met het terugkrijgen van mijn README bestand.

### Sprint 1 - Wo: WS2

1. Leg uit waar het Visual Research in 3 stappen naartoe werkt
   Inspiratie verzamelen -> Wat spreekt mij hiervan aan -> aan de hand hiervan zelf ontwerpen.

2. Vertel in 2 zinnen waar jouw Garden over gaat, en met welke content je dat gaat doen (beeld, tekst, sound, animatie enz).
   Mijn garden gaat over mijn passie voor autosport. Aan de hand van eigen afbeeldingen wil ik mijn verhaal vertellen.

3. Vertel kort welk idee van de Crazy 8 je het liefst zou willen uitvoeren/ verder zou willen onderzoeken.
   Ik ga mijn verhaal vertellen aan de hand van een tijdlijn van mijn eigen belevingen in de autosport.

### Sprint 1 - Ma: Sprintplanning + WS1

1. Leg uit wat een digital garden is en waarom dat anders is dan een reguliere website.
   Een digital garden is een stuk persoonlijker dan een website

2. Leg uit wat een website 'webby' maakt.
   Een website wordt webby wanneer deze creatief, interactief, volwassen, gebruiksvriendelijk en visueel aantrekkelijk zijn.

3. Vertel waar jij mee aan de slag wilt gaan bij het maken van jouw eigen digital garden.
   In mijn digital garden wil ik mensen mijn passie voor autosport overbrengen.

### Kickoff

1. Leg uit wat een source hosting platform is en voor welke jij gekozen hebt.
   Een online server waar je de code voor je website opslaat

2. Vertel welke domeinnaam jij gekozen hebt en hoe je die hebt gekoppeld aan jouw pagina.
   Ik heb gekozen voor massimobenedetti.nl en deze heb ik gekoppeld via GitHub

3. Beschrijf hoe je aanpassingen aan jouw pagina kunt maken en hoe je er voor zorgt dat die op het web gepubliceerd worden.
   Door aanpassingen te maken in mijn HTML en CSS bestanden die gelinkt zijn aan mijn GitHub en deze vervolgens te committen

Een fork van de model repository gemaakt en gepubliceerd via mijn eigen Github omgeving.
