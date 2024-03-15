
```mermaid
%%{init: {"flowchart": {"htmlLabels": true}}}%%
%%{init: {'theme': 'forest'}}%%

flowchart LR
    English[<b>English</b>] --> European-Central1[<b>German<br>French<br>Spanish</b>]
    European-Central1       --> European-Central2[<b>German</b><br>Dutch<br>Polish<br>Esperanto]
    European-Central1       --> European-Latin[<b>Spanish</b><br>Portuguese<br>Italian<br>Latin]
    European-Central2       --> European-North[Danish<br>Swedish<br>Norwegian<br>Icelandic]
    European-Central2       --> European-East1[<b>Russian</b><br>Ukrainian<br>Finnish]
    European-Central2       --> European-East2[Romanian<br>Hungarian<br>Czech]
    European-Latin          --> Mediterranean[Greek<br><b>Turkish<br>Arabic</b>]
    Mediterranean           --> Asian-West[<b>Arabic<br>Persian</b><br>Hebrew]
    Asian-West              --> Asian-South[<b>Hindi<br>Bengali<br>Urdu<br>Tamil<br>Punjabi</b>]
    Chinese[<b>Chinese</b>] --> Asian-East[<b>Japanese<br>Korean<br>Cantonese</b>]
    Asian-East              --> Asian-SouthEast[<b>Vietnamese<br>Thai<br>Indonesian<br>Javanese</b>]

    style English           fill:#FF9
    style European-Central1 fill:#FF9
    style European-Central2 fill:#FF9
    style European-Latin    fill:#FF9
    style European-East1    fill:#FF9
    style Mediterranean     fill:#FF9
    style Chinese           fill:#FF9
    style Asian-East        fill:#FF9
```

Notes:

* **Bold** languages are among top 40 by total number of speakers according to wikipedia: https://en.wikipedia.org/wiki/List_of_languages_by_total_number_of_speakers
* Reference: https://www.theguardian.com/education/gallery/2015/jan/23/a-language-family-tree-in-pictures
