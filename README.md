# Cau d'Igualada — contingut de l'antic web

Aquest directori recull el contingut del web de l'**Agrupament Escolta i Guia Jaume Caresmar i Mª Antònia Salvà** d'Igualada (www.cauigualada.cat), extret de la seva base de dades i convertit a fitxers Markdown.

## Com està organitzat

- **[Sobre nosaltres](sobre-nosaltres/)** — Història de l'escoltisme (mundial, a Catalunya i a Igualada), Baden-Powell, Minyons Escoltes i Guies de Catalunya i l'agrupament.
- **[Unitats](unitats/)** — Pàgines de cada branca i unitat. Els fitxers comuns a tota una branca són a l'arrel de la carpeta (prefix `cill-`, `llid-`, `ring-`, `pic-`, `trucs-`); cada unitat té la seva carpeta, amb el text de la promesa (si n'hi ha) i les cròniques ordenades per curs.
- **[El Cauet](el-cauet/)** — La revista de l'agrupament i l'enllaç a les edicions publicades.
- **[Fem 60 anys](fem-60-anys/)** — Actes del 60è aniversari de l'agrupament (curs 2012-2013).
- **[Igualada x Igualada](igualada-x-igualada/)** — Activitats de servei: recollides d'aliments, Banc de Queviures, desnonaments.
- **[Notícies](noticies/)** — Totes les notícies del web, en un fitxer per curs.
- **[Avís legal i crèdits](avis-legal-i-credits/)** — Peu de pàgina del web.

### Convencions

- Cada fitxer comença amb una capçalera de metadades (entre línies `---`): títol, secció, branca i unitat, curs, dates de creació i d'última actualització, si estava publicat, l'adreça original al web i l'identificador a la base de dades.
- Quan una carpeta correspon a una pàgina amb subpàgines, la pàgina principal és el fitxer `README.md` de la carpeta.
- Els prefixos numèrics (`01-`, `02-`…) només indiquen l'ordre de lectura.
- Prefixos de branca a `unitats/`: `cill-` Castors i Llúdrigues, `llid-` Llops i Daines, `ring-` Ràngers i Noies Guia, `pic-` Pioners i Caravel·les, `trucs-` Trucs.
- A la carpeta `unitats/trucs/`, els fitxers porten el nom de la unitat de Trucs quan apareix al text (`lilium-`, `karakorum-`, `kraken-`; `2n-any-` per a la unitat de Trucs de segon any del curs 2013-2014).
- Les pàgines que es repetien gairebé idèntiques a diverses unitats d'una mateixa branca s'han fusionat en un sol fitxer a l'arrel d'`unitats/`. La capçalera indica de quines unitats provenen.

### Què s'ha deixat fora

- Les imatges: la base de dades només en conté les rutes, no els fitxers. També s'han descartat les pàgines i notícies que eren bàsicament fotografies (àlbums, cartells, felicitacions).
- Les pàgines no publicades sense contingut (la secció de l'Associació de Pares, Mares i Antics Escoltes, que només tenia textos provisionals). Les pàgines no publicades amb contingut rellevant s'han conservat i porten `publicat: false`.
- Les adreces de correu electrònic s'han ocultat: la part anterior a l'arrova és substituïda per 8 asteriscs i es conserva el domini.

### Notícies

La base de dades no conserva la data ni la categoria de cada notícia. El curs al qual s'assigna cada notícia s'ha estimat a partir de l'ordre de publicació i del contingut, i dins de cada fitxer les notícies apareixen en ordre de publicació.

## Glossari

- **Cau / Agrupament**: termes gairebé sinònims per referir-se a l'agrupament escolta i guia (el Cau també és el local on es fan les activitats).
- **AEiG**: Agrupament Escolta i Guia.
- **MEG**: Minyons Escoltes i Guies de Catalunya, l'associació de la qual forma part l'agrupament.
- **Branca**: cada franja d'edat de l'agrupament:
  - **Castors i Llúdrigues (CiLl)**: 6-8 anys.
  - **Llops i Daines (LiD)**: 8-11 anys.
  - **Ràngers i Noies Guia (RiNG)**: 11-14 anys.
  - **Pioners i Caravel·les (PiC)**: 14-17 anys.
  - **Trucs**: 17-19 anys. Les unitats de Trucs canvien de nom cada any i duren dos cursos.
- **Unitat**: cada grup dins d'una branca (p. ex. Wami i Churún-Merú són les dues unitats de Castors i Llúdrigues).
- **Cap**: persona responsable d'acompanyar una unitat. A Trucs no hi ha caps sinó un **animador/a**, que tria la mateixa unitat.
- **Passos**: sortida d'inici de curs en què els infants i joves passen a la branca següent.
- **El Cauet**: la revista de l'agrupament.
- **Consellet, Consell de Roca**: òrgans de decisió de cada branca (Consellet a Castors i Llúdrigues, Consell de Roca a Llops i Daines i a Ràngers i Noies Guia).
- **Escamot, sisena, patrulla, equip**: el petit grup dins de la unitat (escamot a CiLl, sisena a LiD, patrulla a RiNG, equip a PiC).

## Índex complet

### Sobre nosaltres

- [Breu història de l'escoltisme mundial](sobre-nosaltres/01-breu-historia-de-l-escoltisme-mundial.md)
- **02-qui-va-ser-baden-powell/**
  - [Qui va ser Baden-Powell?](sobre-nosaltres/02-qui-va-ser-baden-powell/README.md)
  - [La seva vida](sobre-nosaltres/02-qui-va-ser-baden-powell/01-la-seva-vida.md)
  - [El missatge de Baden-Powell](sobre-nosaltres/02-qui-va-ser-baden-powell/02-el-missatge-de-baden-powell.md)
  - [El testament de Baden-Powell](sobre-nosaltres/02-qui-va-ser-baden-powell/03-el-testament-de-baden-powell.md)
  - [La Llei escolta del 1911](sobre-nosaltres/02-qui-va-ser-baden-powell/04-la-llei-escolta-del-1911.md)
- **03-escoltisme-a-catalunya/**
  - [Introducció de l'escoltisme a Catalunya](sobre-nosaltres/03-escoltisme-a-catalunya/README.md)
  - [Batista i Roca i mossèn Batlle](sobre-nosaltres/03-escoltisme-a-catalunya/01-batista-i-roca-i-mossen-batlle.md)
  - [La Llei escolta segons els Minyons de Muntanya](sobre-nosaltres/03-escoltisme-a-catalunya/02-la-llei-escolta-segons-els-minyons-de-muntanya.md)
- **04-minyons-escoltes-i-guies-de-catalunya/**
  - [Minyons Escoltes i Guies de Catalunya](sobre-nosaltres/04-minyons-escoltes-i-guies-de-catalunya/README.md)
  - [La Llei escolta segons Minyons Escoltes i guies de Catalunya](sobre-nosaltres/04-minyons-escoltes-i-guies-de-catalunya/01-la-llei-escolta-segons-minyons-escoltes-i-guies-de-catalunya.md)
  - [Les tres opcions](sobre-nosaltres/04-minyons-escoltes-i-guies-de-catalunya/02-les-tres-opcions.md)
  - [Els cinc dinamismes](sobre-nosaltres/04-minyons-escoltes-i-guies-de-catalunya/03-els-cinc-dinamismes.md)
- [Història de l'escoltisme a Igualada](sobre-nosaltres/05-historia-de-l-escoltisme-a-igualada.md)
- **06-l-agrupament/**
  - [L'agrupament escolta i guia Jaume Caresmar i MªAntònia Salvà](sobre-nosaltres/06-l-agrupament/README.md)
  - [Què volem aconseguir?](sobre-nosaltres/06-l-agrupament/01-que-volem-aconseguir.md)
  - [Què fem?](sobre-nosaltres/06-l-agrupament/02-que-fem.md)
  - [Com ho fem?](sobre-nosaltres/06-l-agrupament/03-com-ho-fem.md)
  - [Com ens organitzem?](sobre-nosaltres/06-l-agrupament/04-com-ens-organitzem.md)
  - [El fulard i la camisa](sobre-nosaltres/06-l-agrupament/05-el-fulard-i-la-camisa.md)

### Unitats

- [Els CLL anem de campaments de setmana santa a Moià!](unitats/cill-2012-2013-campaments-de-setmana-santa-a-moia.md)
- **cill-churun-meru/**
  - **curs-2011-2012/**
    - [Som els Churún Merú!](unitats/cill-churun-meru/curs-2011-2012/01-som-els-churun-meru.md)
  - **curs-2012-2013/**
    - [Amb la Mika la mecànica comencem un viatge per la història!](unitats/cill-churun-meru/curs-2012-2013/01-amb-la-mika-la-mecanica-comencem-un-viatge-per-la-historia.md)
  - **curs-2013-2014/**
    - [Visca els Churún-Merú!](unitats/cill-churun-meru/curs-2013-2014/01-visca-els-churun-meru.md)
  - **curs-2015-2016/**
    - [Ajudem els follets!](unitats/cill-churun-meru/curs-2015-2016/01-ajudem-els-follets.md)
    - [Visita a Agrapes!](unitats/cill-churun-meru/curs-2015-2016/02-visita-a-agrapes.md)
    - [Despertem els sentits!](unitats/cill-churun-meru/curs-2015-2016/03-despertem-els-sentits.md)
    - [Sortida a Clariana!](unitats/cill-churun-meru/curs-2015-2016/04-sortida-a-clariana.md)
    - [Sortida a Sant Guim de Freixenet!](unitats/cill-churun-meru/curs-2015-2016/05-sortida-a-sant-guim-de-freixenet.md)
    - [Campaments de Setmana Santa a Súria!](unitats/cill-churun-meru/curs-2015-2016/06-campaments-de-setmana-santa-a-suria.md)
    - [Matinal a l'Espelt!](unitats/cill-churun-meru/curs-2015-2016/07-matinal-a-l-espelt.md)
  - **curs-2016-2017/**
    - [Viatgem pel món descobrint músiques de tot arreu!](unitats/cill-churun-meru/curs-2016-2017/01-viatgem-pel-mon-descobrint-musiques-de-tot-arreu.md)
    - [Sortida a l'Anella Verda](unitats/cill-churun-meru/curs-2016-2017/02-sortida-a-l-anella-verda.md)
    - [Sortida a Tous](unitats/cill-churun-meru/curs-2016-2017/03-sortida-a-tous.md)
    - [Treballem les emocions](unitats/cill-churun-meru/curs-2016-2017/04-treballem-les-emocions.md)
    - [Matinal a la Tossa](unitats/cill-churun-meru/curs-2016-2017/05-matinal-a-la-tossa.md)
    - [Sortida a Vallbona](unitats/cill-churun-meru/curs-2016-2017/06-sortida-a-vallbona.md)
    - [Campaments de Setmana Santa a Calaf!](unitats/cill-churun-meru/curs-2016-2017/07-campaments-de-setmana-santa-a-calaf.md)
- [El consellet](unitats/cill-el-consellet.md)
- [El petit grup: l'escamot](unitats/cill-el-petit-grup-l-escamot.md)
- [Qui som els Castors i les Llúdrigues?](unitats/cill-qui-som-els-castors-i-les-lludrigues.md)
- **cill-wami/**
  - **curs-2010-2011/**
    - [Castors i llúdrigues](unitats/cill-wami/curs-2010-2011/01-castors-i-lludrigues.md)
    - [Sortides](unitats/cill-wami/curs-2010-2011/02-sortides.md)
    - [Ja tornem a tenir a l'Aura aquí !](unitats/cill-wami/curs-2010-2011/03-ja-tornem-a-tenir-a-l-aura-aqui.md)
  - **curs-2011-2012/**
    - [Som els Wami!](unitats/cill-wami/curs-2011-2012/01-som-els-wami.md)
  - **curs-2012-2013/**
    - [Els Wami i la màquina del temps](unitats/cill-wami/curs-2012-2013/01-els-wami-i-la-maquina-del-temps.md)
  - **curs-2013-2014/**
    - [Visca els Wami!](unitats/cill-wami/curs-2013-2014/01-visca-els-wami.md)
  - **curs-2015-2016/**
    - [Wamics del cau!](unitats/cill-wami/curs-2015-2016/01-wamics-del-cau.md)
    - [Matinal a la Fou](unitats/cill-wami/curs-2015-2016/02-matinal-a-la-fou.md)
    - [Sortida a Santa Margarida de Montbui](unitats/cill-wami/curs-2015-2016/03-sortida-a-santa-margarida-de-montbui.md)
    - [Dia sobre rodes](unitats/cill-wami/curs-2015-2016/04-dia-sobre-rodes.md)
    - [Qui és el Wamic?](unitats/cill-wami/curs-2015-2016/05-qui-es-el-wamic.md)
  - **curs-2016-2017/**
    - [Wami 2016-17](unitats/cill-wami/curs-2016-2017/01-wami-2016-17.md)
    - [Vam anar a St.Genís!](unitats/cill-wami/curs-2016-2017/02-vam-anar-a-st-genis.md)
- [El consell de Roca](unitats/llid-el-consell-de-roca.md)
- [El petit grup: la sisena](unitats/llid-el-petit-grup-la-sisena.md)
- [Qui som els Llops i daines?](unitats/llid-qui-som-els-llops-i-daines.md)
- **llid-seonee/**
  - **curs-2010-2011/**
    - [Llops i daines Seonee 2010-2011](unitats/llid-seonee/curs-2010-2011/01-llops-i-daines-seonee-2010-2011.md)
  - **curs-2011-2012/**
    - [Llops i daines Seonee 2011-2012](unitats/llid-seonee/curs-2011-2012/01-llops-i-daines-seonee-2011-2012.md)
- **llid-wahya/**
  - **curs-2010-2011/**
    - [Llops i daines Wahya 2010-2011](unitats/llid-wahya/curs-2010-2011/01-llops-i-daines-wahya-2010-2011.md)
  - **curs-2011-2012/**
    - [Som els Wahya!](unitats/llid-wahya/curs-2011-2012/01-som-els-wahya.md)
  - **curs-2015-2016/**
    - [Cau amb els llops de Moià!](unitats/llid-wahya/curs-2015-2016/01-cau-amb-els-llops-de-moia.md)
  - [Text de la promesa — Wahya](unitats/llid-wahya/text-de-la-promesa.md)
- [Compromís i progrés personal](unitats/pic-compromis-i-progres-personal.md)
- [El projecte](unitats/pic-el-projecte.md)
- [Els equips](unitats/pic-els-equips.md)
- **pic-maracaibo/**
  - **curs-2013-2014/**
    - [Som els Maracaibo!](unitats/pic-maracaibo/curs-2013-2014/01-som-els-maracaibo.md)
  - [D'on prové el nom?](unitats/pic-maracaibo/d-on-prove-el-nom.md)
  - [Text de la promesa — Maracaibo](unitats/pic-maracaibo/text-de-la-promesa.md)
- [Qui som?](unitats/pic-qui-som.md)
- **pic-tanganyika/**
  - **curs-2010-2011/**
    - [Tanganyika](unitats/pic-tanganyika/curs-2010-2011/01-tanganyika.md)
  - **curs-2011-2012/**
    - **escocia-2012/**
      - [Escòcia 2012 campaments d'estiu](unitats/pic-tanganyika/curs-2011-2012/escocia-2012/README.md)
      - [Objectius projecte](unitats/pic-tanganyika/curs-2011-2012/escocia-2012/01-objectius-projecte.md)
      - [Carta pels nostres pares i mares](unitats/pic-tanganyika/curs-2011-2012/escocia-2012/02-carta-pels-nostres-pares-i-mares.md)
      - [Carta abans de marxar de campaments](unitats/pic-tanganyika/curs-2011-2012/escocia-2012/03-carta-abans-de-marxar-de-campaments.md)
  - **curs-2012-2013/**
    - [Som els Tanganyika!](unitats/pic-tanganyika/curs-2012-2013/01-som-els-tanganyika.md)
  - [D'on prové el nom?](unitats/pic-tanganyika/d-on-prove-el-nom.md)
  - [Text de la promesa — Tanganyika](unitats/pic-tanganyika/text-de-la-promesa.md)
- [Encantats i Besiberris fem CAU conjunt!](unitats/ring-2013-2014-cau-conjunt-encantats-i-besiberris.md)
- **ring-besiberris/**
  - [Carta dels Ràngers i Noies Guia](unitats/ring-besiberris/carta-dels-rangers-i-noies-guia.md)
  - **curs-2010-2011/**
    - [Besiberris](unitats/ring-besiberris/curs-2010-2011/01-besiberris.md)
    - [Projectes](unitats/ring-besiberris/curs-2010-2011/02-projectes.md)
    - [La Censada Nova](unitats/ring-besiberris/curs-2010-2011/03-la-censada-nova.md)
    - [Montserrat](unitats/ring-besiberris/curs-2010-2011/04-montserrat.md)
  - **curs-2011-2012/**
    - [Som els Besiberris!!](unitats/ring-besiberris/curs-2011-2012/01-som-els-besiberris.md)
  - **curs-2013-2014/**
    - [Visca els Besiberris!](unitats/ring-besiberris/curs-2013-2014/01-visca-els-besiberris.md)
  - [Els Besiberris](unitats/ring-besiberris/els-besiberris.md)
  - [Els nostres valors](unitats/ring-besiberris/els-nostres-valors.md)
  - [Text de la promesa — Besiberris](unitats/ring-besiberris/text-de-la-promesa.md)
- [Com ens organitzem?](unitats/ring-com-ens-organitzem.md)
- [Consell de Roca](unitats/ring-consell-de-roca.md)
- **ring-encantats/**
  - **curs-2010-2011/**
    - [Encantats](unitats/ring-encantats/curs-2010-2011/01-encantats.md)
    - [Activitats i excursions](unitats/ring-encantats/curs-2010-2011/02-activitats-i-excursions.md)
    - [Projectes, excursions i campaments](unitats/ring-encantats/curs-2010-2011/03-projectes-excursions-i-campaments.md)
  - **curs-2011-2012/**
    - [Som els Encantats!!](unitats/ring-encantats/curs-2011-2012/01-som-els-encantats.md)
  - **curs-2013-2014/**
    - [Visca els Encantats!!](unitats/ring-encantats/curs-2013-2014/01-visca-els-encantats.md)
  - [Els Encantats](unitats/ring-encantats/els-encantats.md)
  - [Text de la promesa — Encantats](unitats/ring-encantats/text-de-la-promesa.md)
- [L'operació](unitats/ring-l-operacio.md)
- [La Promesa a R/NG](unitats/ring-la-promesa.md)
- [Ràngers i Noies Guia](unitats/ring-rangers-i-noies-guia.md)
- **trucs/**
  - **curs-2010-2011/**
    - [Trucs](unitats/trucs/curs-2010-2011/01-trucs.md)
    - [Campaments a Tavertet](unitats/trucs/curs-2010-2011/02-campaments-a-tavertet.md)
    - [Calçotada](unitats/trucs/curs-2010-2011/03-calcotada.md)
  - **curs-2011-2012/**
    - [Som els Trucs!!](unitats/trucs/curs-2011-2012/01-som-els-trucs.md)
  - **curs-2013-2014/**
    - [Visca els Trucs!](unitats/trucs/curs-2013-2014/01-2n-any-visca-els-trucs.md)
    - [Campaments d'intercanvi Catalunya-Bòsnia-Montenegro](unitats/trucs/curs-2013-2014/02-2n-any-campaments-d-intercanvi-catalunya-bosnia-montenegro.md)
    - [Visca els Lilium!](unitats/trucs/curs-2013-2014/03-lilium-visca-els-lilium.md)
    - [Visca els Karakorum!](unitats/trucs/curs-2013-2014/04-karakorum-visca-els-karakorum.md)
  - **curs-2014-2015/**
    - [Som els Trucs Kraken!](unitats/trucs/curs-2014-2015/01-kraken-som-els-trucs-kraken.md)
    - [El mar i el cel a l’infinit](unitats/trucs/curs-2014-2015/02-kraken-el-mar-i-el-cel-a-l-infinit.md)
    - [Ruta i descoberta d'Euskadi](unitats/trucs/curs-2014-2015/03-kraken-ruta-i-descoberta-d-euskadi.md)
  - **curs-2015-2016/**
    - [Els Lilium tornen!](unitats/trucs/curs-2015-2016/01-lilium-els-lilium-tornen.md)
- [Acció de servei](unitats/trucs-accio-de-servei.md)
- [Compromís i progrés personal](unitats/trucs-compromis-i-progres-personal.md)
- [Projectes i servei](unitats/trucs-projectes-i-servei.md)
- [Qui som?](unitats/trucs-qui-som.md)

### El Cauet

- [Què és el Cauet?](el-cauet/README.md)
- [EL CAUET: les revistes publicades](el-cauet/les-revistes-publicades.md)

### Fem 60 anys

- [Fem 60 anys](fem-60-anys/README.md)
- [El cau participa en la renovació de l'ofrena del Ciri Votiu a Montserrat](fem-60-anys/01-el-cau-participa-en-la-renovacio-de-l-ofrena-del-ciri-votiu-a.md)
- [Missa del Gall](fem-60-anys/02-missa-del-gall.md)
- [Calçotada 60 anys](fem-60-anys/03-calcotada-60-anys.md)
- [Exposició 60è aniversari](fem-60-anys/04-exposicio-60e-aniversari.md)
- [Festa de Sant Jordi 2013](fem-60-anys/05-festa-de-sant-jordi-2013.md)
- [Caminada al Cogulló i cerimònia de record](fem-60-anys/06-caminada-al-cogullo-i-cerimonia-de-record.md)
- [Projecte 60 cims](fem-60-anys/07-projecte-60-cims.md)

### Igualada x Igualada

- [Fem servei](igualada-x-igualada/README.md)
- [IgualadaxIgualada](igualada-x-igualada/01-igualadaxigualada.md)
- [22 de desembre](igualada-x-igualada/02-22-de-desembre.md)
- [Banc de Queviures d'Igualada](igualada-x-igualada/03-banc-de-queviures-d-igualada.md)
- [La segona recollida aporta els productes més necessaris al Banc de Queviures](igualada-x-igualada/04-la-segona-recollida-aporta-els-productes-mes-necessaris-al-banc-de.md)
- [El Cau d'Igualada contra els desnonaments](igualada-x-igualada/05-el-cau-d-igualada-contra-els-desnonaments.md)
- [El cau organitzarà un punt d'intercanvi d'aliments del Banc de Queviures](igualada-x-igualada/06-el-cau-organitzara-un-punt-d-intercanvi-d-aliments-del-banc-de.md)

### Notícies

- [Notícies del curs 2010-2011](noticies/curs-2010-2011.md)
- [Notícies del curs 2011-2012](noticies/curs-2011-2012.md)
- [Notícies del curs 2012-2013](noticies/curs-2012-2013.md)
- [Notícies del curs 2013-2014](noticies/curs-2013-2014.md)
- [Notícies del curs 2014-2015](noticies/curs-2014-2015.md)
- [Notícies del curs 2015-2016](noticies/curs-2015-2016.md)
- [Notícies del curs 2016-2017](noticies/curs-2016-2017.md)
- [Notícies del curs 2017-2018](noticies/curs-2017-2018.md)
- [Notícies del curs 2018-2019](noticies/curs-2018-2019.md)

### Avís legal i crèdits

- [Avís Legal](avis-legal-i-credits/avis-legal.md)
- [Crèdits](avis-legal-i-credits/credits.md)
