---
title: "Quick References - Useful Functions R"
author: "Femke van der Pol"
output: 
  html_document: 
    highlight: zenburn
    theme: journal
---

# Useful Functions
Some generalised useful functions in R

## HTML output design
**R-chunks arguments** 

``` r
eval=FALSE
```
Prints the literal code, does not produce a computation


``` r
echo=FALSE
```
Prints the computation only, not the literal code


``` r
include=FALSE
```
prevents code and results (a chunk) from appearing in the finished file.

the function `echo=F`prints the computation only

---

## Statements

**If...else**

``` r
if (TRUE) { 
  message <- "I execute this when true!"
} else {
  message <- "I execute this when false!"
}

print(message)

#example
weather <- 'cloudy'
high_chance_of_rain <- TRUE

if (weather == 'cloudy' & high_chance_of_rain){ 
  message = "Pack umbrella!"
} else {
  message = "No need for umbrella!"
}

print(message)
```
Here, whichever argument is within the brackets, will determine which one of the actions in the {} will be executed.

For within the brackets, you can use "&" as AND operator, "|" as OR operator and "!" as the NOT operator. 

# Keyboard Shortcuts
|Keyboard shortcut | Result| 
|------------------|:-------:|
| Alt + - | <- |
| Crtl + Shift +M| %>%



*Last updated: 31-08-2025*

**Tags for searching:** #cheatsheet #functions #quick_reference
