---
title: "Création d'une application Shiny et d'un paquet R"
description: "Projet de programmation"
weight: 5
translationKey: "programming tools in data science"
---


Bayer, J., Raffin, R., Vuignier, C. & Lovey, G. (2020). [<span style="color:blue">*Creation of a shiny app and a R package.*</span>](https://myshinyapp.netlify.app)


Au cours du troisième semestre du master en Management et dans le cadre du cours sur les outils de programmation en science des données, on nous a demandé de construire un paquet R qui exécute une application shiny.


![](/Shiny.png)


Le paquet R est disponible [<span style="color:black">**ici**</span>](https://github.com/GaetanLovey/hec_programming_tools_in_data_science/tree/f3e2956e57521a19c0278a595660b44d02f8dd1a/project-G1) ou peut être téléchargé en utilisant le code R suivant: 

```{r}
remotes::install_github(
  "GaetanLovey/hec_programming_tools_in_data_science",
  subdir = "project-G1",
  build_vignettes = TRUE
)
```

Cliquez [<span style="color:black">**ici**</span>](https://mcdonald.shinyapps.io/McDonald/) pour utiliser l'application.
