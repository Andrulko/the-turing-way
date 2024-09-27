(partage d'aperçu-pd)=
# Partagez votre travail de recherche

In order to make sure that (most) research outputs are available to everyone interested in analysing or reusing them, let's take some time to learn about how to share them. La science ne peut que progresser en s'appuyant sur les résultats de chacun. La première étape consiste à partager votre travail. Different digital research outputs or {ref}`research objects<cm-ro>`, such as data, software and code, protocols, reagents, and hardware, can be shared as open results on the web. They should come with specific information such as licenses, documentation and source code (repository, online index or archive).

Mais le seul partage ne suffit pas. Vous devez vous assurer que vos objets de recherche sont identifiables **F** **A**ccesible, **I**noperable et **R**eutilisable. Ceci est appelé {ref}`Principes FAIR<rr-rdm-fair>` qui fournit des directives pour améliorer le Findability, Accessibilité, interopérabilité et réutilisabilité des actifs numériques ; qui soutiennent la reproductibilité de la recherche.

Cet aspect est déjà pris en compte lors du développement de votre {ref}`plan de gestion des données (DMP)<rr-rdm-dmp>` (voir {ref}`pd-overview-planning-dmp`). Par conséquent, il est important de revoir votre DMP pour vous assurer que les lignes directrices sont également appliquées lors de la mise à disposition de vos résultats. Vous pouvez en apprendre plus à ce sujet dans un chapitre sur {ref}`faisant des données FAIR<rr-rdm-fair>`).

(pd-overview-sharing-archive)=
## Share your data

Comme vos données, vos sorties devraient être archivées dans un endroit ouvert, où les personnes peuvent y accéder. If you have sensitive data, you will not be able to share the raw data, but there may be some data you can share. A repository is a good place to store your data.

Vous trouverez un aperçu de certains dépôts disponibles pour l'archivage de vos données dans [re3data.org](https://www.re3data.org/).

Une autre bonne ressource où vous pouvez en savoir plus sur ce sujet est le chapitre sur {ref}`Partage et archivage des données<rr-rdm-sharing>`.

(pd-overview-sharing-protocols)=
## Partagez vos protocoles

L'une des raisons pour lesquelles la recherche reproductible est de fournir aux autres les outils nécessaires pour s'appuyer sur elle. Si les détails des protocoles ne sont pas partagés, les chercheurs peuvent passer des mois à les optimiser avant de pouvoir commencer leurs projets.

Un outil qui peut être utilisé pour éviter cela est [protocols.io](https://www.protocols.io/). Il fournit un moyen de s'assurer que vos protocoles sont ouvertement disponibles, vous permettant de les mettre à jour tout en gardant une trace des changements. En outre, avoir vos protocoles en ligne les rend plus faciles à partager, ce qui leur donne la possibilité de contribuer.

## Partage des scripts d'analyse et des logiciels de recherche

Si vous êtes nouveau dans le contrôle de version, vous pouvez en savoir plus à ce sujet dans le chapitre {ref}`Contrôle de version<rr-vcs>`. You should now consider putting a snapshot of your code in a repository, so you can be sure it gets archived for a relatively long time, and it become citable. Indeed, there is no guarantee that the repository will stay available for a long time.


Vous pouvez intégrer votre système de contrôle de version avec un référentiel d'usage général. Par exemple, lors de l'intégration de GitHub avec Zenodo, vous pouvez obtenir des identifiants d'objets numériques ou des DOI pour votre logiciel. Cela facilite automatiquement le partage et le rend citable. Vous pouvez en savoir plus sur les DOI dans le chapitre sur {ref}`Créer un centre de recherche<cm-citable>`.



## Share Research Hardware

In absence of better solution, you may deal with your hardware documentation with the smae strategy as with your software: using version control  repositories during its development, and zenodo integration for archiving. If your documentation is in the form of a website, try to provide a independent html build that can run without a server.

## Share reagents

Depending on your research domain, you may have produced reagents (genetic material or tissue for example). If there is a specific bank for these products that can share them widely, you may consider using them. Make sure a persistent identifier is given, an that the description of your reagents have enough metadata to make sharing useful.

## Collecter vos Recherches

Une fois votre recherche terminée, vous voudrez peut-être rassembler toutes les parties numériques de votre projet en un seul endroit. Cela s'appelle un recueil de recherche. Publier votre papier avec un compendium de recherche permet l'étendue de votre recherche : à partir de la conception du projet, grâce à la mémoire de données et à l'analyse et aux résultats obtenus.

Cela présente des avantages sans fin. Il rend votre travail partageable et reproductible, les autres peuvent s'appuyer sur lui et vous donner plus de visibilité.

Vous pouvez lire comment configurer votre compendia de recherche, {ref}`ce chapitre<rr-compendia>`.

(pd-overview-sharing-Licence)=
## Ajouter une licence aux résultats de recherche

Même si vous avez obtenu une licence au début du projet, vous devez y réfléchir à nouveau lorsque vous partagez vos résultats et les résultats finaux - cela permet aux gens d'avoir l'information sur la façon dont votre recherche doit être réutilisée et partagée.

Si vous voulez plus d'informations sur la façon de choisir et d'ajouter une licence à votre projet, vous pouvez consulter le chapitre de licence de {ref}`<rr-licensing>`.

(citation pd-overview) =
## Recevoir des Citations

Tout ce dur travail aura sa récompense. Après avoir publié toutes vos recherches, de la conception aux résultats, vous aurez plus de visibilité à votre travail et plus de possibilité d'obtenir du crédit.

Non seulement vos résultats peuvent être cités, mais vos méthodes et protocoles peuvent être réutilisés et votre conception peut être partagée.

Lisez {ref}`ce chapitre sur l'ORCID<cm-citable-orcid>` pour plus d'informations sur la façon dont vous pouvez collecter différents résultats de recherche en un seul endroit en utilisant ORCID et en les mettant en évidence pour obtenir un crédit équitable pour votre travail.
