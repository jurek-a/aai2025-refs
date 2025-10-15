# JGs ist of references (reading material and code repos) from AAI MSc course at Cranfield 2025

Welcome to the AAI books jungle. This repository's main README.md and additional documents provide overview and links to external references mentioned in the lectures and reading lists of my AAI selected modules.

Notes : I hope this is helpful to the more inquisitive but .. use at your own risk !  
- This repo is guaranteed to exist (only) until the end of the calendar year 2025 at its primary address [https://github.com/jurek-a/aai2025-refs](https://github.com/jurek-a/aai2025-refs). In 2026 those literature notes repo might be deleted, or converted to a gist, or disappear. We will see.
- This is NOT intended to be academic material, just a quick way to find mentioned books, chapters and articles, my comments may include my private sentiments, puns or jokes and book references are not necessarily in the mandated referencing style.
- See the library managed reading lists as primary source of course material, of course. 
- I often go one level deeper than in the course's published reading lists references, trying to reach sources and fully understand content, and the links to pdfs and code have been verified as I have added them here only after accessin each resource myself.

## M01 : SLM : Statistical Learning Methods - W02 - 13 OCT 2025

Libary reading list [N-AAI-SLM](https://rl.talis.com/3/cranfield/lists/6600DDA5-EB4C-70FA-0D43-D8F665F9BC18.html?lang=en-GB)

1. Schaum - probability review
   - Some worked out exercises videos are in an iOS or Android app from the publishers [schaums.com](https://www.mheducation.com/highered/campaigns/schaums-outlines.html) - the book is under Mathematics section, the videos of 2-3 worked exercies per chapter for c 1-7, then 1 per 8-10, but none for 11
   - Chapter 11 contains a summary of Bayesian methods - skip to that to start with background for bayesian methods
   - Basic probability and statistics summary in a concise form, don't expect answers to the "why" questions - it is 100 years of stats theory foundametals summarized in 400 pages. Good as a reference. Lots of exercises, but there is no literature / references section. 
     
2. Murphy - PML (book0, 2012)
   - See clarification about Murphy's three books updates/s and changes in [PML books 2012-2022-2023 chapters map](murphy-pml-chapters-map.md)
      - the authors links to all editions [probml.github.io/pml-book](https://probml.github.io/pml-book/)
   - downloadable pdfs
     - the 2012 version (the original book which uses matlab code) - [pml 2012 on EBook Central - with lib login](https://ebookcentral.proquest.com/lib/cranfield/detail.action?docID=3339490) (you need academic openathens login)
     - the 2025 edition (code converted to python) - [pml-book](https://probml.github.io/pml-book/book1.html) - note that in this edition some chapters have been added and some removed !
   - code in Matlab - the 2012 (book0) edition -- [PMTK](https://github.com/probml/pmtk3)
   - code in Python - the 2022 (book1) edition - [pyprobml](https://github.com/probml/pyprobml)
   - SLM covers chapters 2, 3, 4, 7, 14, 15, 18 (of the orginal pml 2012 edition)
     - 2 is Probability
     - 3 is Generative models for discrete data
     - 4 is Gaussian models
     - 7 is Linear regression
     - 14 is Kernels
     - 15 is Gaussian processes
     - 18 is (EKF, UKF)
 
3. Barber - BRML
   - downloadable book pdf [brml](http://www.cs.ucl.ac.uk/staff/d.barber/brml/) - ref as requested by the author, or direct latest as of now [03-2025 version](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/180325.pdf)
   - BRML toolbox (or toolkit) - see the software link on author's book web page
   - SLM AAI module covers chapters 10, 14, 16
     - 10 is Naive Bayes
     - 14 is Nearest neighbour
     - 16 is Supervised linear dimension reduction
  - This book contains a ton of references, lots of exercises and examples. Computer scientist or physicists in nature writing about foundations glossing over detail, and that's maybe just what you need but in order to understand Barber's summaries of works of others and truly understand how things really work it was bettter (for me) to read referenced works instead
  - The supporting example Matlab code is not maintained, not strighforward, user effort required needs a good review/rework

4. ISL - Introduction to Statistical Learning
   - this is a "poor-man's" subset of ESL by Hastie Tibshirani from 2001 (or an "applied" version - stripped of some rigour and theory, simplified)
   - PDFs of both the python version and R versions of the book are at [statlearning.com](https://www.statlearning.com/)
   - code (python and R) - [ISLP_labs on github](https://github.com/intro-stat-learning/ISLP_labs)
   - SLM AAI module covers chapters 3,4,8 (and maybe more)
     - 3 is Linear Regression
     - 4 is Classification
     - 8 is Tree-Based Methods

( Extra ) 5. Bayesian Networks and Decision Graphs, Jensen & Nielsen, 2007

   - not on the main course reading list - my extra basic reading - and wortwhile to read in order to understand parts of BRML
   - pdf online [in a pdf from Springer](https://link.springer.com/book/10.1007/978-0-387-68282-2) (use academic lib access)
  
## Deeper dive into particular subjects

## 1. Gausian models for SLM

- Rasmussen, Williams GPML - [Gaussian Processes for Machine Learning, Carl Edward Rasmussen and Christopher K. I. Williams, 2006](https://gaussianprocess.org/gpml/) - chapters PDFs for download
  
## 2. Bayesian Networks

- Code of Bayes Net Toolbox [bayesnet.github.io - Usage](https://bayesnet.github.io/bnt/docs/usage.html#basics) , source [github.com/bayesnet/bnt](https://github.com/bayesnet/bnt)


# Additional - level 2 books links

[slm-book-links](slm-book-links.md)
