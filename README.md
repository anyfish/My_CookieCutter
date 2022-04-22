<p align="center">
<a href="https://github.com/anyfish"><img src="https://i.ibb.co/HDt0TSb/anyfish-logo.png" alt="logo-mafl" border="0" width = 200> </a>
</p>
<h1 align=center><font size = 5>Cookiecutter template for<br>custom work environments for analysis.</font></h1>
<br>
<p align='center'>

## Why use it?

● It will speed up your work.
● They will thank you.
● You will thank yourself.
● Routine and automation will reduce decision fatigue.
● Customizing is easier than build from scratch.
● Reproducibility becomes much more feasible.
● Finding things becomes easy.


## Structure of directories and resulting files

    {{ cookiecutter.project_slug }}
        ├── data
        │   ├── external          <- External sources added to the data set.    
        │   ├── processed           <- The final, canonical data sets for modeling.
        │   └── raw                 <- The original, immutable data dump.
        │
        │
        ├── models
        │   └── notebooks           <- Jupyter notebooks. Naming convention is a number (for ordering),
        │                              the creator's initials, and a short `-` delimited description, e.g.
        │                              `1.0-jvelezmagic-initial-data-exploration`.
        │
        ├── utils
        │   ├── project_final       <- Functional summary of the project.  
        │   ├── project_structure   <- Organization of folders and files.
        │   └── visualization       <- Graphs of the relevant results.
        │
        │
        ├── .gitignore              <- Files to ignore by `git`.
        │
        │
        ├── environment.yml         <- The requirements file for reproducing the analysis environment.
        │
        │
        └── README.md               <- The top-level README for developers using this project.
---


This repositorie was made by [@martinfarrera](https://twitter.com/MartinFarrera_), contact me [Linkedin](https://www.linkedin.com/in/martinfarrera/).