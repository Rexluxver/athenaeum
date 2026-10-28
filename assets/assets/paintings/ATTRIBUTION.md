# Background paintings

All images are photographic reproductions of two-dimensional paintings whose
creators died more than 100 years ago. Wikimedia Commons marks each file as
**Public domain** (checked Oct 12, 2026). Under US law (Bridgeman v. Corel)
faithful reproductions of public-domain 2D art add no new copyright. The files
were downloaded as 1280 px thumbnails and resized for the app.

| File | Painting | Artist | Date | Source |
|---|---|---|---|---|
| friedrich_wanderer.jpg | Wanderer above the Sea of Fog | Caspar David Friedrich (1774–1840) | c. 1817 | https://commons.wikimedia.org/wiki/File:Caspar_David_Friedrich_-_Wanderer_above_the_sea_of_fog.jpg |
| turner_fighting_temeraire.jpg | The Fighting Temeraire | J. M. W. Turner (1775–1851) | 1839 | https://commons.wikimedia.org/wiki/File:The_Fighting_Temeraire,_JMW_Turner,_National_Gallery.jpg |
| constable_hay_wain.jpg | The Hay Wain | John Constable (1776–1837) | 1821 | https://commons.wikimedia.org/wiki/File:John_Constable_The_Hay_Wain.jpg |
| friedrich_monk_by_the_sea.jpg | The Monk by the Sea | Caspar David Friedrich (1774–1840) | 1808–1810 | https://commons.wikimedia.org/wiki/File:Caspar_David_Friedrich_-_Der_M%C3%B6nch_am_Meer_-_Google_Art_Project.jpg |
| constable_wivenhoe_park.jpg | Wivenhoe Park, Essex | John Constable (1776–1837) | 1816 | https://commons.wikimedia.org/wiki/File:John_Constable_-_Wivenhoe_Park,_Essex_-_Google_Art_Project.jpg (Public domain; original: National Gallery of Art, Washington, Widener Collection; checked Oct 14, 2026) |
| monet_poppy_field.jpg | Poppy Field (Coquelicots, La promenade), Argenteuil | Claude Monet (1840–1926) | 1873 | https://commons.wikimedia.org/wiki/File:Claude_Monet_-_Poppy_Field_-_Google_Art_Project.jpg (Public domain, PD-Art; original: Musée d'Orsay, Paris, RF 1676; Google Art Project reproduction; downloaded as a 1920 px thumbnail; checked Oct 14, 2026). Used for the Classroom scene. |

## Classroom desk

assets/scene/classroom/desk.png is our own work (CC0), rendered procedurally by
tool/mockups/make_desk.py (no third-party imagery).

## Word-game backdrops (added Oct 19, 2026)

Same basis: Wikimedia Commons marks each file **Public domain** (PD-Art; every
artist died before 1956, in fact before 1925). Checked Oct 19, 2026 via the
Commons API (LicenseShortName = "Public domain"); downloaded as 1920 px
thumbnails and resized to 1600 px on the long side.

| File | Painting | Artist | Date | Used for | Source |
|---|---|---|---|---|---|
| fragonard_the_reader.jpg | Young Girl Reading | Jean-Honoré Fragonard (1732–1806) | c. 1769 | Wordle-style | https://commons.wikimedia.org/wiki/File:Fragonard,_The_Reader.jpg (National Gallery of Art, Washington) |
| seurat_grande_jatte.jpg | A Sunday on La Grande Jatte | Georges Seurat (1859–1891) | 1884–1886 | Connections | https://commons.wikimedia.org/wiki/File:A_Sunday_on_La_Grande_Jatte,_Georges_Seurat,_1884.jpg (Art Institute of Chicago) |
| renoir_moulin_de_la_galette.jpg | Bal du moulin de la Galette | Pierre-Auguste Renoir (1841–1919) | 1876 | (was Crossword; HOLD, kept bundled but unused until re-verified) | https://commons.wikimedia.org/wiki/File:Pierre-Auguste_Renoir,_Le_Moulin_de_la_Galette.jpg (Musée d'Orsay) |
| renoir_boating_party.jpg | Luncheon of the Boating Party | Pierre-Auguste Renoir (1841–1919) | 1880–1881 | Fill in the blank | https://commons.wikimedia.org/wiki/File:Pierre-Auguste_Renoir_-_Luncheon_of_the_Boating_Party_-_Google_Art_Project.jpg (Phillips Collection) |
| caillebotte_paris_street.jpg | Paris Street; Rainy Day | Gustave Caillebotte (1848–1894) | 1877 | Matching | https://commons.wikimedia.org/wiki/File:Gustave_Caillebotte_-_Paris_Street;_Rainy_Day_-_Google_Art_Project.jpg (Art Institute of Chicago) |

## Seasonal Classroom scenes (added Oct 20, 2026)

The Classroom painting changes with the season (lib/config/seasons.dart);
summer keeps the Monet *Poppy Field* above. A gentle snowfall is drawn on top
in code (no image) from December 1 to January 6. Same basis: Wikimedia
Commons marks each painting **Public domain** (PD-Art; Claude Monet died in
1926). Checked Oct 20, 2026 via the Commons API; resized to at most 1600 px.

| File | Painting | Artist | Date | Season | Source |
|---|---|---|---|---|---|
| monet_the_magpie.jpg | The Magpie (La Pie) | Claude Monet (1840–1926) | 1868–1869 | Winter | https://commons.wikimedia.org/wiki/File:Claude_Monet_-_The_Magpie_-_Google_Art_Project.jpg (Public domain; original: Musée d'Orsay, Paris; Google Art Project reproduction) |
| monet_springtime.jpg | Springtime | Claude Monet (1840–1926) | 1872 | Spring | https://commons.wikimedia.org/wiki/File:Claude_Monet_-_Springtime_-_Google_Art_Project.jpg (Public domain; original: Walters Art Museum, Baltimore; Google Art Project reproduction) |
| monet_poppy_field.jpg | Poppy Field, Argenteuil | Claude Monet (1840–1926) | 1873 | Summer | see above |
| monet_autumn_argenteuil.jpg | Autumn Effect at Argenteuil | Claude Monet (1840–1926) | 1873 | Autumn | https://commons.wikimedia.org/wiki/File:Claude_Monet_027.jpg (Public domain, PD-Art; original: The Courtauld, London) |

Fragonard: title and date corrected Oct 27, 2026 against NGA open data
(objectid 46303, accession 1961.16.1, "Young Girl Reading", c. 1769,
openaccess=1; museum spelling "Jean Honoré Fragonard"). The file name is
unchanged.

## A Round of Five backdrops and the Crossword swap (added Oct 27, 2026)

These eight files come straight from the museums' own open-access programmes
(not Wikimedia Commons). Each was a single download of one known object,
re-encoded here as sRGB JPEG q78, progressive, 1290 px on the long edge; no
crop (the crop is an `Alignment` in code). Cleared in
studio-plan/games/PAINTING-RIGHTS.md. On cards and shared images the credit
reads "Public domain" (never "CC0" or "©"); CC0 appears only here and on the
Credits screen.

| File | Full credit line | Licence check (Oct 27, 2026) | Used for |
|---|---|---|---|
| lepicie_woman_reading.jpg | Nicolas-Bernard Lépicié, *Woman Reading*, 1769 · Cleveland Museum of Art, CC0 · clevelandart.org/art/1964.288 | Cleveland Open Access API `share_license_status: CC0`; source `1964.288_print.jpg` | The Missing Word |
| zoffany_dutton_family.jpg | Johann Zoffany, *The Dutton Family in the Drawing Room of Sherborne Park, Gloucestershire*, c. 1772 · Cleveland Museum of Art, CC0 · clevelandart.org/art/2023.122 | API CC0; `2023.122_print.jpg` | Who Spoke? |
| gifford_autumn_wood_path.jpg | Sanford Robinson Gifford, *Autumn, a Wood Path*, 1876 · Cleveland Museum of Art, CC0 · clevelandart.org/art/1922.220 | API CC0; `1922.220_print.jpg` | In Order |
| collier_vanitas_still_life.jpg | Edwaert Collier, *Vanitas Still Life*, 1662 · The Metropolitan Museum of Art, Purchase, 1871, accession 71.19 · Public domain (Met Open Access, CC0) · metmuseum.org/art/collection/search/435918 | Met Collection API `isPublicDomain: true`; `DP146494.jpg` (3805×3153) | Word & Sense |
| corot_pond_ville_davray.jpg | Camille Corot (Cleveland: "Jean Baptiste Camille Corot"), *Pond at Ville-d'Avray*, late 1860s · Cleveland Museum of Art, CC0 · clevelandart.org/art/1944.80 | API CC0; `1944.80_print.jpg` | Odd One Out |
| panini_pantheon_interior.jpg | Giovanni Paolo Panini, *Interior of the Pantheon, Rome*, 1747 · Cleveland Museum of Art, CC0 · clevelandart.org/art/1974.39 | API CC0; `1974.39_print.jpg` | True to the Text? |
| church_twilight_wilderness.jpg | Frederic Edwin Church, *Twilight in the Wilderness*, 1860 · Cleveland Museum of Art, CC0 · clevelandart.org/art/1965.233 | API CC0; `1965.233_print.jpg` | Round results and every share card |
| renoir_oarsmen_chatou.jpg | Pierre-Auguste Renoir, *Oarsmen at Chatou*, 1879 · National Gallery of Art, Washington, Gift of Sam A. Lewisohn, 1951.5.2 (museum record: "Auguste Renoir") · Public domain (NGA Open Access, CC0) · objectid 39759 | NGA open data `published_images.csv`: uuid 1153f2b7-bfe6-4159-8ca4-211ce86564b1, objectid 39759, openaccess=1, 12867×10469; `objects.csv`: 39759, 1951.5.2, "Oarsmen at Chatou", 1879. Downloaded via IIIF `/full/1290,/0/default.jpg` | Crossword (crop `Alignment(-0.6, 0)`, top scrim 0.80) |

Short credit on share cards (Solon's format), e.g.
"Frederic Edwin Church, Twilight in the Wilderness (1860) · Cleveland Museum
of Art · Public domain". Collier is printed with no death year.

## Games UI (added Oct 27, 2026)

- assets/games/badges/: the seven Parliament badges, our own original vector
  designs (studio-plan/games/art/badge-*.svg), drawn to PNG by
  tool/games/make_badges.py. CC0.
- assets/games/ui/parchment_tile.webp: procedural paper texture by
  tool/games/make_parchment.py. CC0.
