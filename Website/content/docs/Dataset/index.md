---
title: 'The Dataset'
date: 2019-02-11T19:27:37+10:00
weight: 1
---

The dataset is from [southpark.fandom.com](https://southpark.fandom.com/) where we download all character pages and episode scripts. A character link to another character if the other character is mentioned in its character page. This way a digraph can be created for characters that interact with each other. In the bottom of all character pages their category is displayed. This has also been scraped from the fandom wiki. All this information can be found in a csv file at our github page. Follow the link [here](https://github.com/koldbrandt/socialgraphs/blob/main/characters.csv).  

All scripts from the show has also been downloaded to be able to do sentiment analysis and a network showing which characters that has been apart of which episode. This is two different files, where the first one includes information about the episodes, and the other one containing all the spoken lines in the episodes. The episode information dataset can be found [here](https://github.com/koldbrandt/socialgraphs/blob/main/episodes.csv) and the file with all the lines can be found [here](https://github.com/koldbrandt/socialgraphs/blob/main/lines.csv).