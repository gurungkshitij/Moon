---
layout: post
title:  "College Scoreboard: PCA and k-means clustering"
date:   2020-05-06
excerpt: "<b>Unsupervised learning</b> techniques to study private colleges around the U.S: <b>R</b>"
feature: https://dficlub.org/wp-content/uploads/2019/11/FR-DeBrusk-Machine-Learning-Bots-Risk-1200.jpg
comments: true
---
   
## Introduction:

In this project, I attempt to classify, compare, and study 135 different private colleges in the U.S. bsaed on 14 different variables like admission rate, averaet SAT score, percentage of white and non-white, faculty salary, etc. I implement unsupervised learning techniques like Principal Component Analysis (PCA) and K-means clustering to achieve my goal. 

### Main goal of this project:
- Implement PCA to identify qualitative features of the U.S. colleges 
- Determine the candidate for optimal number of clusters using elbow plot
- Use k-means clustering on top of PCA to classify, compared, and observe any patters among colleges

### How users can get started with the project?
- [CollegeScoreboard.Rmd](https://github.com/gurungkshitij/collegeboard_pca_cluster/blob/master/CollegeScoreboard.Rmd) is the main file
- [Download](https://github.com/gurungkshitij/collegeboard_pca_cluster.git) all the files and change the directory of the data
as you read in Colleges2015.csv. 
- Run the CollegeScoreboard.Rmd
- The final report is [CollegeScoreboard.pdf](https://github.com/gurungkshitij/collegeboard_pca_cluster/blob/master/CollegeScoreboard.pdf)

<a href="https://github.com/gurungkshitij/collegeboard_pca_cluster.git" class="btn btn-success"> Source code</a>

<hr>
<figure class="half">
    <a href='/assets/img/pca.jpg'><img src='/assets/img/pca.jpg'></a>
    <a href='/assets/img/cluster_col.jpg'><img src='/assets/img/cluster_col.jpg'></a>
    <figcaption> fig: Clustering results</figcaption>
</figure>
        
