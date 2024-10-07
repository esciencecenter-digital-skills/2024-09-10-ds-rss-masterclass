![](https://)![](https://)![](https://i.imgur.com/iywjz8s.png)


# Homework Collaborative Document - Triple Threat (Group 3)

2024-09-10-ds-rss-masterclass

Welcome to The Homework Collaborative Document for "Triple Threat" (Group 3).

Work together with your group on the homework exercises in this document.

**Group members**
*Please add your email address so you can get in touch with your group!*


**If you are not one of these people, please follow the link to the collaborative document of day one and in the homework group table find your own group's document.**

-------------------------------------------------------

For the homework exercises, see the [Masterclass page](https://esciencecenter-digital-skills.github.io/research-software-support/main/masterclass) on the Research Software Support platform. 


Collaborative Document day 1: [link](https://codimd.carpentries.org/uKv9hTtdR_yHxKl86FpiqQ)

Collaborative Document day 2: [link](https://codimd.carpentries.org/F_pLYnf8RAGyXX5cdm2H5w)

The link to this document: [link](https://codimd.carpentries.org/4CJ6um8iSxe2uwpr97FMcA)


##  🫱🏽‍🫲🏻 Code of Conduct

Participants are expected to follow these guidelines:
* Use welcoming and inclusive language.
* Be respectful of different viewpoints and experiences.
* Gracefully accept constructive criticism.
* Focus on what is best for the community.
* Show courtesy and respect towards other community members.
 
## ⚖️ License

All content is publicly available under the Creative Commons Attribution License: [creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/).

## 🙋Getting help

If you have a question, either put it in the last section of [the collaborative document of day 1](https://codimd.carpentries.org/uKv9hTtdR_yHxKl86FpiqQ?both#Questions-regarding-homework) or come to the **online homework sessions**:

| Date           | Time          | 
| -------------- | ------------- | 
| Wed 25/09/2024 | 11:00 - 12:00 | 
| Mon 30/09/2024 | 15:00 - 16:00 | 

[Homework session zoom link](https://us02web.zoom.us/meeting/register/tZMkfumppzooG9xCWql6revgSk8jG8h7w8Ed)


## 🖥 Workshop website

[Workshop Website](https://esciencecenter-digital-skills.github.io/2024-09-10-ds-rss-masterclass/)

[Research Software Support platform](https://tinyurl.com/researchsoftware-2024)


## 🗓️ Planning
*You can use this space to make a planning with your groupmates for working on the homework. Decide who will do what by when and make sure to keep some time for reviewing eachothers work and the final work.*

## 🧠 Collaborative Notes
*Use this area to make notes and document your discussions.*

## 🔧 Exercises

### Research software lifecycle

Chosen software: [AneuFinder](https://www.bioconductor.org/packages/release/bioc/html/AneuFinder.html), published in [Bakker et al., 2016](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0971-7), an R-package to annotate copy number variations in single-cell sequencing data.

Q. Would you consider this Research Software or Software used in Research? Explain why. 
Research software, because it was specifically designed for research. It was designed and developed to address a specific research question because an existing tool did not yet exist.
Q. Where does it fit in the research life cycle? Explain why.
    1. Processing & analyzing: used to analyze data both in the past and present. 
    2. Publishing & sharing: it is published in a journal and shared publically through a repository. 
    3. Preserving: maintaining the software such that it keeps working, still done by the developers. 
    4. Re-using: mostly done by other researchers.

### Software in the Research landscape


Q. Explain why you chose these three and what makes them valuable for the chosen piece of software.

1. FAIR, because the software is *findable* (it's on an online repository, i.e. Bioconductor/GitHub), it is *accessible* (open access), it is *interoperable* because it can be used on a variety of operating systems (i.e. Linux/MacOS/Windows/cluster etc.) and the code is completely open source, and it is *re-usable* because it is maintained and can be applied to genome sequencing data from other sources (i.e. organisms) and other research institutes.
2. Open Science/Open Source: because the research paper, code and data are fully accessible.
3. Carpentries: non-bioinformatic researchers were trained in the ways of R to help adjust, expand and improve the code such that the package worked as desired.

### Software Management Plan

**Behold, the best software management plan:**
![](https://github.com/bbakker1989/dataisbeautiful/blob/master/WhatsApp%20Image%202024-09-17%20at%2016.01.48.jpeg?raw=true)

Q1. Assess what level of management (low, medium, high) your custom template matches most.

Medium-level, because it is more complicated than just an R-script, rather a complete R-package. If it failed to work, society would not collapse. No known research projects will fail if the software stops working. The tool is not meant for use in diagnostics, but fundamental research.

Q2. What is different from your custom template and the default management level template? Does this difference make sense?

We excluded the Risk and Support aspects, and that makes sense as the tool is not meant for diagnostics, see answer to Q1.

Q3. Finally use section 6 (Implementation Examples) from the Practical Guide to Software Management Plans to create the Software Management Plan template with questions that a researcher/developer would have to answer.

**Purpose** What is the current reason or expected end-use for developing the software? 
To create a new tool for assessing copy number variations in single-cell sequencing data as no existing tool meets the requirements to address the research questions we had [(see Bakker et al., 2016)](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0971-7)

**Reliability** Low risk of harm to self or others, because it does not for example directly control medical equipment (see Q1 and Q2), and it is based on scientific literature and experience.

Medium to high risk to both reputation and research, because if the tool does  not reliably perform as described or desired, the results of any research using the tool can be called into question. Thereby the reputation of the researcher, their department and institution may be negatively affected. We have to fight against the scientific Trumps of the world! No fake data in my backyard! With time, the dependencies of the tool may become obsolete or incompatible so that the tool no longer works effectively.

**Maintenance** Dependency management is very important because the tool uses packages and their functions and features developed by other researchers, which are still being updated. If new functions or features are added to those dependencies, our tool may yield unexpected results or even break if we do not keep track of those changes.

**SMP breakdown**
*Purpose*: an R-package to automatically annotate copy number variations in single-cell sequencing data.

*Version control*: Major updates, including new models to perform analyses will be listed as X.0.0 updates, with minor updates, bugs and corrections as sub-updates.
*Testing*: A script provided in the user manual is provided to analyse the accompanying example data, that includes as many package features as possible for the user to test whether the package works as expected.
*Packaging*: The tool is packaged as an R-package, that can be installed with a single prompt in the R-console.
*Software engineering quality*: We will follow the recommended practice for software development as outlined in ["The Turing Way."](https://book.the-turing-way.org/index.html)

*User documentation*: A comprehensive user manual will be available to new users, including example code and data to experiment with.
*Deployment documentation*: Clear instructions will be listed in the user manual and on the repositor website to install and update the package.
*Developer documentation*: Individual functions within the package will have extensive documentation per the format required by CRAN (Comprehensive R Archive Network).

*Software licensing and compatibility*: Artistic-2.0. The tool may be copied and modified, but those modification may not then be published as if it were a new tool.
*Citation*: Bakker B, Taudt A, Belderbos ME, Porubsky D, Spierings DC, de Jong TV, Halsema N, Kazemier HG, Hoekstra-Wakker K, Bradley A, de Bont ES, van den Berg A, Guryev V, Lansdorp PM, Colome-Tatche M, Foijer F (2016). “Single-cell sequencing reveals karyotype heterogeneity in murine and human malignancies.” *Genome Biology*, **17**(1), 115, http://doi.org/10.1186/s13059-016-0971-7.
*Maintenance*: The main developers, the co-first authors of the published paper will regularly check compatibility with dependencies.
*Repository*: Package will be published on Bioconductor, a commonly used and open repository for bioinformatics research software.

## 📚 Resources
*Use this to share *