# Titkos Mikulás sorsoló

Egyszerű, egyetlen HTML-fájlból álló Titkos Mikulás sorsoló. Nincs szerver, nincs adatbázis – GitHub Pages-en ingyen fut.

## Használat

1. Hozz létre háztartásokat, és add hozzá a neveket.
2. Kattints a **Sorsolás indítása** gombra. Senki sem húzhatja saját magát vagy a saját háztartásából valakit.
3. Mindenki neve mellett van egy **Link másolása** gomb – küldd el a linket az adott személynek.
4. A link megnyitásakor a címzett látja, kit húzott. A linkből magából nem olvasható ki a név.

Az adatok csak a szervező böngészőjében tárolódnak (localStorage). Új sorsolás után a korábbi linkek érvénytelenek.

## Közzététel GitHub Pages-en

1. Hozz létre egy új repót a GitHubon (pl. `titkos-mikulas`), és töltsd fel az `index.html`-t.
2. A repóban: **Settings → Pages → Source: Deploy from a branch**, ág: `main`, mappa: `/ (root)`.
3. Pár perc múlva elérhető: `https://szabovin.github.io/titkos-mikulas/`
