---
date: "2020-05-22"
tags:
- survival analysis
- alternative data
- competing risks
- statistical flaws
- remdesivir
- visualization
- r
title: Compassionate Use of Remdesivir for Patients with Severe Covid-19 data
author: "Lucy D'Agostino McGowan"
---


A paper by Grein et al., [Compassionate Use of Remdesivir for Patients with Severe Covid-19](https://www.nejm.org/doi/full/10.1056/NEJMoa2007016), was recently published in the New England Journal of Medicine examining a cohort of patients with COVID-19 who were treated with compassionate-use remdesivir. There are two things that were interesting about this paper:

1. They had a very neat figure that included tons of information about their cohort
2. The primary statistical analysis was not appropriately done


I've pulled the data from their Figure 2 to recreate it. [[Data](https://github.com/LucyMcGowan/nejm-grein-reanalysis)] [[Blog post](https://livefreeordichotomize.com/2020/05/21/survival-model-detective-1/)]

It was [pointed out by Stefanos Bonovas & Daniele Piovani](https://www.nejm.org/doi/full/10.1056/NEJMc2015312?source=nejmtwitter&medium=organic-social) in a letter to the editor that the authors used the wrong analysis to look at this data (simple survival analysis versus competing risks). I've pulled the data from Figure 3A and recreated the analysis appropriately [[Blog post](https://livefreeordichotomize.com/2020/05/22/survival-model-detective-2/)]

