# Klikklak

Een enkelvoudig HTML-bestand dat willekeurige Nederlandse lettergreepwoorden genereert voor beginnende lezers. Open `klikklak.html` in een browser — geen installatie of internetverbinding vereist.

## Hoe het werkt

Drie kaarten tonen een willekeurige combinatie van lettergrepen:

| Positie | Label | Beschrijving |
|---|---|---|
| **Begin** (blauw) | Voorkant | Openende medeklinker of medeklinkercluster (bijv. *bl*, *dr*, *st*) |
| **Midden** (oranje) | Midden | Klinker of klinkercombinatie (bijv. *aa*, *oe*, *ij*) |
| **Eind** (groen) | Einde | Sluitende medeklinker of cluster (bijv. *n*, *rk*, *cht*) |

Tik op **Nieuw woord** om een nieuwe willekeurige combinatie te genereren.

## Een lettergreep vergrendelen

Elke kaart heeft een vergrendelknop. Wanneer vergrendeld, blijft die positie vast terwijl de andere twee bij de volgende tik opnieuw worden geschud. Zo kun je één lettergreep in veel verschillende woorden oefenen. Alle drie de kaarten kunnen tegelijk vergrendeld worden.

## De lettergroep aanpassen

Tik op de knop **Letters instellen** (rechtsboven) om de instellingen te openen. Elke positie toont alle beschikbare lettergrepen als aanklikbare labels — gemarkeerde labels zijn actief. Tik op een label om het aan of uit te zetten. Per positie moet minstens één label actief blijven. Je selectie wordt automatisch opgeslagen in de browser (`localStorage`) en blijft bewaard tussen sessies.

### Standaardwaarden

| Positie | Standaard actieve lettergrepen |
|---|---|
| Begin | m, r, v |
| Midden | aa, i, o, oo |
| Eind | k, n, s |

## Broncode & licentie

- Broncode: https://github.com/sneyders/klikklak
- Licentie: GNU General Public License v3.0
