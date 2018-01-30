# Spring 2018
# Project 1:  Spooky Textual Analysis

## Project Description
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Spring 2018

+ Project title: Understanding gender and character actions in the 19th century horror novels 
+ This project is conducted by Wanting Cheng, Columbia(UNI: wc2628)

+ Project summary: In this project, I explore the relationship between character gender and character actions in the context of horror stories written in the 19th century by three authors. I study the ratio of male vs. female in each author, the popular action words associated with male and female characters, and use clustering methods to analyze the difference in the portrayal of gender roles.

## 1. Introduction and Data
  I've always been interested in whether authors portray their male and female characters differently, and have taken classes where the professor discussed how gender roles are largely different in the 19th century. This project provides me with a great opportunity to approach this question from a more quantitative perspective. In particular, I'm also curius about whether the gender of the author make a difference on how s/he depict gender roles, since we have two male authors (EAP, HPL) and one female author (MWS). 
  This project seeks to answer the following questions:
  + How does the occurence of pronouns look? Does the female author talk more about female characters?
  
  + Which verbs or words are most associated with male and female characters? What do male and female characters do in novels written by each author?
  
  + Is there a way to guess the gender of the character given a word, a token, a sentence?
  
  Regarding Spooky data, we are given 19579 sentences in total, each written by an author among  Edgar Allan Poe (EAP), HP Lovecraft (HPL), and Mary Shelley (MWS). In the data file, EAP has 7900 sentences, HPL has 5635 sentences, and MWS has 6044. For this study I defined two classes of pronouns: the male pronouns were "he" and the female pronouns were "she". I then used tidy data principles and n-grams to get the word following the pronouns, and treated them as the character actions.

## 2.
  
