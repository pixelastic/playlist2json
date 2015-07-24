# playlist2json

Pass a youtube playlist url to the script and it will create a `json` file
containing metadata of all the videos of the playlist.

## Usage

```
$ playlist2json "https://www.youtube.com/playlist?list=PLyzb9DL11tdbBE9jpIm76GPcANwSG7Otf"

Parsing https://www.youtube.com/feeds/videos.xml?playlist_id=PLyzb9DL11tdbBE9jpIm76GPcANwSG7Otf
File saved as ./json/USI_2015.json
```

## Output

```json
[
  {
    "objectID": "289lwrW_gP0",
    "playlist_name": "USI_2015",
    "title": "De l'entreprise digitale à l'entreprise libérée - Ludovic Cinquin, à l'USI",
    "url": "http://www.youtube.com/watch?v=289lwrW_gP0",
    "published": 1437383766,
    "thumbnail": "https://i3.ytimg.com/vi/289lwrW_gP0/hqdefault.jpg",
    "thumbnail_width": "480",
    "thumbnail_height": "360",
    "description": "Diplômé de l'Ecole Centrale Paris et de la Technische Universität de Munich, Ludovic Cinquin a accompagné la fondation d'OCTO en 1998. \n\nIl traite du passage de l'entreprise digitale à l'entreprise libérée. La transformation digitale de l’entreprise prend acte de l’impact des technologies sur les business models, la relation au client, mais aussi et surtout sur les façons de travailler et la culture de l’entreprise : toute transition numérique finit par trouver sur son chemin la nécessaire autonomisation des équipes, la prise de décision au plus proche du terrain par les gens qui font, le droit à l'erreur, l'enjeu d'un pilotage centré sur la mesure.\nLes ressorts de cette transformation culturelle sont au final très proches de ceux qu’ont mis en oeuvre les entreprises libérées. Nous pouvons y trouver des pistes pour explorer les enjeux de ce grand saut du changement digital ?\n\nInformations et inscription sur http://www.usievents.com\n\nSuivez USI sur Twitter : https://twitter.com/USIEvents\nRetrouvez USI sur LinkedIn : http://linkd.in/13Ls21Y\nAbonnez-vous à notre chaine : http://bit.ly/19sPpSp\n\nPlus d'informations sur OCTO Technology : http://www.octo.com",
    "views": "428",
    "rating": "5.00"
  },
  [...]
  {
    "objectID": "b1szL_vySqM",
    "playlist_name": "USI_2015",
    "title": "Comment éviter de se faire court-circuiter par le digital ? - Christian Fauré, à l'USI",
    "url": "http://www.youtube.com/watch?v=b1szL_vySqM",
    "published": 1437383912,
    "thumbnail": "https://i3.ytimg.com/vi/b1szL_vySqM/hqdefault.jpg",
    "thumbnail_width": "480",
    "thumbnail_height": "360",
    "description": "Ingénieur et philosophe, Christian Fauré est Partner chez OCTO Technology et président de l'Institut de Recherche et d'Innovation du Centre Pompidou.\nIl répond à la question suivante : Comment éviter de se faire court-circuiter par le digital ? Son propos s'adresse aussi bien aux entreprises qu'aux individus, car si les premières peuvent se faire \"Uberiser\", les seconds – c'est à dire nous tous – peuvent aussi perdre leur emploi et, comme il le montre, leurs savoirs. En cause : l'automatisation galopante que porte la transformation digitale de nos sociétés et de nos vies.\nAu-delà des constats, ce sont des véritables préconisations thérapeutiques concernant les automatismes digitaux qui seront présentées durant cette session, notamment en portant un discours différent sur ce que l'on peut entendre à propos des \"transformations digitales\".\n\nInformations et inscription sur http://www.usievents.com\n\nSuivez USI sur Twitter : https://twitter.com/USIEvents\nRetrouvez USI sur LinkedIn : http://linkd.in/13Ls21Y\nAbonnez-vous à notre chaine : http://bit.ly/19sPpSp\n\nPlus d'informations sur OCTO Technology : http://www.octo.com",
    "views": "371",
    "rating": "5.00"
  }
]
```

