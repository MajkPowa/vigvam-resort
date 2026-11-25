# HorizonX · pohyb pro Vigvam

Rozbor veřejných ukázek z 25. listopadu 2026. Tři oficiální videoukázky mají 1 920 × 1 080 px a 30 snímků za sekundu. Časy níže označují polohu v nahrávce. Vybrané přechody jsem porovnal po 0,2 s. Z nahrávky nelze určit přesnou křivku zrychlení ani rychlost vstupu uživatele. Hodnoty v části „Použití ve Vigvamu“ jsou návrhem pro vlastní komponenty.

## Altura Coastal Residences

**Pozorování.** V úvodním záběru zakrývá skutečný obrys střechy spodní část písma. Při posunu celé úvodní plochy vyjede zdola čelní pohled do domu. V čase 3,8 s je nad vstupem ostrý titulek, ve 4,0 s slábne a ve 4,2 s je pryč. Mezi 4,2 a 4,8 s se dveřní rámy zvětšují a mizí za okraji obrazu. V 5,0 s se vlevo nad obývacím pokojem objevuje měkký nový titulek, v 5,2 s je ostrý. Další místnost má titulek na opačné straně. Autor uvádí 421 zdrojových snímků, osm zastávek a posun na sousední zastávku kolečkem, swipem či šipkou. Dvanáctisekundový sestřih končí u ložnice. [Popis autora](https://horizonx.so/explore/altura-coastal-residences) · [Průchod dveřmi ve videu](https://cdn.horizonx.so/altura-coastal-residences/altura-coastal-residences-scroll-detail-v1.mp4#t=3.8,5.2)

**Použití ve Vigvamu.** Slovo za střechou lze vytvořit dvěma přesně zarovnanými vrstvami jedné fotografie a maskou skutečného obrysu vigvamu. V galerii soudku jedno stisknutí vybere další snímek. Starý popisek vybledne během prvních 140 ms, dvě fotografie se prolnou během 560 ms a nový popisek se objeví v závěrečných 180 ms. Záběr z exteriéru a záběr z interiéru musí mít vlastní popisy. Průjezd dveřmi vyžaduje souvislou sérii z jednoho prostoru. Na telefonu zůstane svislé posouvání stránky volné.

## Alder & Stone

**Pozorování.** Mezi 3 a 5 s kamera přejde od celku k velmi blízkému pohledu na bodový model. V 5,2 s jsou jednotlivé body podlaží zřetelné. Kolem 5,4–5,8 s mizí zadní část titulku, poté přední. Ze světlého podkladu se v 6,0–6,6 s vynoří malý celek města. Horní navigace si přitom drží pozici. Samostatnou pozdější scénu s hotspoty popisuje autor. Galerie ukazuje také horizontální pás projektů a diagram rozložený do několika částí. [Popis autora](https://horizonx.so/explore/alder-stone) · [Průlet ve videu](https://cdn.horizonx.so/alder-stone/alder-stone-feature-20261016.mp4#t=3,7) · [Diagram fází](https://cdn.horizonx.so/alder-stone/alder-stone-process.webp)

**Použití ve Vigvamu.** Po výběru objektu v mapě nastaví kamera nový cíl na danou stavbu, plynule ji přiblíží a zastaví. Pro vlastní přechod navrhujeme 900 ms a dojezd bez překmitu `cubic-bezier(.22,1,.36,1)`. Popis a odkaz na detail mají být dostupné hned po výběru. Tažení přeruší pohyb kamery a předá ji návštěvníkovi. Tlačítko pro celek vrátí mapu do výchozího pohledu.

## Crest Water Hero

**Pozorování.** Horizont, kruh za předmětem i text drží polohu. Během 1,4–3,0 s se napravo od karty zvýrazní několik eliptických vln, zatímco se na kartě mění úhel hrany a světelný pruh. Odraz se mění spolu s lokálním zvlněním. Pohyb či kliknutí nad vodou a naklánění karty směrem k ukazateli popisuje autor. Původ jednotlivých vln nelze ze samotného záznamu přiřadit konkrétním kliknutím. [Popis autora](https://horizonx.so/explore/crest-water-hero) · [Hladina ve videu](https://cdn.horizonx.so/crest-water-hero/crest-water-hero-hero.mp4#t=1.2,3.4)

**Použití ve Vigvamu.** Pro fotografii s dobře viditelným jezírkem vymezit masku podle břehu. Jemný podnět myši může vyslat dvě rozšiřující se elipsy s dozněním do 1 100 ms. Vlny se omezí na vodu. Stavba, linie břehu, nadpis a rezervační panel poskytnou oku pevný bod. Efekt se hodí k záběru, pro který byla maska vytvořena.

## Liquid Glass

**Pozorování.** Veřejná galerie obsahuje tři statické kompozice. Denní agenda má datum a kruhový ukazatel vlevo, seznam návazných událostí vpravo. Níže leží pole a přepínač. Na fotografii prosvítá obloha, na tmavém pozadí odděluje jednotlivé vrstvy světlejší tenká hrana. Detail přepínače ukazuje světlý kruh na tmavé ploše. Galerie dokládá vzhled stavů. Čas přechodu ani odezvu na dotyk z ní změřit nelze. [Popis autora](https://horizonx.so/explore/liquid-glass) · [Varianta na obloze](https://cdn.horizonx.so/liquid-glass/gallery1.webp) · [Varianta na tmavé ploše](https://cdn.horizonx.so/liquid-glass/gallery3.webp)

**Použití ve Vigvamu.** Lehce průsvitný může být okraj panelu nad fotografií. Samotné datum, počty hostů a mřížka kalendáře potřebují stálý kontrast. Po aktivaci pole se může kalendář odkrýt během 200 ms posunem o 6 px a zvýšením krytí. Klávesnicí lze okamžitě vybrat den. Zavření vrátí fokus do pole a zachová příjezd i odjezd.

## Omezený pohyb

Při `prefers-reduced-motion: reduce` se fotografie a popisek přepnou přímo. Mapa skočí na vybraný cíl nebo nabídne seznam míst se stejnými odkazy. Hladina zůstane fotografií a kalendář se otevře ihned. Ověřit volbu klávesnicí, dotykem a při přepnutí systémové předvolby během návštěvy. Rezervace je přístupná od prvního vykreslení.
