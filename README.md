# Poděbradská radiotelegrafická stanice

Responzivní historická webová stránka o radiotelegrafické stanici v Poděbradech z 20. let 20. století.

## Obsah

Stránka představuje:

- historii výstavby stanice v poděbradských mokřinách,
- hlavní technické parametry,
- stavbu 150metrových anténních stožárů,
- vysílače Bethenod–Latour s výkonem až 100 kW,
- ochranu hlavní budovy proti povodním,
- dobové ovládací a vysílací sály,
- historický text doplněný o odkazy na původní zdroje.

## Spuštění

Projekt nevyžaduje instalaci žádných závislostí. Otevřete soubor `index.html` v internetovém prohlížeči.

Pro lokální náhled lze použít také jednoduchý webový server, například:

```text
python -m http.server 8000
```

Potom otevřete adresu `http://localhost:8000`.

## Struktura projektu

| Soubor | Popis |
| --- | --- |
| `index.html` | Kompletní stránka včetně CSS stylů v hlavičce |
| `budova.jpg` | Hlavní budova radiostanice |
| `stavba.jpg` | Stavba anténních stožárů |
| `vysilac.jpg` | Interiér vysílacího sálu |
| `ovladani.jpg` | Ovládací panely a měřicí přístroje |

## Vzhled a technologie

- moderní tmavý režim s retro vizuálními prvky,
- zlaté a oranžové akcenty,
- texturované boxy ve stylu zažloutlého papíru,
- CSS proměnné definované v `:root`,
- responzivní grid pro počítače, tablety i mobilní telefony,
- sémantické HTML prvky a alternativní texty obrázků.

## Historické zdroje

Historická sekce vychází z dobového textu **„Stavba radiotelegrafické stanice v Lázních Poděbradech“**.

- [Originální článek o radiostanici v Poděbradech](https://ok1frd.kd.cz/Podebrady.htm)
- [Zrcadlo zdroje na hornictvi.info](https://www.hornictvi.info/)

Historický obsah na stránce je zkrácený a jazykově upravený pro současné webové použití. Struktura stránky, popisky a současné webové zpracování byly vytvořeny s pomocí AI.