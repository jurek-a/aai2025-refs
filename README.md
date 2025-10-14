# This is my (JG) list of references for AAI MSc at Cranfield 2025 (aaimc-read-code-refs) 

This repository main readme and additional documents contain external references of my selected modules reading lists : 1. SLM, 2. ... etc (will be updated with time)

Note - use at your own risk, this page is a list of references mentioned in the course and is NOT an academic material, comments may include my private sentiments, puns or jokes ] 

See the library managed reading lists as primary source of course material, of course. This readme contains just my notes, for private use and to find quickly author's PDFs and github reops and NOT following the referencing guidelines. In this summary I simply go one level deeper thant the published references in the reading list, verify links and code as of today.

## M01-SLM : Statistical Learning Methods - W02 - 13 OCT 2025

Libary reading list [N-AAI-SLM](https://rl.talis.com/3/cranfield/lists/6600DDA5-EB4C-70FA-0D43-D8F665F9BC18.html?lang=en-GB)

1. Schaum - probability review
   - Some worked out exercises videos are in an iOS or Android app from the publishers [schaums.com](https://www.mheducation.com/highered/campaigns/schaums-outlines.html) - the book is under Mathematics section, the videos of 2-3 worked exercies per chapter for c 1-7, then 1 per 8-10, but none for 11
   - Chapter 11 is a summary of Bayesian methods
   - Basic probability and statistics summary in a concise form, don't expect answers to the "why" questions - it is 100 years of stats theory foundametals summarized on 400 pages. Good as a reference. Lots of exercises, but there is no literature / references section.
     
2. Murphy - PML
   - downloadable book pdf
     - the 2012 version (matlab) - [pml 2012 on EBook Central - with lib login](https://ebookcentral.proquest.com/lib/cranfield/detail.action?docID=3339490)
     - the 2025 version (python) - [pml-book](https://probml.github.io/pml-book/book1.html)
   - code in Matlab - the 2012 edition -- [PMTK](https://github.com/probml/pmtk3)
   - code in Python - the 202x edition - [pyprobml](https://github.com/probml/pyprobml)
   - SLM covers chapters 2, 3, 4, 7 (of the 2012 edition)
     - 2 is Probability
     - 3 is Generative models for discrete data
     - 4 is Gaussian models
     - 7 is Linear regression
  - note that there are other related books by K. Murpy and the current latest published PML reference has extra chapters and chapter numbers shifted (copared to lecture notes slides) and also code in 2012 is matlab and in 2022 is python - here is a quick [PML book 2012-2022 chapters map](murphy-pml-chapters-map.md)

3. Barber - BRML
   - downloadable book pdf [brml](http://www.cs.ucl.ac.uk/staff/d.barber/brml/) - ref as requested by the author, or direct latest as of now [03-2025 version](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/180325.pdf)
   - BRML toolbox (or toolkit) - see the software link on author's book web page
   - SLM AAI module covers chapters 10, 14, 16
     - 10 is Naive Bayes
     - 14 is Nearest neighbour
     - 16 is Supervised linear dimension reduction
  - This book contains a ton of references, lots of exercises and examples. Computer scientist or physicists in nature writing about foundations glossing over detail, and that's maybe just what you need but in order to understand Barber's regurgirated summaries of works of other and how things really work it is actually bettter to read referenced works - for me it was necessary for this "to stick"
  - The supporting example Matlab code is not strighforward, user effort required needs a good review (tbd)

4. ISL - Introduction to Statistical Learning
   - this is a "poor-man's" subset of ESL by Hastie Tibshirani from 2001 (or applied version - stripped of some rigour and theory)
   - PDFs of both the python and R versions of the book are at [statlearning.com](https://www.statlearning.com/)
   - code (python and R) - [ISLP_labs on github](https://github.com/intro-stat-learning/ISLP_labs)
   - SLM AAI module covers chapters 3,4,8
     - 3 is Linear Regression
     - 4 is Classification
     - 8 is Tree-Based Methods

5. Bayesian Networks and Decision Graphs, Jensen & Nielsen, 2007

   - not on the course reading list - my extra basic reading - and very good to read in order to understand parts of BRML
   - pdf online [in a pdf from Springer](https://link.springer.com/book/10.1007/978-0-387-68282-2) (use lib access)
  
## Deeper dive into particular subjects

## 1. Gausian models for SML

- Rasmussen, Williams GPML - [Gaussian Processes for Machine Learning, Carl Edward Rasmussen and Christopher K. I. Williams, 2006](https://gaussianprocess.org/gpml/) - chapters PDFs for download 
