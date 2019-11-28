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

## Useage

The user is expected to edit the preamble.tex file only. Please provide the following arguments:

``` 
\newcommand{\yname}{Your name}
\newcommand{\fname}{Father's name}
\newcommand{\yroll}{Roll number}
\newcommand{\dept}{Department}
\newcommand{\org}{Hall}
\newcommand{\insti}{Indian Institute of Technology Kharapur }
\newcommand{\lost}{argument}
\newcommand{\ldate}{date of incident}
\newcommand{\ltime}{Time of incident in 24 hour format}
```
The seventh line (19th line in the real file) in the above code accepts the following arguments:
i = id card
m = medical book
p = passport
w = wallet
mo = money
vo = voter id
ht = hall ticket
atm = atm card
pb = pass book
dl = driving license

For example, if the user wants to report the missing of atm card, s/he is expected to edit the line seven as:
```
\newcommand{\lost}{atm}
```
## Compiling 

The following code may be used in a Linux terminal to compile the code. The command also deletes the .log and .aux files. Necessary corrections may be made to this command if you wish to retain these files.

```
pdflatex application.tex && rm application.aux && rm application.log && rm preamble.aux
```

## Suggestions and criticism are welcome :+1:
