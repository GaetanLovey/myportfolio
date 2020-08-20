---
title: "Gaëtan Lovey"
output:
  html_document: 
    css: columns.css
  pdf_document: 
    keep_tex: true
    includes:
      in_header: columns.tex
  beamer_presentation: 
    keep_tex: true
    includes:
      in_header: columns.tex
---
<center> 
# About me

> I obtained my bachelor in Business Administration from HES-SO Valais/Wallis in 2018. 
> I am currently doing a master's degree in management at HEC Lausanne. 

</p></center>


<p align="center">
  <img src="/profile.png" width="200" height="300"/>
</p>

<p>&nbsp; </p>

<center>  

#### **Education** 

<i class="fas fa-graduation-cap fa-pulse"></i> MSc in Management, en cours de formation
  <br/>*HEC Lausanne*

<i class="fas fa-graduation-cap"></i> BSc in Business Administration, 2018
  <br/>*HES-SO Valais/Wallis*
  
</p></center>

<p>&nbsp; </p>

<center> 
[<i class="fas fa-folder fa-2x"></i> <br/>CV](https://glovey.netlify.app/en/curriculum-vitæ/)
</p></center>


:::::: {.cols data-latex=""}

::: {.col data-latex="{0.55\textwidth}"}
#### **Education** 

<i class="fas fa-graduation-cap fa-pulse"></i> MSc in Management, en cours de formation
  <br/>*HEC Lausanne*

<i class="fas fa-graduation-cap"></i> BSc in Business Administration, 2018
  <br/>*HES-SO Valais/Wallis*
  
</p></center>


:::

::: {.col data-latex="{0.05\textwidth}"}
\ 
<!-- an empty Div (with a white space), serving as
a column separator -->
:::

::: {.col data-latex="{0.4\textwidth}"}
#### **Interests** 
- Footbal
- Ski

:::
::::::


# Two columns

Below is a Div containing three child Divs side by side. The Div
in the middle is empty, just to add more space between the left
and right Divs.

:::::: {.cols data-latex=""}

::: {.col data-latex="{0.55\textwidth}"}
```{r, echo=FALSE, fig.width=5, fig.height=4}
par(mar = c(4, 4, .2, .1))
plot(cars, pch = 19)
```
:::

::: {.col data-latex="{0.05\textwidth}"}
\ 
<!-- an empty Div (with a white space), serving as
a column separator -->
:::

::: {.col data-latex="{0.4\textwidth}"}
The figure on the left-hand side shows the `cars` data.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
enim ad minim veniam, quis nostrud exercitation ullamco laboris
nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor
in reprehenderit in voluptate velit esse cillum dolore eu fugiat
nulla pariatur.
:::
::::::
