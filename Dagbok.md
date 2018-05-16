# Dagbok

## 2018-04-09

*   Idag träffade jag min handledare.
*   Jag läste också tre studier som handlade om "property based testing", där man utifrån att veta vad som är giltig indata (mha JSON Schema), slumpar en massa giltig och ogiltig data och jämför resultatet med det förväntade resultatet.
*   Jag började också skriva dagbok.

## 2018-04-10

*   Idag var en halvdag. Jag motiverade min halvdag med att jag påbörjade arbetet (dock mest det praktiska arbetet) en bra bit (ca 2-3 veckor) innan projektet officiellt "började".
*   Jag utredde olika metodval. Hur man ska tänka kring metodval.
    [Inspiration](http://www.eippee.eu/cms/Default.aspx?tabid=3284)
*   Jag skrev lite. Mest egna kommentarer så att jag inte skulle glömma saker.

## 2018-04-11

*   Idag var en halvdag pga ovan nämnda anledningar.
*   Jag skrev färdigt kapitlet som förklarade JSON.
*   Jag skrev "färdigt" kapitlet som förklarade JSON Schema.

## 2018-04-12

*   Började fundera på och implementera flödet (Det blev mest första steget):

> JSON Schema -> Datarepresentation i Delphi (Språket programmet skrivs i) -> Användargränsnitt

*   Strukturerade om hela rapporten. Byggde det efter kth-mallen i word.
*   Skrev ner saker under rubriken arbete.

## 2018-04-13

Det mest grundläggande användargränsnittet skapades, och ett json-schema kunde skickas från server, och sedan generera ett extremt enkelt gränsnitt på klienten. Inga värden kan ändras än och schemat är hårdkodat. Användargränsnittet jobbar enbart med "title" och "description" så ingen riktig data.

## 2018-04-16

Idag skapade jag stöd för att generera ett gui som kan visa, beskriva, låta användare redigera och spara:

*   textsträngar
*   ipv4 formaterade textsträngar
*   heltal
*   booleska värden

## 2018-04-17

Idag var en skrivardag. Förstudien är i princip färdig nu.

## 2018-04-18

Idag renskrev jag en hel del innan jag skickade in min rapport. Jag läste Abdullahis och Rasmus rapport och noterade några kommentarer.

## 2018-04-19

Idag fortsatte jag skriva på teorin. Det saknades mycket om "hur andra gjort" och jag började skriva på det.

## 2018-04-20

Idag fortsatte jag mycket med det jag gjorde igår. Att skriva om tidigare implementationer. Jag gick också på halvtidsseminarium med handledare och två andra grupper. Jag fick bra feedback.

## 2018-04-23

Idag implementerade jag en massa sista grejer till uit. Nu kan man specificera:

*   Att en textsträng har en max eller minlängd
*   Att en textsträng följer ett "regex-pattern", dvs vilket mönster som helst.
*   Att ett heltal har ett max eller minvärde
*   Att ett värde bara får vara ett av några förutbestämda värden.
*   Att det finns "default"-värden

Implementationen är i princip helt färdig nu.

## 2018-04-24

Idag var det halvpaus och jag pluggade inför en ks i indek. Däremot så läste jag en hel del i boken "Att genomföra examensarbete". Jag skrev dessutom färdigt listan med verktyg som skulle/har utvärderats.

## 2018-04-25

Idag var en produktiv dag. Jag har beskrivit 12 olika verktyg djupgående. Jag har beskrivit vad de gör och hur det relaterar till mitt arbete.

Jag har också skrivit en utförlig förklaring för hur det aldrig kan fungera med verktyg som gör: JSON -> JSON Schema

Jag gör det genom att visa en JSON-fil och visar hur det kan beskrivas med 4 helt olika JSON Scheman och att det bara är "the tip of the iceberg"

## 2018-04-26

Idag blev jag färdig med att djupgående utvärdera, förstå, analysera och förklara ALLA kända implementationer som implementerar något i närheten av vad jag gör.

## 2018-04-27

Idag började jag beskriva systemet i helhet.

## 2018-05-02

Idag skrev jag en stor del om arbetet. Jag förklarade hur JSON Scheman genererades. Dessutom skrev jag färdigt metoddelen, där jag lade till vad jag "faktiskt ska göra".

## 2018-05-03

Idag skrev jag väldigt mycket om själva arbetet. Jag kommer behöva åka till jobbet och ta några screenshots och kolla på lite kod (för att dubbelkolla implementationen). Dataflödet och systemet i helhet är beskrivet. Hur JSON Scheman parsas är beskrivet. Hur Schemat struktureras är beskrivet.

## 2018-05-04

Idag skrev jag en hel del om hur andra gjort GUIn och hur mitt förhåller sig till deras. Jag har kvar att skriva om specifika detaljer i min implementation men sen så är kapitel **4. Arbete** färdigskrivet och då är det bara diskussion och lite mer i introduktion kvar. Jag tog screenshots idag och lite sånt också.

## 2018-05-07

Idag skrev jag väldigt väldigt mycket om Arbetet. Jag är nästan färdig med kapitlet. Efter det har jag bara diskussionskapitlet kvar innan jag ska korrläsa och fixa till allt.

## 2018-05-08

Idag blev jag färdig med kapitlet om Arbetet (Resultat) woop woop 🎊 🎈 🎉 🕺 💪

Nu är det bara Diskussion kvar och allmänt fixande

## 2018-05-09

Idag var en ledig dag för jag pluggade inför en kontrollskrivning.

## 2018-05-10

Idag skrev jag större delen av `Diskussion, Sammanfattning och Fortsatt arbete`-kapitlet. Det är (typ) färdigt.

## 2018-05-11

Idag skrev jag abstract.

Jag fixade också en massa styling så att saker ska se bättre ut.

## 2018-05-14

Idag korrläste jag en massa och fixade jättemånga grejer.

*   Nu ser citeringar korrekta ut
*   Nu har jag en mer ordentlig introduktion
*   Nu ser all kod bättre ut. Flera kodexempel är flyttade till 2-kolumns-layouter för smaller footprint
*   JSON förklaras på ett bättre sätt.
*   osv...

## 2018-05-15

Idag har jag också korrläst och fixat en massa småsaker. Mycket börjar komma ihop nu. 2 kapitel är "klara". 3 kapitel måste korrläsas lite mer och 1 metodkapitel måste skrivas.

## 2018-05-15

Idag ändrade jag mycket och lade till mycket. Jag skrev bland annat ett metodikkapitel, och skrev om underkapitlet metod i introduktionen. Det mesta börjar komma ihop och jag förväntar mig att jag kan lämna in en första version nu på fredag.
