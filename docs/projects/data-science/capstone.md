---
tags:
  - Social Networks
  - Deep Learning
  - Graph Neural Networks
  - Link Prediction
  - Python
  - Coursework
---

<div style="display: flex;">

<img align="left" height="120" width="120" src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/capstone/trace-bg.svg" />

<div>
Textual and Relational Analysis of Community Extremism (TRACE) is my capstone project together with my groupmates as Bachelor of Science in Data Science students. Its primary goal is to model user-tweet interactions in Twitter / X and find out which users are more likely to interact with extremist tweets.
</div>
</div>

[Website :material-web:](https://capstone2-mvp3-frontend-cfworkers.chrisgari.workers.dev){ .md-button }
[GitHub :simple-github:](https://github.com/iragca/capstone-project-2){ .md-button }

=== "Paper"

    <embed src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/capstone/trace.pdf"
    type="application/pdf"
    width="100%"
    height="800px"
    />

=== "Website"

    <img src="https://pub-2605a5350a664b7cad96b61a19778380.r2.dev/capstone/website.png">

## Methodology

- Retrieve training data through web-scraping and API access
- Use a self-hosted [PocketBase](https://pocketbase.io/) instance to store datasets
- Use Graph Neural Networks to model user-tweet relationship
- [MLFlow](https://mlflow.org/) for recording experiments

## Metrics

- 88.7% accuracy in predicting an interaction (reply) between a user and a tweet
