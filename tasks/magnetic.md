# Magnetiske Bolde
I denne opgave skal du skrive logik som får et sæt af magnetiske objekter til at tiltrækkes af hinanden. Du kan starte i scenen `Magnetism`, som er klar til start.

I scenen er der placeret en række bolde. Nogle af dem er lavet af plastik (rød) og de andre af et magnetisk (blank metalisk) materiale. Din opgave går på at få alle de magnetiske bolde til at blive tiltrukket ind mod center-positionen for alle boldene (billedet nedenfor viser en grov skitse, hvor den blå bold antages at være midtpunkt). Boldene kan bevæge sig med konstant hastighed, da det ikke nødvendigvis behøves være en realistisk simulation.

<img src="images/magnetism.png" style="width: 80%; display: block; margin: auto;" />

Alle de magnetiske bolde har tag'et `Magnetic`.

## Opgaverne

1. Implementer en løsning til ovenstående problemstilling.
2. På samplesheet'et finder du eksempler på hvordan man kan parallelisere opgaver i det sprog du arbejder i. Implementer en løsning til problemet, som udregner alle boldenes nye positioner parallelt og tilsidst opdaterer alle boldene sekventielt på Main-tråden.