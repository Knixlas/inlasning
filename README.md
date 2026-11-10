# Inläsningen

Granskningssida för ljudboken *Jag springer inte, jag flyr* (uppläst av Martin Forsström).

- `index.html` — hela sidan, en fil. Samma fil ligger på `https://sviden.se/inlasning/` (One.com) och publiceras härifrån via GitHub Pages på `https://knixlas.github.io/inlasning/`.
- Data och ljud: Supabase-projektet Trixa, schemat `inlasning` och bucketen `inlasning-ljud`. All åtkomst går via edge-funktionen `inlasning`, skyddad med två ord (inläsare / lyssnare), inga konton.
- Rättigheter: inläsarordet får ladda upp och bocka av kommentarer. Båda orden får lyssna, kommentera och sätta status.

Ändras sidan här måste den också laddas upp till One.com om sviden.se-adressen ska följa med.
