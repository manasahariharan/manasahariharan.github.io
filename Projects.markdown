---
layout: page
aside: true
title: Projects
permalink: /projects/
article_header:
  type: overlay
  theme: light
  align: center
  background_color: '#203028'
  background_image:
    src: /assets/images/allnodesnw.png
aside:
 toc: true

---

### [Spotify Artists](https://github.com/manasahariharan/Genres-Network)


I spend way too much time on Spotify and have always been interested in how seemingly different styles of music are influenced by each other. So I created a network of the genres used to classify artists in Spotify. Spotify has over 4000 genres to describe the music styles of its artists! I collected data on over 80k artists spanning all regions and styles and used cooccurrence of genre tags (multiple genres can be assigned to an artist, beyonce's music can be described as dance pop, pop, r&b or "post-teen pop" ) associated with the artists to build a network of genres. I also used Gephi to cluster and analyse the network. 

This project lets to explore how various common and upcoming genres are related and are influenced by each other. Do check out the blog/code for more information on the process!

[Interacted Visualization](https://manasahariharan.github.io/Spotify-Artists-Network/) 
[Blog discussing my findings](https://medium.com/analytics-vidhya/what-kind-of-music-do-you-listen-to-exploring-the-network-of-spotifys-genres-56d188201a07) 



### [Twitter Sentiment on Clinton vs Trump in 2016 Elections](https://github.com/manasahariharan/Twitter-Sentiment-on-2016-Election-Candidates)

Remember 2016? It was the year of Pokemon Go, and oh, The Election. Nearly all the polls were wrong and Twitter played a huge role in the election. Polls are still being conducted over phone lines and have extremely small sample sizes as a proportion of the population. I felt that our polling tactics need to keep up with advancing technology, and while Twitter is obviously a very noisy source of data, I wanted to see, if in retrospect we can predict the surprising election result by calculating the overall sentiment on Twitter towards the 2 candidates at various points of their campaign. 

In this project, I create a model to scrape tweets related to the candidates and label them using their hashtags. I then used this labeled dataset to compare various algorithms and predict the overall sentiment on twitter related to the candidates (pro-Clinton, anti-Clinton, pro-Trump, anti-Trump) at various points during the election campaign. This project was a part of my final grade for the STAT 578 Course at UIUC. The best F-1 Score was 0.9 with a holdout sample from the labeled dataset using a SGD algorithm with a log loss funstion.



### [Airbnb Boston](https://github.com/manasahariharan/Airbnb)


<video width="800" height="400" controls><source src="/assets/images/proj_final.mp4" type="video/mp4"></video>

Airbnb is a popular platform to find vacation rentals in the city of your choice. For each listing, there are reviews left by guests with ratings on various aspects of their accomodation. In this project, we try to understand the factors that contribute to high ratings. We also created an interactive dashboard using RShiny that lets you choose filters on number of rooms, price, location etc. and browse the available listings in the city of Boston.  



### [Stylome Classification](https://github.com/manasahariharan/Stylome_Classification)

Can we analyze the writing style of an author using Natural Language Processing? Can we identify a character from the kinds of words they use in a novel? I used the novel "Les Liaisons Dangereuses", an epistolary novel (where each chapter is a letter written by on of the characters) to see if we predict the character who wrote the letter based on the features in that chapter's text. We also compared multiple algorithms for prediction and analyze the word patterns of characters.  The best accuracy was 77% obtained with a SVC Classifier using Bigrams as features.