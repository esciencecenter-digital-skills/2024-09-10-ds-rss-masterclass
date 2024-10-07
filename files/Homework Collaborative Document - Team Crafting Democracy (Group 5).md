![](https://i.imgur.com/iywjz8s.png)


# Homework Collaborative Document - Team Crafting Democracy (Group 5)

2024-09-10-ds-rss-masterclass

Welcome to The Homework Collaborative Document for "Team Crafting Democracy" (Group 5).

Work together with your group on the homework exercises in this document.


**Group members**
*Please add your email address so you can get in touch with your group!*


**If you are not one of these people, please follow the link to the collaborative document of day one and in the homework group table find your own group's document.**

-------------------------------------------------------

For the homework exercises, see the [Masterclass page](https://esciencecenter-digital-skills.github.io/research-software-support/main/masterclass) on the Research Software Support platform. 


Collaborative Document day 1: [link](https://codimd.carpentries.org/uKv9hTtdR_yHxKl86FpiqQ)

Collaborative Document day 2: [link](https://codimd.carpentries.org/F_pLYnf8RAGyXX5cdm2H5w)

The link to this document: [link](https://codimd.carpentries.org/YLcdp8H7RhSUqFNf8nzKeQ)

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
## Ex1: Research Software or Software used in Research

Q1: Is _Democracy Topic Modelling_ Research Software or Software used in Research? Explain why (max 100 words)

This project is classified as research software rather than software in research as it contributes to the research objective (mapping and assesing democratic backsliding in texts) and represents a core element of the research methodology itself,. The software generates new insigts and data that wouldn't be possible without it as a part of an ongoing funded [research project](https://research-software-directory.org/projects/assessing-democratic-backsliding-in-europen-and-its-neighborhood). 

Q2: _Where does it fit in the research life cycle? Explain why_

_Democracy Topic Modelling_ is used in the _Processing & Analyzing_ phase of the research. It is a collection of JupyterNotebooks. So it is to process and analyze the quality of democratic assessments. Since we're reusing it, we're not publishing the code ourself, we're not using it to preserve or re-use our own research and it is not used in the collection or planning phase.

## Ex2: Software in the Research Landscape
Q1: _From all the different initiatives, concepts and organizations discussed in the [Software Landscape module](https://esciencecenter-digital-skills.github.io/research-software-support/modules/softwarelandscape/slides) or the [Yellow Pages](https://esciencecenter-digital-skills.github.io/research-software-support/main/yellowpages), pick **three** that your chosen piece of software could/should connect to and/or use.
Explain why you chose these three and what makes them valuable for the chosen piece of software._

[Yellow Pages]: FAIR for Research Software - the software in question deals with high risk aspects with both data and insights from the analysis. FAIR software principles become a strict requirement for this reason, as both the code and the results should be easily findable, accessible, interoperable and reproducible. If any of these factors are missing,the methods or the results produced as a result of using the software would unreliable, and possibly even dangerous/polarizing. 

[Yellow Pages]: Code Refinery - Adhering to proper Software Management best practices helps the software to be maintainable and assists in the reproducability. Having "good code" helps future researchers to re-use and adapt previous efforts.

[Yellow Pages]: The Turing Way - Since democracy manifests differently across societies, it is not something that can be easily quantified. When developping  _Democratic Topic Modelling_, considering ethical implications is essential to avoid bias or does not unintentially reinforce biases. Having ethical safeguards in place helps avoid misinterpretation. The Turing Way offers a Guide for Ethical Research.



## Ex3: SMP

### Purpose

Th purpose of the software is to analyze democracy assessment reports: (1) how they vary over time in different democracies, and (2) test the precision of current assessments used.

### Risk analysis
The software is classified as _high risk_ as it deals with a sensitive topic with the use of potentially sensitive reports and subjectivity of the natural language. The potential implications of having bias are big.

The risks will be mitigated by complying with data quality requirements, diversifying the training dataset (to avoid the bias) and using well supported dependencies. Additionally, the repository associated with the software will be open and accessible to other researchers for transparency.

### Repository

The code is hosted in a [public repository on GitHub](https://github.com/backdem/democracy-topic-model). 

### Maintenance

For the duration of the research project, the software will be maintained by the team of developers. Afterwards, the maintenance will be performed by the community *(ask/clarify).

### Version control

Version control will be managed using Git. See Repository.

### Software engineering quality

Code quality standards, such as PEP8 (for Python), are adhered to.

### Testing

In compliance with the best software practices, we will implement unit tests on the software.

### User documentation

User documentation will include the [description and the purpose of the project](https://research-software-directory.org/projects/assessing-democratic-backsliding-in-europen-and-its-neighborhood) as well as the guidelines for installation and usage.

### Developer documenation

Developer documentation will be provided in the form of extensive comments in the code.

### Software licensing and compatibility

Licensed under Apache 2.0

### Citation

```latex
@software{democracy-topic-model
    author = {Zhelyazkova, Asya and Egger, Clara and Cushing, Reginald and Zdrale, Sara},
    title = {Democratic Topic Modelling},
    year = {2024},
    url = {https://research-software-directory.org/software/democracy-topic-modelling},
    version = {0.0}
}
```




## 📚 Resources
*Use this to share *