# GD Entry Application

This is a latex repo to create an application letter addressed to the officer in charge at the IIT Kgp police station requesting the creation of a General Diary (GD) Entry.

This repo can be used to report the theft or missing of 

1. Institute Id card
2. Medical book
3. Passport
4. Wallet
5. Money
6. Voter id
7. Hall ticket
8. Atm card
9. Pass book
10. Driving license

##Useage

The user is expected to edit the preamble.tex file only. Please provide the following arguments:

``` 
\newcommand{\yname}{Your name}
\newcommand{\fname}{Father's name}
\newcommand{\yroll}{Roll number}
\newcommand{\dept}{Department}
\newcommand{\org}{Hall}
\newcommand{\insti}{Indian Institute of Technology Kharapur }
% i = id card
% m = medical book
% p = passport
% w = wallet
% mo = money
% vo = voter id
% ht = hall ticket
% atm = atm card
% pb = pass book
% dl = driving license
\newcommand{\lost}{argument}
\newcommand{\ldate}{date of incident}
\newcommand{\ltime}{Time of incident in 24 hour format}
```
