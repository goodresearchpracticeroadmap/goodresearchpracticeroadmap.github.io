---
section: Doing
nav_order: 2
title: Data Analysis
---

{% include roadmap-zoom-title.html cssClass="data-analysis" title="Following proper procedures for data analysis and following appropriate methods ensure the validity and reliability of your findings, leading to credible and reproducible results." %}

  

  - **Follow any analysis methods planned in any protocols or preregistrations**, and if deviations are required, **document these**. 

  - You should always make sure any data analysis is **replicable and reproducible** – be sure you know and record exactly what you did and how you did it.  

 -  Be sure to back up your analysis workflow and use a system for version control

  - If using specific software for data analysis, always **record the exact software versions and settings used**, and keep a record of the exact steps you followed.  

  - If your analyses change over time, **do not completely rewrite any analysis records or code** but rather add to it or make a copy of your analysis script – this ensures you still have a record of earlier analyses, and don’t lose any important information. 

  - If using coding/programming, follow steps to **ensure your code is reproducible**: use version control, good coding practices, upload to repositories, and have proper procedures in place for updating, overwriting, or collaborating on code.   

  - If doing quantitative research, engage in appropriate **statistical training** and ensure you understand the statistical tests you are using, and which tests or checks are **suitable to the type of data** you're analysing – this should ideally have been addressed in the “planning” stage of your project. If needed, seek out help with analysis from an expert, statistician, or data analysis group. 

- **Avoid questionable research practices such as HARKing and P-hacking** during analysis – this is common and **isn’t always done deliberately**

- For quantitative data, consider whether you need to perform any **data checks** before including data in analysis e.g., tests normality, sphericity, homogeneity, or checking for outliers etc. – these should have ideally been planned in any protocols.  

- Understand the importance of **good data presentation** and consider ways to incorporate these practices: graphic and figure design, types of plots available, slide design. Scope out any helpful guides and/or tools that may help you achieve this. Ensure your data presentation is accessible, eg. use colour-blind friendly presentation. 

  
{% include alert.html text="**Are you confident you understand the best ways analyse and present your data? Does your experimental design and data analysis help to answer your research question?**" align="center" color="success" %}

{% capture additional_resources %}
- [Experimental design and data analysis (UoE School of Biomedical Sciences)](https://www.ed.ac.uk/biomedical-sciences/experimental-design-and-data-analysis/)
- [Statistical Design and Analysis of Biological Experiments  – Hans-Michael Kaltenbach (Senior Scientist at ETH Zürich)](https://n.ethz.ch/~kahans/doe2021/)
- ["Ten reproducible research things" – advice on data quality, backups, documentation etc.](https://guereslib.github.io/ten-reproducible-research-things/)
- ["Reproducible data analysis" (Stanford)](https://poldrack.github.io/psych-open-science-guide/4_reproducibleanalysis.html)
- Tsang, Benjamin. “P Hacking — Five Ways It Could Happen to You.” Nature, 8 May 2025, [https://doi.org/10.1038/d41586-025-01246-1](https://doi.org/10.1038/d41586-025-01246-1).
- ["Tidy data" (Hadley Wickham)](https://www.jstatsoft.org/article/view/v059i10)
- ["Writing robust code" (the Turing Way)](https://the-turing-way.netlify.app/reproducible-research/code-quality/code-quality-robust)
- ["Data visualisation" (The Turing Way)](https://book.the-turing-way.org/reproducible-research/rdm/rdm-visualisation)
- ["How to make scientific figures accessible to readers with color blindness"](https://www.ascb.org/diversity-equity-and-inclusion/how-to-make-scientific-figures-accessible-to-readers-with-color-blindness/)
{% endcapture %}

{% include accordion.html title1="Suggested resources" text1=additional_resources %}
