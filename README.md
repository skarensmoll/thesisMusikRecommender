# MusikRecommender

This is a novel approach to recommend music through the use of chord progressions and music features.
The approach is levereging machine learning clustering and distance algorithms to make recommendations. 

To add some context here, deep learning algorithms still present difficulties to detect accurately chords.

Additionally, most of the music recommendation systems out there are leveraging other's users input rather than pure musical aspects to recommend music
which sometimes creates an umbalanced environment for new artist trying to expose their music for the world. Since normally these algorithms 
based their recommendation on items that have been already played by a user; it drives us to the next problem: **The cold start problem**.

The cord start problem is known as users for who the system does not have historical information about their preferences because its their first time
interacting with the tool, therefore, it is extremely difficult to recommend something with the existing approaches such as: collaborative filtering, 
or content based filtering.


### How this repo is structured:

1. The folder `experiments` holds files named with numbers which try to follow the [CRISP-DM](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining) methodology,
   There is a Data Understanding, Data Preparation and Modeling stage.
2. Since the idea is to iterate and try different approaches that could bring the best results, this project will hold different git-branches, with slight changes
   that could be in either of the different stages of the CRISP process


## Overall approach

1. Data has been scrapped from [https://www.ultimate-guitar.com/](this web site), since a song can have a sequence like this C, D, Eb, F for instance, a 2D 
2. transition matrix has been created.
