---
title: "Software citation"
teaching: 10
exercises: 3
---

:::::::::::::::::::::::::::::::::::::: questions 

- Why should software be cited?
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

The first two challenges in this episode can be considered optional.
They prepare the argumentative grounds for the necessity of software citation
by creating an understanding of software as a research output
that needs to be treated on par with papers.

If learners are aware of this already, the following challenges can be skipped.

This episode is also relatively theoretical.
It may be expedient to provide suitable examples from the domain of the learners.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Over the last decades, research in almost all disciplines has become increasingly digitalized.
Research data is often created, processed, analyzed and visualized using dedicated research software.
Research software also enables complex simulations and modeling.
And without software, we would not be able to understand and build the machine learning models
that increasingly support the utilization of large data sets.

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

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Software as a research output

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Research software embeds research knowledge. 
It represents and manipulates complex theoretical constructs (e.g., heuristics, methods, models)
that cannot be easily translated into words or equations to include in a traditional paper.[^4]

In order to fully understand and *reproduce* computational research results,
the software (and data) that was used for the research is needed at least as much,
if not more, than the paper describing or summarizing the results.

This makes software a valid research output in its own right.
Consequently, research software should be treated the same as other outputs
in the research lifecycle.

For us as researchers, this means that when we report our research and results 
(for example in a paper),
we must provide information about the research software that we have used,
in the same way that we must provide information about other research outputs
that our own research builds on.
Traditionally, we provide this information by citing artifacts of previous
and related work, usually peer-reviewed publications.

The method of *citation* has been formalized and used for a long time [TODO link].
During our education as researchers, we usually learn early on how to cite other work.

It therefore makes sense to apply the method of citation to all forms of research output,
including research data and software.
::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Research software often implements complex theoretical constructs.
This makes software a valid research output that should be treated the same
as other research outputs.

Furthermore, to be able to fully **understand** these constructs,
and **reproduce computational research** and its results, 
we need access to the software it has been conducted with.

This means that research software should be cited when reporting research and results in papers and other publications.

The citation of traditional text publications is a well-established practice,
but it is less well-known how to apply this practice to software.

## The principles of software citation

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor
Software differs from traditional text outputs in a number of ways:

- Papers usually have a final state: the peer-reviewed, accepted and published version.
Software is often developed dynamically, and many versions exist, of which some may be
labeled as stable snapshot, and promoted to a release version.
- Each software version may have a different set of authors and contributors, 
whereas published papers have a fixed set of authors and contributors.
- An iteration on a paper is considered a new, separate paper.
An iteration on a software version is still considered the same software.
- While papers, as peer-reviewed text publications, are firmly established as citable outputs,
the status of research software as citable output is still not universally accepted.
- Paper publications and citations to papers have long served as a means of evaluating research,
and scholarly credit is currently still based mostly on paper-related metrics. Normative, legal
attribution to paper contributors is solved through established guidelines for authorship, e.g.,
by academic institutions, funders [TODO cite DFG] or domain-specific committees such as the 
International Committee of Medical Journal Editors [TODO cite https://www.icmje.org/recommendations/browse/roles-and-responsibilities/defining-the-role-of-authors-and-contributors.html].
Currently, there is no well-established practice of evaluation based on research software,
nor universally accepted norms for scholarly credit and attribution.[TODO but: Helholtz guidelines]
- The process of paper publication is well-defined and widely followed,
including peer-review, archiving, and assigning persistent identifiers to papers.
In contrast, we have only begun to understand the requirements for a similar publication process for software,
and there is not yet a universally accepted definition of software publication.[TODO but: HERMES]

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Software differs from traditional text outputs in a number of ways:

- Software is usually developed dynamically, and has no "camera-ready" or final version.
- Software authors may differ between versions.
- Different software versions are still considered the same software.
Iterations on papers are usually considered separate papers.
- Software is not yet universally considered a citable output.
- Software does not play the same role as papers in academic evaluation.
- The process of publishing a paper is well-known, but the requirements and process of software publication are currently less well understood.

Software citation must consider these differences.
The software citation principles have been defined accordingly in a paper by Smith et al. (2016)[^5]:

1. **Importance:** Software should be considered a legitimate and citable research output.
It should be cited on the same basis as any other research output such as a paper or a book.
2. **Credit and attribution:** Software citations should facilitate giving scholarly credit and normative, 
legal attribution to all software authors.
3. **Unique identification:** Software citations should include a method for machine-actionable unique identification of the software.
4. **Persistence:** Unique identifiers and metadata describing the software should persist - even beyond the lifespan of the software they describe.
5. **Accessibility:** Software citations should make it possible to access the software and its associated metadata and resources (documentation, data, etc.).
6. **Specificity:** Software citations should allow identification of and access to the specific version of the software that was used.

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 3: How to cite software correctly

Which of the following software citations adhere to the software citation principles?

1. [...] *To analyze our data, we used Microsoft Excel (Office 2019, Microsoft, Redmond, WA, USA). The analysis shows* [...]

---

2. [...] *To analyze our data, we used Pandas 1.5.3 (McKinney 2010). The analysis shows* [...]<br/>
<br/>
**References**<br/>
W. McKinney, "Data Structures for Statistical Computing in Python," Proceedings of the 9th Python in Science Conference, pp. 56–61, 2010, doi: 10.25080/Majora-92bf1922-00a.

---

3. [...] *To analyze our data, we used Pandas (The pandas development team 2023). The analysis shows* [...]<br/>
<br/>
**References**<br/>
The pandas development team. (2023). pandas-dev/pandas: Pandas (v1.5.3). Zenodo. https://doi.org/10.5281/zenodo.7549438.

:::::::::::::::::::::::: solution 

**Example 1.** This is not a software citation at all, but rather an in-text *mention* of the software, 
using a format similar to what is commonly used to specify a scientific instrument that was used for the research.

Also, although some version identification was provided ("Office 2019"), the information is not specific enough to
identify the exact software version that was used. This mention also neither provides a unique identifier nor
makes the exact software version accessible.

A better (but not optimal) way of software citation would have looked like this:

<div style="padding-left:5%">
[...] *To analyze our data, we used Microsoft Excel (Microsoft 2019). The analysis shows* [...]<br/>
<br/>
**References**<br/>
Microsoft (2019), Microsoft Excel (version 1808 (Build 10396.20023 Klick-und-Los)). Redmond, WA, USA. https://learn.microsoft.com/de-de/officeupdates/update-history-office-2019.
</div>

Note that it is hard to link to an exact version of Excel.
This makes it nearly impossible to reliably reproduce the analysis that is reported in this paper.
Perhaps Excel is not the optional choice for data analysis?

**Violated software citation principles:** Importance, Unique identification, Accessibility, Specificity

---

**Example 2.** Although the text mentions a specific version, and the respective reference lists the author and provides a unique identifier (a Digital Object Identifier, or DOI),
the reference itself is to a paper describing the software, not the software itself.

A better way of software citation would have looked like this:

<div style="padding-left:5%">
[...] *To analyze our data, we used Pandas 1.5.3 (McKinney 2010). The analysis shows* [...]<br/>
<br/>
**References**<br/>
W. McKinney, "Data Structures for Statistical Computing in Python," Proceedings of the 9th Python in Science Conference, pp. 56–61, 2010, doi: 10.25080/Majora-92bf1922-00a.
</div>

**Violated software citation principles:** Importance

---

**Example 3.** The example uses the information provided by the software authors themselves (see [this archived snapshot of the pandas citation page](http://web.archive.org/web/20230322145850/https://pandas.pydata.org/about/citing.html)). 
Although this example does not have the same issues as the previous ones, the author information is problematic,
as it does not facilitate giving credit and attribution to the individual authors directly.
Tracking individual authors for each software version can be complicated and tedious,
and there is not yet a good general definition of what constitutes software authorship to begin with.
However, in the context of software citation it would be better practice to do the work of defining individual authors for each software version.


**Violated software citation principles:** Credit and attribution

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Citation metadata

We need some very specific metadata
to correctly cite a software version.
The main question is, where do we get these metadata from?
Unlike a paper, software usually does not have a title page that provides all the correct metadata.

::::::::::::::::::::::::::::::::::::: challenge

## Citing an example software

Imagine that you are writing a paper about time spent in space as a comorbidity factor in astronauts.
In search of software that you can use to analyse your data, you have found
an open source Python script.
You can successfully reuse the software to analyse your data, and want to cite it
in your paper.

Based on the contents of the GitHub repository you cloned the script from,
how would you cite it according to the software citation principles?
You can find the repository at https://github.com/sdruskat/astronaut-analysis.

:::::::::::::::: solution

It is really hard to cite the script according to the software citation principles, as we cannot be sure about the correct citation metadata:

- **What is the name of the software, seeing that the repository contains data, software *and* results?** Is it "Astronaut Analysis", is it "Astronaut Analysis Script", or is it "astronaut-analysis.py"?
- **Who are the authors of the software?** There is one contributor called "schlauch" in the commit history, but what is their full name? And what about the owner of the repository, "sdruskat"?
- **What is the version of the software that has been used for the analysis?** There are no tags and no releases on the GitHub page.
- **What is the persistent identifier of the software?** There is no hint that this software even has a persistent identifier.

The best we can do with regard to a maximally correct citation of the script is something like this:

> The Astronaut Analysis developers (2021): Astronaut Analysis code (commit 66bc52d49262f0b9034ddc690df6d1cdfff9e7b8). https://github.com/sdruskat/astronaut-analysis/commit/66bc52d49262f0b9034ddc690df6d1cdfff9e7b8.

The "publication date" is the date of the last commit to the GitHub repository, and we can extract the full commit identifier from the URL of the last commit.

:::::::::::::::::::::::::
:::::::::::::::::::::::::::::::::::::::::::::::

The answer to this question is that, just like with a paper, the software authors must provide the metadata themselves.
These must minimally include:

- A list of the software authors,
- the name of the software,
- the version of the software,
- a method to access the software version to be cited, ideally through a persistent unique identifier such as a DOI.

These metadata should be provided together with the source code of the software,
usually in a publicly accessible source code repository.

While the software citation metadata could simply be included in the documentation,
for example as a plain text or ${\rm B{\small IB}\TeX}$ reference snippet in a README file,
this makes it hard or impossible to reliably extract and process the metadata.

Instead, the metadata should be provided in a way that is readable for both humans and machines.
The [Citation File Format (CFF)](https://citation-file-format.github.io) provides a format to do this in a software citation metadata file.

::::::::::::::::::::::::::::::::::::: keypoints 

- Citing software in research is important for reproducibility, and for giving credit to software authors.
- It is important to cite the software itself, not a paper describing the software.
- A software citation should uniquely identify an accessible persisted copy of the specific version of the software that was used.
- Researchers need to know the software name and list of authors, the version information, and ideally a persistent identifier for the software version they want to cite.

::::::::::::::::::::::::::::::::::::::::::::::::

[^1]: Simon Hettrick. (2018). softwaresaved/software_in_research_survey_2014: Software in research survey (1.0). Zenodo. https://doi.org/10.5281/zenodo.1183562.
[^2]: European Commission, Directorate-General for Research and Innovation, Osimo, D., Switters, J., Recognising the importance of software in research: Research Software Engineers (RSEs), a UK example, Publications Office, 2019, https://data.europa.eu/doi/10.2777/787013.
[^3]: Deutsche Forschungsgemeinschaft. (2020). The Digital Turn in the Sciences and Humanities. Zenodo. https://doi.org/10.5281/zenodo.4191345.
[^4]: Jay C, Haines R, Katz DS et al. The challenges of theory-software translation [version 1; peer review: 2 approved, 1 approved with reservations]. F1000Research 2020, 9:1192 (https://doi.org/10.12688/f1000research.25561.1).
[^5]: Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working Group. 2016. Software citation principles. PeerJ Computer Science 2:e86 https://doi.org/10.7717/peerj-cs.86 