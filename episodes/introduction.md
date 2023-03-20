---
title: "Software citation"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- Why should researchers cite software?
- How should software be cited?
- What do researchers need to cite software correctly?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Understand what software citation is, and why it is important.
- Understand the principles of software citation.
- Understand what information researchers need to cite software correctly.

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

This episode is relatively heavy on theory.
It may be expedient to provide suitable examples from the domain of the learners.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: How important is software for research?

Which of the following statements is true?

1. 92% of academics use software to conduct their research.
2. 69% of academics say that their research would not be practical without software.
3. 56% of academics develop their own software.


:::::::::::::::::::::::: solution

All statements are true, according to survey data from 2014[^1]!

The fact that "software plays an extremely important role in research"
has been acknowledged not only by the researchers themselves, but also by, e.g.,

- research software engineers (RSEs), i.e., the people that create research software and have
formed their own [national associations](https://researchsoftware.org/);
- research funders: the German Research Foundation (DFG), for example, has issued a whitepaper[^3] that talks about the "fundamental importance of software";
- politics: the quote at the beginning of this sentence is from a report[^2] by the European Commission.


:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 2: Is software a research method, or a research output?

Which of the following statements are true?

1. Software is the implementation of a research method.
2. Software is a research output in its own right.
3. It depends.


:::::::::::::::::::::::: solution 

While *3. It depends.* is certainly true, there are good arguments
for considering software a research output in its own right, in the same
way that academic papers are considered a valid research output.

Software embeds research knowledge. 
It represents and manipulates complex theoretical constructs (e.g., heuristics, methods, models)
that cannot be easily translated into words or equations to include in a paper.[^4]
In order to fully understand and reproduce computational research results,
the software (and data) that was used for the research is needed at least as much,
if not more, than the paper describing or summarizing the results.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::


## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Citing software in research is important for reproducibility, and for giving credit to software authors.
- It is important to cite the software itself, not a paper describing the software.
- A software citation should uniquely identify an accessible persisted copy of the specific version of the software that was used.
- Researchers need to know the software name and list of authors, the version information, and ideally a persistent identifier for the software version they want to cite.

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
[^1]: Simon Hettrick. (2018). softwaresaved/software_in_research_survey_2014: Software in research survey (1.0). Zenodo. https://doi.org/10.5281/zenodo.1183562.
[^2]: European Commission, Directorate-General for Research and Innovation, Osimo, D., Switters, J., Recognising the importance of software in research: Research Software Engineers (RSEs), a UK example, Publications Office, 2019, https://data.europa.eu/doi/10.2777/787013.
[^3]: Deutsche Forschungsgemeinschaft. (2020). The Digital Turn in the Sciences and Humanities. Zenodo. https://doi.org/10.5281/zenodo.4191345.
[^4]: Jay C, Haines R, Katz DS et al. The challenges of theory-software translation [version 1; peer review: 2 approved, 1 approved with reservations]. F1000Research 2020, 9:1192 (https://doi.org/10.12688/f1000research.25561.1).