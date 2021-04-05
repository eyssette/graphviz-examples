# Repertoire de schémas créés avec Graphviz

J'utilise beaucoup le logiciel de programmation de graphiques [Graphviz](https://graphviz.org/).
J'ai créé des modèles pour pouvoir créer plus facilement des schémas qui me servent dans mes cours de philosophie et pour mes recherches personnelles.

Les modèles sont disponibles ici : https://github.com/eyssette/graphviz-templates

Voici des exemples de schémas que j'ai créés avec ces modèles.

Accéder directement aux images au format svg : https://github.com/eyssette/graphviz-examples/search?l=SVG

## Schémas type “carte mentale”

https://github.com/eyssette/graphviz-examples/tree/master/diagram

[Lien vers GraphvizOnline avec le modèle “carte mentale” déjà chargé](https://dreampuf.github.io/GraphvizOnline/#digraph%20G%20%7B%0A%2F%2F%20Template%20%3A%20diagram%0A%2F%2F%20Usage%20%3A%20%0A%2F%2Frankdir%3DLR%0Asplines%3Dtrue%0A%2F%2Fsplines%3Dcurved%0Abgcolor%3Dgrey98%0Apad%3D0.3%0Astyle%3Dfilled%0Aedge%5Bminlen%3D4%5D%0Anode%5Bstyle%3Dfilled%2C%20fontcolor%3Dwhite%5D%0Aranksep%3D0.1%0Anodesep%3D0.2%0A%0A%2F%2F%20NIVEAU%201%0Anode%5Bfillcolor%3D12%2C%20fontsize%3D18%5D%0Aa1%5Blabel%3D%22%22%5D%0A%0A%2F%2F%20NIVEAU%202%0Anode%5Bfillcolor%3Dred4%2C%20fontsize%3D16%5D%0Aa1-%3E%7B%0Ab1%5Blabel%3D%22%22%5D%20%20%20%20%0Ab2%5Blabel%3D%22%22%5D%0A%7D%5Bheadport%3Dn%5D%0A%0Anode%5Bfontcolor%3Dblack%5D%0A%2F%2F%20NIVEAU%203%20(sans%20interm%C3%A9diaire)%0Anode%20%5Bshape%3Dbox%2C%20fillcolor%3Dwhite%2C%20color%3Dgrey50%5D%0A%2F%2F%20c1%5Blabel%3D%22%22%5D%0Ab1-%3Ec1%0Ac1%5Blabel%3D%22%22%5D%0Ab2-%3Ec2%0Ac2%5Blabel%3D%22%22%5D%0A%0A%2F%2F%20INTERM%C3%89DIAIRE%20AVANT%20NIVEAU%203%0Anode%5Bfillcolor%3Dgrey78%2C%20shape%3Doval%5D%0A%2F%2F%20%5Barrowhead%3Dnone%5D%0A%2F%2F%20bc1%5Blabel%3D%22%22%5D%0A%0A%2F%2F%20NIVEAU%203%20(avec%20interm%C3%A9diaire)%0Anode%5Bfillcolor%3Dwhite%2C%20shape%3Dbox%2C%20color%3Dgrey50%5D%0A%2F%2F%20c1%5Blabel%3D%22%22%5D%0A%0A%2F%2F%20NIVEAU%204%0Anode%5Bstyle%3D%22filled%2Crounded%22%2C%20fillcolor%3Dwhite%2C%20shape%3Dbox%2C%20color%3Dgrey50%5D%0A%2F%2F%20d1%5Blabel%3D%22%22%5D%0A%0A%2F%2F%20%C3%89TIQUETTES%20EN%20ROUGE%0Anode%5Bshape%3Dplaintext%2C%20fontcolor%3Dfirebrick3%2C%20fillcolor%3Dgrey98%5D%0A%2F%2F%20e1%5Blabel%3D%3C%20%3CB%3E%3D%20Titre%3C%2FB%3E%3CBR%20%2F%3E%3CBR%20%2F%3EContenu%3CBR%20%2F%3E%20%3E%5D%0A%2F%2F%20e1%5Blabel%3D%22%22%5D%0A%2F%2F%20-%3Ee1%5Bminlen%3D1%2C%20style%3Dinvis%5D%0A%0A%2F%2F%20REMARQUES%20EN%20BLEU%0Anode%5Bcolor%3Dblue%2C%20shape%3Dbox%2C%20margin%3D0.07%2C%20fontcolor%3Dblack%2C%20fontsize%3D12%2C%20style%3D%22dashed%22%2C%20penwidth%3D0.6%5D%0Aedge%5Bcolor%3Dblue%2C%20arrowhead%3D%22none%22%2C%20xlabel%3D%22%22%2C%20style%3D%22dashed%22%2C%20penwidth%3D0.6%5D%0A%2F%2F%20r1%5Blabel%3D%22%22%5D%0A%2F%2F%20%7Brank%3Dsame%3B-%3Er1%7D%0A%2F%2F%20%7Brank%3Dsame%3Br1-%3E%5Bdir%3Dback%5D%7D%0A%0A%7D)


## Schémas en arbre d'un raisonnement

https://github.com/eyssette/graphviz-examples/tree/master/argument

### version avec seulement les objections rédigées dans le schéma

[Lien vers GraphvizOnline avec ce modèle déjà chargé](https://dreampuf.github.io/GraphvizOnline/#digraph%20G%20%7B%0Asplines%3Dtrue%0Anewrank%3Dtrue%0Acompound%3Dtrue%0A%0A%0Anode%5Bcolor%3Dred3%2C%20style%3D%22rounded%2C%20filled%22%2C%20shape%3D%22circle%22%2C%20fillcolor%3Dred3%2C%20penwidth%3D0.5%2C%20fontcolor%3Dwhite%2C%20margin%3D0%2C%20size%3D1%5D%0Ao1%5Blabel%3D%22o1%22%5D%0A%0Anode%5Bshape%3Dbox%2C%20fillcolor%3Dwhite%2C%20style%3D%22filled%2Crounded%22%2C%20color%3Dblack%2C%20fontsize%3D24%2C%20penwidth%3D1%2Cfontcolor%3Dblack%2C%20margin%3D0.1%5D%0Aedge%5Bminlen%3D2%2Ccolor%3Dred3%2C%20penwidth%3D0.8%2C%20arrowsize%3D0.8%2C%20label%3D%22Objection%20!%22%2C%20fontcolor%3Dred4%2Cfontsize%3D10%5D%0A%7Brank%3Dsame%3Bo1-%3Ep1%5Bdir%3Dback%5D%7D%0A%0A%0Asubgraph%20cluster_0%20%7B%0Abgcolor%3Dgrey90%0Astyle%3Drounded%0Acolor%3Dgrey50%0Amargin%3D40%0A%0A%0A%0Anode%5Bshape%3Dbox%2C%20fillcolor%3Dwhite%2C%20style%3D%22filled%2Crounded%22%2C%20color%3Dblack%5D%0Aedge%5Blabel%3D%22%22%2Cxlabel%3D%22Par%0Acons%C3%A9quent%20%E2%80%A6%22%2Cfontcolor%3Dgrey40%3Bfontsize%3D15%2Cminlen%3D3%2Ccolor%3Dblack%2Cpenwidth%3D1%2C%20arrowsize%3D1%5D%0A%0A%0A%0Asubgraph%20cluster_1%20%7B%0Astyle%3D%22box%22%0Amargin%3D15%0Abgcolor%3Dgrey73%0Acolor%3Dgrey73%0Ap1%5Blabel%3D%22(1)%20Pr%C3%A9misse%20A%22%5D%0A%0Ap2%5Blabel%3D%22(2)%20Pr%C3%A9misse%20B%22%5D%0A%7D%0A%0Ap1-%3Ep2%5Bstyle%3Dinvis%2Cxlabel%3D%22%22%2Cminlen%3D1%5D%0A%2F%2F%7Brank%3Dsame%3Bp1-%3Ep2%5Bstyle%3Dinvis%2Cxlabel%3D%22%22%2Cminlen%3D1%5D%7D%0A%0Ap2%3As-%3Ep3%3An%5Bltail%3Dcluster_1%5D%0A%2F%2Fp2%3Aw-%3Ep3%3An%5Bltail%3Dcluster_1%5D%0Ap3%5Blabel%3D%22(3)%20Lemme%201%22%5D%0A%0A%7Brank%3Dsame%3Bp3-%3Ep4%5Bstyle%3Dinvis%5D%7D%0A%0Ap4%5Blabel%3D%22(4)%20Pr%C3%A9misse%203%22%5D%0A%0A%7Bp3%2Cp4%7D-%3EC%0A%0A%0AC%5Blabel%3D%22Conclusion%22%2Cfillcolor%3Dblack%2C%20fontcolor%3Dwhite%2C%20color%3Dblack%2C%20shape%3Dellipse%5D%0A%0A%0A%7D%0A%0Anode%5Bcolor%3Dred3%2C%20style%3D%22rounded%2C%20filled%22%2C%20shape%3D%22circle%22%2C%20fillcolor%3Dred3%2C%20penwidth%3D0.5%2C%20fontcolor%3Dwhite%2C%20margin%3D0%2C%20size%3D1%2Cfontsize%3D14%5D%0Ao2%5Blabel%3D%22o2%22%5D%0A%7Brank%3Dsame%3Bp4-%3Eo2%7D%0A%0A%7D)

### version avec seulement des objections numérotées

[Lien vers GraphvizOnline avec ce modèle déjà chargé](https://dreampuf.github.io/GraphvizOnline/#digraph%20G%20%7B%0Asplines%3Dtrue%0Anewrank%3Dtrue%0Acompound%3Dtrue%0A%0A%0Anode%5Bcolor%3Dred3%2C%20style%3D%22rounded%2C%20filled%22%2C%20shape%3D%22circle%22%2C%20fillcolor%3Dred3%2C%20penwidth%3D0.5%2C%20fontcolor%3Dwhite%2C%20margin%3D0%2C%20size%3D1%5D%0Ao1%5Blabel%3D%22o1%22%5D%0A%0Anode%5Bshape%3Dbox%2C%20fillcolor%3Dwhite%2C%20style%3D%22filled%2Crounded%22%2C%20color%3Dblack%2C%20fontsize%3D24%2C%20penwidth%3D1%2Cfontcolor%3Dblack%2C%20margin%3D0.1%5D%0Aedge%5Bminlen%3D2%2Ccolor%3Dred3%2C%20penwidth%3D0.8%2C%20arrowsize%3D0.8%2C%20label%3D%22Objection%20!%22%2C%20fontcolor%3Dred4%2Cfontsize%3D10%5D%0A%7Brank%3Dsame%3Bo1-%3Ep1%5Bdir%3Dback%5D%7D%0A%0A%0Asubgraph%20cluster_0%20%7B%0Abgcolor%3Dgrey90%0Astyle%3Drounded%0Acolor%3Dgrey50%0Amargin%3D40%0A%0A%0A%0Anode%5Bshape%3Dbox%2C%20fillcolor%3Dwhite%2C%20style%3D%22filled%2Crounded%22%2C%20color%3Dblack%5D%0Aedge%5Blabel%3D%22%22%2Cxlabel%3D%22Par%0Acons%C3%A9quent%20%E2%80%A6%22%2Cfontcolor%3Dgrey40%3Bfontsize%3D15%2Cminlen%3D3%2Ccolor%3Dblack%2Cpenwidth%3D1%2C%20arrowsize%3D1%5D%0A%0A%0A%0Asubgraph%20cluster_1%20%7B%0Astyle%3D%22box%22%0Amargin%3D15%0Abgcolor%3Dgrey73%0Acolor%3Dgrey73%0Ap1%5Blabel%3D%22(1)%20Pr%C3%A9misse%20A%22%5D%0A%0Ap2%5Blabel%3D%22(2)%20Pr%C3%A9misse%20B%22%5D%0A%7D%0A%0Ap1-%3Ep2%5Bstyle%3Dinvis%2Cxlabel%3D%22%22%2Cminlen%3D1%5D%0A%2F%2F%7Brank%3Dsame%3Bp1-%3Ep2%5Bstyle%3Dinvis%2Cxlabel%3D%22%22%2Cminlen%3D1%5D%7D%0A%0Ap2%3As-%3Ep3%3An%5Bltail%3Dcluster_1%5D%0A%2F%2Fp2%3Aw-%3Ep3%3An%5Bltail%3Dcluster_1%5D%0Ap3%5Blabel%3D%22(3)%20Lemme%201%22%5D%0A%0A%7Brank%3Dsame%3Bp3-%3Ep4%5Bstyle%3Dinvis%5D%7D%0A%0Ap4%5Blabel%3D%22(4)%20Pr%C3%A9misse%203%22%5D%0A%0A%7Bp3%2Cp4%7D-%3EC%0A%0A%0AC%5Blabel%3D%22Conclusion%22%2Cfillcolor%3Dblack%2C%20fontcolor%3Dwhite%2C%20color%3Dblack%2C%20shape%3Dellipse%5D%0A%0A%0A%7D%0A%0Anode%5Bcolor%3Dred3%2C%20style%3D%22rounded%2C%20filled%22%2C%20shape%3D%22circle%22%2C%20fillcolor%3Dred3%2C%20penwidth%3D0.5%2C%20fontcolor%3Dwhite%2C%20margin%3D0%2C%20size%3D1%2Cfontsize%3D14%5D%0Ao2%5Blabel%3D%22o2%22%5D%0A%7Brank%3Dsame%3Bp4-%3Eo2%7D%0A%0A%7D)

## Synthèse des idées d'un article

https://github.com/eyssette/graphviz-examples/tree/master/summary

## Succession de conjectures et de réfutations

https://github.com/eyssette/graphviz-examples/tree/master/conjectures-and-refutations

## Débats

https://github.com/eyssette/graphviz-examples/tree/master/debating
