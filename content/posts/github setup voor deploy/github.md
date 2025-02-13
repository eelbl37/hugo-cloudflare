---
title: Github setup 
date: "2025-02-12"
---




Pagina met stappenplan:
https://blog.jobins.jp/deploying-a-static-website-on-cloudflare-pages-using-the-hugo-framework




Na het bewerken aanpassen van je site de volgende stappen uitvoeren
om de wijzigingen op github te plaatsen.






In je project local voer je onderstaande opdrachten uit met git


    echo "# hugo-cloudflare" >> README.md
    git init  # overslaan moest al bij toevoegen theme via submodule
    git add README.md   # de README.md 
    git commit -m "first commit"    # Alleen de readmefile!!
    git branch -M master
    git remote add origin git@github.com:eelbl37/hugo-cloudflare.git  # ssh pad naar de repo
    git push -u origin master



Nu is alleen de REAME.md file  geupload naar github.

Maak een eerste post en een menu, voeg wat tekst toe



## deploy hugo site with cloudflare


# Before you continue

All of the framework guides assume you already have a fundamental understanding of
Git. If you are new to Git, refer to this summarized Git handbook on how to set
up Git on your local machine.

If you clone with SSH, you must generate SSH keys on each computer
you use to push or pull from GitHub.

Refer to the GitHub documentation  and Git documentation for more information.

Go to Deploy with Cloudflare Pages if you already have a Hugo site
hosted with your Git provider.


# Deploy with Cloudflare Pages

To deploy your site to Pages:

  -  Log in to the Cloudflare dashboard and select your account.
  -  
  -  In Account Home, select Workers & Pages > Create application > Pages > Connect to Git.
  -  
  -  Select the new GitHub repository that you created and, in the Set up 
    builds and deployments section, provide the following information:


# Configuration option    Value

    Production branch       main
    Build command           hugo
    Build directory         public
