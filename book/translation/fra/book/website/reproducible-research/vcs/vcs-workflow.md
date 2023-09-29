(rr-vcs-workflow)=
# Flux de travail général

Le contrôle de version est une approche systématique des modifications effectuées dans un fichier ou un ensemble de fichiers au fil du temps. Cela permet à vous et à vos collaborateurs de suivre l'historique, de voir ce qui a changé et de rappeler des versions spécifiques plus tard lorsque nécessaire. Une procédure typique pour utiliser le contrôle de version est la suivante:

1. Créer des fichiers - ceux-ci peuvent contenir du texte, du code ou les deux.
2. Travaillez sur ces fichiers, en changant, en supprimant ou en ajoutant un nouveau contenu.
3. Créer un instantané du statut du fichier (également connu sous le nom de version) pour le moment.
4. Document what was changed in the version history of that file.

The snapshot process is often done manually for text or presentation documents (for instance by naming files with the suffixes `v01`, `v02` and so on). A description of the changes for each version is sometimes made via an external document like a spreadsheet. Finding the latest version can also be facilitated by putting old versions in a subfolder. This manual process is not very practical when a lot of files are changing, like when one creates code or work with data. In these cases, the use of a version control software is highly recommended.


Ce processus de création d'un instantané est décrit différemment dans différents logiciels de contrôle de version. Par exemple, Git le décrit comme « un engagement ». Certains systèmes l'appellent "un point de temps" ou "un point de contrôle"; et cela est appelé "sauvegarde de votre travail" dans d'autres cas, comme dans [Google docs](https://docs.google.com/) ou [HackMD](http://hackmd.io/). The version history may be more or less informative.

Au fur et à mesure que vous enregistrez votre travail en ajoutant des modifications, vous faites de plus en plus d'instantanés. Vous pouvez les considérer comme une sauvegarde des versions de ces fichiers tout en documentant leur historique. Si vous devez retourner à une version précédente d'un fichier à cause d'une erreur, ou si vous avez changé d'avis à propos d'une mise à jour précédente, vous pouvez accéder au fichier dans votre version préférée, ou renvoyer tout votre projet à un état antérieur.


```{figure} ../../figures/main-branch.*
---
name: main-branch
alt: circles represents different snapshot of a file, they are added sequentially. An arrow going from the last circle to several cirles on the left represents the possiblitiy to return to a paste state of the file.
---
Version history with a single branch
```

Dans de nombreux systèmes de contrôle de version, vous pourrez ajouter un commentaire à chaque fois que vous enregistrez une nouvelle version. Ces commentaires devraient être clairs et concis afin de faciliter la compréhension des modifications proposées et des mises à jour apportées dans une version. Cela garantit qu'il est facile de trouver ce que vous cherchez quand vous avez besoin de revenir à une version antérieure. Vos collaborateurs vous remercieront, mais les versions futures de vous-même.
