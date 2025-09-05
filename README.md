# OpenData Ajuntament de Rubí
Aquest repositori recopila i posa a disposició els conjunts de dades del nostre portal de [Dades Obertes](https://www.seu-e.cat/ca/web/rubi/dades-obertes) en formats CSV i JSON. Aquestes dades són fonamentals per promoure la transparència i l'accessibilitat de la informació pública.

A més dels conjunts de dades, en aquest repositori també es publicaran els arxius PBIX corresponents als quadres de comandament desenvolupats amb PowerBI. Aquests quadres de comandament són utilitzats en diversos portals, com ara el portal de [Transparència](https://www.seu-e.cat/ca/web/rubi/govern-obert-i-transparencia), i es basen en els mateixos conjunts de dades que es comparteixen aquí.

El nostre objectiu és proporcionar una plataforma centralitzada i accessible per a la distribució de dades obertes i eines d'anàlisi, fomentant així una cultura de transparència i responsabilitat.

---

## 📂 Estructura del repositori

- `datasets/`: Conté els conjunts de dades.
  - `csv/`: Conjunts de dades en format CSV.
  - `json/`: Conjunts de dades en format JSON.
- `pbix/`: Conté els arxius PBIX de quadres de comandament.
  - `Economia/`: Quadres de comandament relacionats amb la Economia pròpia de l'Ajuntament.
  - `Sector Públic/`: Quadres de comandament utilitzats en el portal de transparència sobre temes del sector públic.

---

## 🗂 Categories

Les categories utilitzades en aquest repositori són les mateixes que al portal de Dades Obertes, per garantir homogeneïtat:

- <img src="assets/icons/flask.svg" width="20" alt="Ciència i Tecnologia"> **Ciència i Tecnologia**: Dades relacionades amb investigacions científiques, desenvolupament tecnològic, innovació i aplicacions tecnològiques que impulsen el progrés en diversos camps.
- <img src="assets/icons/store.svg" width="20" alt="Comerç"> **Comerç**: Informació sobre activitats comercials, mercats, tendències de consum, i intercanvi de béns i serveis a nivell local i internacional.
- <img src="assets/icons/masks-theater.svg" width="20" alt="Cultura i oci"> **Cultura i oci**: Dades sobre activitats culturals, esdeveniments d'oci, patrimoni cultural, arts escèniques, música, literatura i altres formes d'expressió artística.
- <img src="assets/icons/users.svg" width="20" alt="Demografia"> **Demografia**: Estadístiques i anàlisis de població, incloent la distribució per edat, sexe, origen, densitat poblacional, i altres característiques sociodemogràfiques.
- <img src="assets/icons/chart-line.svg" width="20" alt="Economia"> **Economia**: Informació sobre l'activitat econòmica, incloent indicadors macroeconòmics, mercats financers, comerç exterior, i desenvolupament empresarial.
- <img src="assets/icons/graduation-cap.svg" width="20" alt="Educació"> **Educació**: Dades sobre el sistema educatiu, incloent el nombre d'estudiants, professors, institucions educatives, rendiment acadèmic, i polítiques educatives.
- <img src="assets/icons/bolt.svg" width="20" alt="Energia"> **Energia**: Informació sobre la producció, distribució i consum d'energia, així com dades sobre fonts d'energia renovable i no renovable, i eficiència energètica.
- <img src="assets/icons/futbol.svg" width="20" alt="Esport"> **Esport**: Estadístiques sobre la pràctica esportiva, competicions, instal·lacions esportives, i promoció de l'activitat física i l'esport a nivell local i nacional.
- <img src="assets/icons/house.svg" width="20" alt="Habitatge"> **Habitatge**: Dades sobre el mercat immobiliari, preus de compra i lloguer, accessibilitat a l'habitatge, i polítiques d'habitatge.
- <img src="assets/icons/coins.svg" width="20" alt="Hisenda"> **Hisenda**: Informació sobre finances públiques, incloent ingressos i despeses de l'administració, gestió del deute, i polítiques fiscals.
- <img src="assets/icons/industry.svg" width="20" alt="Indústria"> **Indústria**: Dades relatives al sector industrial, incloent producció, innovació, ocupació industrial, i desenvolupament tecnològic en diversos sectors.
- <img src="assets/icons/scale-balanced.svg" width="20" alt="Legislació i justícia"> **Legislació i justícia**: Informació sobre el sistema legal i judicial, incloent lleis, regulacions, procediments judicials, i estadístiques sobre l'administració de justícia.
- <img src="assets/icons/leaf.svg" width="20" alt="Medi Ambient"> **Medi Ambient**: Dades sobre la conservació i protecció del medi ambient, incloent qualitat de l'aire i l'aigua, biodiversitat, canvi climàtic, i polítiques ambientals.
- <img src="assets/icons/tractor.svg" width="20" alt="Medi Rural i Pesca"> **Medi Rural i Pesca**: Informació sobre activitats agràries, desenvolupament rural, pesca, i la gestió sostenible dels recursos naturals en àrees rurals.
- <img src="assets/icons/heart-pulse.svg" width="20" alt="Salut"> **Salut**: Estadístiques sanitàries, informació sobre serveis de salut, indicadors de salut pública, recerca mèdica, i polítiques de salut.
- <img src="assets/icons/building-columns.svg" width="20" alt="Sector Públic"> **Sector Públic**: Dades sobre l'administració pública, serveis públics, empleats públics, transparència i eficàcia governamental.
- <img src="assets/icons/shield-halved.svg" width="20" alt="Seguretat"> **Seguretat**: Informació sobre seguretat ciutadana, estadístiques de criminalitat, serveis de seguretat i emergència, i polítiques de seguretat.
- <img src="assets/icons/people-group.svg" width="20" alt="Societat i benestar"> **Societat i benestar**: Dades sobre benestar social, serveis socials, igualtat, inclusió, qualitat de vida, i polítiques de suport a la ciutadania.
- <img src="assets/icons/bus.svg" width="20" alt="Transport"> **Transport**: Informació sobre sistemes de transport, infraestructura de transport, mobilitat, i polítiques de transport sostenible.
- <img src="assets/icons/briefcase.svg" width="20" alt="Treball"> **Treball**: Estadístiques sobre el mercat laboral, ocupació, desocupació, condicions laborals, i polítiques d'ocupació.
- <img src="assets/icons/umbrella-beach.svg" width="20" alt="Turisme"> **Turisme**: Dades sobre el sector turístic, incloent visitants, allotjaments, destinacions turístiques, i l'impacte econòmic del turisme.
- <img src="assets/icons/city.svg" width="20" alt="Urbanisme i infraestructures"> **Urbanisme i infraestructures**: Informació sobre planificació urbana, desenvolupament d'infraestructures, gestió del sòl, i polítiques d'urbanisme.

---

## Ús

Per accedir als conjunts de dades, navegueu a la carpeta `datasets` i seleccioneu el format desitjat (`csv` o `json`). Els arxius PBIX es troben a la carpeta `pbix`, classificats per categories.

---

## Llicència

Aquest repositori està sota la [Llicència CC BY-NC 4.0](LICENSE).

---

### Crèdits

Icones: [Font Awesome Free](https://fontawesome.com) – Icons © Fonticons, Inc. (CC BY 4.0).
