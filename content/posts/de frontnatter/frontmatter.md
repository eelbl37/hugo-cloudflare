---
title: De Frontmatter
date: "2025-02-12"
---

De frontmatter van dit artiekel.

    ---
    title: De Frontmatter
    date: "2025-02-12"
    ---


## Schrijfwijze.

de title  staat niet tussen aanhalingstekens.

de datum staat tussen aanhalings tekens

de description staat tussen aanhalings tekens

De datum is belangrijk of uitzetten.
Teksten met de datum van vandaag worden weergegeven.
Oudere documenten worden ook weergegeven, maar documenten in de toekomst worden niet weergegeven.


## menus

Een menu in de frontmatter werkt alleen tijdens deze pagina.
Menus die altijd weergegeven moeten worden plaats je in de config.yaml

    menu:
     - identifier: categories
       name: categories
       url: /categories/
       weight: 10
     - identifier: tags
       name: tags
       url: /tags/
       weight: 20
     - identifier: about
       name: about
       url: /about/
       weight: 30
     - identifier: menumaken
       name: menumaken
       url: /menumaken/
       weight: 40  