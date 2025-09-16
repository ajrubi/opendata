# OpenData Ajuntament de Rubí

Aquest repositori recopila i posa a disposició els conjunts de dades del nostre portal de [Dades Obertes](https://www.seu-e.cat/ca/web/rubi/dades-obertes) en formats **CSV** i **JSON**.  
Aquestes dades són fonamentals per promoure la transparència i l'accessibilitat de la informació pública.

A més dels conjunts de dades, en aquest repositori també es publicaran els arxius **PBIX** corresponents als quadres de comandament desenvolupats amb PowerBI.  
Aquests quadres de comandament són utilitzats en diversos portals, com ara el portal de [Transparència](https://www.seu-e.cat/ca/web/rubi/govern-obert-i-transparencia), i es basen en els mateixos conjunts de dades que es comparteixen aquí.

El nostre objectiu és proporcionar una plataforma centralitzada i accessible per a la distribució de dades obertes i eines d'anàlisi, fomentant així una cultura de transparència i responsabilitat.

---

## 📂 Estructura del repositori

- `datasets/`
  - `csv/<categoria>/`: Conjunts de dades en format CSV classificats per categoria.
  - `json/<categoria>/`: Conjunts de dades en format JSON classificats per categoria.
- `pbix/<categoria>/`: Arxius PBIX de quadres de comandament classificats per categoria.

---

## 🗂 Categories

Les categories utilitzades en aquest repositori són les mateixes que al portal de Dades Obertes, per garantir homogeneïtat:

- ![light](assets/icons/flask-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/flask-solid-full-dark.svg#gh-dark-mode-only) **[Ciència i Tecnologia](datasets/csv/ciencia-i-tecnologia/)**: Dades relacionades amb investigacions científiques, desenvolupament tecnològic, innovació i aplicacions tecnològiques que impulsen el progrés en diversos camps.
- ![light](assets/icons/gift-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/gift-solid-full-dark.svg#gh-dark-mode-only) **[Comerç](datasets/csv/comerc/)**: Informació sobre activitats comercials, mercats, tendències de consum, i intercanvi de béns i serveis a nivell local i internacional.
- ![light](assets/icons/music-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/music-solid-full-dark.svg#gh-dark-mode-only) **[Cultura i oci](datasets/csv/cultura-i-oci/)**: Dades sobre activitats culturals, esdeveniments d'oci, patrimoni cultural, arts escèniques, música, literatura i altres formes d'expressió artística.
- ![light](assets/icons/chart-bar-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/chart-bar-solid-full-dark.svg#gh-dark-mode-only) **[Demografia](datasets/csv/demografia/)**: Estadístiques i anàlisis de població, incloent la distribució per edat, sexe, origen, densitat poblacional, i altres característiques sociodemogràfiques.
- ![light](assets/icons/euro-sign-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/euro-sign-solid-full-dark.svg#gh-dark-mode-only) **[Economia](datasets/csv/economia/)**: Informació sobre l'activitat econòmica, incloent indicadors macroeconòmics, mercats financers, comerç exterior, i desenvolupament empresarial.
- ![light](assets/icons/graduation-cap-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/graduation-cap-solid-full-dark.svg#gh-dark-mode-only) **[Educació](datasets/csv/educacio/)**: Dades sobre el sistema educatiu, incloent el nombre d'estudiants, professors, institucions educatives, rendiment acadèmic, i polítiques educatives.
- ![light](assets/icons/bolt-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/bolt-solid-full-dark.svg#gh-dark-mode-only) **[Energia](datasets/csv/energia/)**: Informació sobre la producció, distribució i consum d'energia, així com dades sobre fonts d'energia renovable i no renovable, i eficiència energètica.
- ![light](assets/icons/basketball-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/basketball-solid-full-dark.svg#gh-dark-mode-only) **[Esport](datasets/csv/esport/)**: Estadístiques sobre la pràctica esportiva, competicions, instal·lacions esportives, i promoció de l'activitat física i l'esport a nivell local i nacional.
- ![light](assets/icons/house-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/house-solid-full-dark.svg#gh-dark-mode-only) **[Habitatge](datasets/csv/habitatge/)**: Dades sobre el mercat immobiliari, preus de compra i lloguer, accessibilitat a l'habitatge, i polítiques d'habitatge.
- ![light](assets/icons/money-bill-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/money-bill-solid-full-dark.svg#gh-dark-mode-only) **[Hisenda](datasets/csv/hisenda/)**: Informació sobre finances públiques, incloent ingressos i despeses de l'administració, gestió del deute, i polítiques fiscals.
- ![light](assets/icons/industry-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/industry-solid-full-dark.svg#gh-dark-mode-only) **[Indústria](datasets/csv/industria/)**: Dades relatives al sector industrial, incloent producció, innovació, ocupació industrial, i desenvolupament tecnològic en diversos sectors.
- ![light](assets/icons/scale-balanced-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/scale-balanced-solid-full-dark.svg#gh-dark-mode-only) **Legislació i justícia](datasets/csv/legislacio-i-justicia/)**: Informació sobre el sistema legal i judicial, incloent lleis, regulacions, procediments judicials, i estadístiques sobre l'administració de justícia.
- ![light](assets/icons/leaf-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/leaf-solid-full-dark.svg#gh-dark-mode-only) **[Medi Ambient](datasets/csv/medi-ambient/)**: Dades sobre la conservació i protecció del medi ambient, incloent qualitat de l'aire i l'aigua, biodiversitat, canvi climàtic, i polítiques ambientals.
- ![light](assets/icons/paw-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/paw-solid-full-dark.svg#gh-dark-mode-only) **[Medi Rural i Pesca](datasets/csv/medi-rural-i-pesca/)**: Informació sobre activitats agràries, desenvolupament rural, pesca, i la gestió sostenible dels recursos naturals en àrees rurals.
- ![light](assets/icons/heart-pulse-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/heart-pulse-solid-full-dark.svg#gh-dark-mode-only) **[Salut](datasets/csv/salut/)**: Estadístiques sanitàries, informació sobre serveis de salut, indicadors de salut pública, recerca mèdica, i polítiques de salut.
- ![light](assets/icons/building-columns-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/building-columns-solid-full-dark.svg#gh-dark-mode-only) **[Sector Públic](datasets/csv/sector-public/)**: Dades sobre l'administració pública, serveis públics, empleats públics, transparència i eficàcia governamental.
- ![light](assets/icons/shield-halved-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/shield-halved-solid-full-dark.svg#gh-dark-mode-only) **[Seguretat](datasets/csv/seguretat/)**: Informació sobre seguretat ciutadana, estadístiques de criminalitat, serveis de seguretat i emergència, i polítiques de seguretat.
- ![light](assets/icons/users-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/users-solid-full-dark.svg#gh-dark-mode-only) **[Societat i benestar](datasets/csv/societat-i-benestar/)**: Dades sobre benestar social, serveis socials, igualtat, inclusió, qualitat de vida, i polítiques de suport a la ciutadania.
- ![light](assets/icons/bus-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/bus-solid-full-dark.svg#gh-dark-mode-only) **[Transport](datasets/csv/transport/)**: Informació sobre sistemes de transport, infraestructura de transport, mobilitat, i polítiques de transport sostenible.
- ![light](assets/icons/wrench-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/wrench-solid-full-dark.svg#gh-dark-mode-only) **[Treball](datasets/csv/treball/)**: Estadístiques sobre el mercat laboral, ocupació, desocupació, condicions laborals, i polítiques d'ocupació.
- ![light](assets/icons/hotel-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/hotel-solid-full-dark.svg#gh-dark-mode-only) **[Turisme](datasets/csv/turisme/)**: Dades sobre el sector turístic, incloent visitants, allotjaments, destinacions turístiques, i l'impacte econòmic del turisme.
- ![light](assets/icons/road-solid-full-light.svg#gh-light-mode-only) ![dark](assets/icons/road-solid-full-dark.svg#gh-dark-mode-only) **[Urbanisme i infraestructures](datasets/csv/urbanisme-i-infraestructures/)**: Informació sobre planificació urbana, desenvolupament d'infraestructures, gestió del sòl, i polítiques d'urbanisme.

---

## Ús

Per accedir als conjunts de dades, navegueu a la carpeta `datasets` i seleccioneu el format desitjat (`csv` o `json`). Els arxius PBIX es troben a la carpeta `pbix`, classificats per categories.

---

## 📖 Llicència

Aquest repositori està sota la [Llicència CC BY-NC 4.0](LICENSE).

---

### Crèdits

Icones: [Font Awesome Free](https://fontawesome.com) – Icons © Fonticons, Inc. (CC BY 4.0).