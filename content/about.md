---
title: deploy hugo site
date: "2024-06-15"
---



## Deploy hugo site met cloudflare


Een hugo project deployen met cloudflare.

Voor deze test heb ik een kleine site gemaakt.

open een nieuw project
voeg een theme toe als submodule. Een theme copieren naar de theme dir in je project geeft bij de deploy een error.

Pagina met stappenplan:
https://blog.jobins.jp/deploying-a-static-website-on-cloudflare-pages-using-the-hugo-framework


## Github

maak in github een nieuw project aan.
Voer een passende naam in, verder alles overslaan zo laten, en druk op create.


## In je project

In je project local voer je onderstaande opdrachten uit.


    echo "# hugo-cloudflare" >> README.md
    git init  # overslaan moest al bij toevoegen theme via submodule
    git add README.md   # maken
    git commit -m "first commit"    # Alleen de readmefile!!
    git branch -M master
    git remote add origin git@github.com:eelbl37/hugo-cloudflare.git  # ssh pad naar de repo
    git push -u origin master



