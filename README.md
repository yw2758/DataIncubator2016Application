#DataIncubator2016Application
This repo is dedicated for Data Incubator 2016 Application 

### Project: NYC Housing recommendation system for school or university seekers among parents

The goals for this repo are
- exploratory data analysis
- making recommendation for parents using open data from NYC including crime records, motor vehicle collisions records and hospital records
- implementing shiny app for visulazation

This repo has been organized as follows.
```
proj/
├── lib/
├── data/
├── doc/
├── figs/
├── lib/
└── output/
```

* 2 plots were put under figs file

The recommendation system is mainly based on 3 components: school community crime rate, motor collision rate and hospital convenience.
All of the data source is public and easy to download.

The initiative behind this project is based on my own education experience. My family is fully devoted to my personal education and my parents really spent quite a long time gathering information about all schools in our city because they had to consider every aspects of a particular when it comes to deciding the best school for me. It's hare to dig out safety and healthcare information and issues about a school,however,despite the ranking or teachers' background of a particular school is easy to follow up on government websites.
Therefore recently I came up with this idea to incorporate those things of my parent's concern and make it into a comprehensive school or university recommendation system.

The basic principle behind this system is KNN clustering methods.

The total size of these data source is around 1.5GB, which is not too big to handle in R environment.

The final format of this project will be in Shiny app. For further improvement it could be realized on Ruby platform.
