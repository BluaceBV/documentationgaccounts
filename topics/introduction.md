# Handleiding G-rekening

## Introductie

Voor het automatisch verwerken van het gebruik van een G-rekening voor leveranciers en klanten in Business Central zijn diverse instellingen nodig in combinatie met de G-Accounts extensie van Bluace BV.

Instellingen zoals:

*	GB-tussenrekeningen voor de verwerking inkoopfactuur en voor verkoopfactuur
*	De tussenrekeningen moet worden opgenomen In de leverancier- en klant boekingsgroepen
*	Bankrekening inrichten met (G-rekening) waarop klanten moeten betalen.
*	Transactiewijze Klant gekoppeld aan onze G-bankrekening
*	Per leverancier opgave van de leverancier bankrekeningen, de standaard en zijn G-rekeningnummer.
*	Per leverancier opgave van het percentage wat op de leveranciers G-rekening moet worden verwerkt, de transactiewijze en het G-bankrekeningnummer.
*	Per klant via de actie G-rekening een opgave van percentage, transactiewijze en ons G-bankrekeningnummer.

Hier volgt een beschrijving van de werking van de extensie op basis van een betaling van een deel op de G-rekening van de leverancier.

De oplossing is gekoppeld aan de standaard inkoopfacturatie en verkoopfacturatie. Bij de boeking van bijvoorbeeld een inkoopfactuur, wordt gecontroleerd of deze leverancier de G-rekening instellingen heeft ingeregeld. Als dit het geval is zal bij de boeking rekening worden gehouden met deze instellingen. Waarbij de originele inkoopfactuur/ leveranciersposten worden tegen geboekt. En het totaalfactuurbedrag van de leveranciersposten zal worden gesplitst in twee posten, op basis van de G-rekening instellingspercentage op de leverancierskaart. Er worden twee nieuwe leveranciersposten aangemaakt waarvan een deel wordt gekoppeld aan de reguliere leveranciersbankrekening en het andere deel aan de G-rekening (o.b.v. het percentage). De originele inkoopfactuur en de tegenboeking worden in dezelfde actie/boeking vereffend zodat hiervoor géén open posten blijven staan. 

[:arrow_left:](../README.md) [Back](../README.md)