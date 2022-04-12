# PasteurCanteenDesserts
A Survey of Canteen Desserts at Institut Pasteur

### Contact: Rebecca Stevick, rstevick(at)pasteur.fr

## Contents

Poster: [STEVICK_Pasteurcake_poster_reduced.pdf](STEVICK_Pasteurcake_poster_reduced.pdf)

- Raw data: [PasteurCanteenDesserts.xlsx](PasteurCanteenDesserts.xlsx)  
- R code: [PasteurCanteenDessertsAnalysis.Rmd](PasteurCanteenDessertsAnalysis.Rmd)  
- HTML output: [PasteurCanteenDessertsAnalysis.html](PasteurCanteenDessertsAnalysis.html)
- Github-rendered md output: [PasteurCanteenDessertsAnalysis.md](PasteurCanteenDessertsAnalysis.md)

## About

Lunch is a key aspect of the scientific work day in France, often occurring minutes after loading precious reactions into the “good” PCR machine and ending minutes after the same PCR finishes. There are three components of a well-rounded lunch: entrée, main dish, and dessert. The modern scientist often skips the entrée course, but dessert choice remains crucial to daily happiness and PCR success. At Institut Pasteur (IP), we are blessed with bountiful dessert choices that reflect seasonal and weekly trends. However, the diversity of desserts, chocolate growth patterns, and their associated chantilly toppings are not yet understood.

In this unique study, we conducted a multi-year survey of daily dessert sampling in order to eat our sadness away and address knowledge gaps in canteen dessert choice. Our results will inform decision-making of IP students, post-docs, and the entire scientific community for years to come.

## Methods

### Biased Sampling Technique
The lead author selected a dessert (sometimes 2) from the IP Canteen and sometimes took a photo 4-5 days per week, but missed holidays and the month of August (Fig. 1). A total of 102 desserts were sampled.

### Statistical Methods and Phylogenetic Tree
Metadata were aggregated for each dessert based on the following categories: Animation, Chantilly, Nuts, Chocolate, types of fruit, and type of dessert. All descriptive and statistical analyses were performed in the R statistical computing environment (v4.0.1). A phylogenetic tree was
calculated using choucroute as an outgroup, and colored according to dessert category and/or associated ingredients.

### Small-Sample Dessert Survey
A shared spreadsheet was filled out by 8 IP scientists who have eaten some of the desserts. Each dessert was rated 1-5, with the following guidelines:
1. Would not eat again. Not worth the calories. Do not recommend.
2. It’s edible, but I wouldn’t recommend it. Would eat if last dessert on Earth.
3. It neither contributes nor subtracts from my quality of life.
4. Delicious but missing something. A good choice overall.
