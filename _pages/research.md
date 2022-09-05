---
permalink: /research/
title: "Research"
---

{% include base_path %}

## Research themes

My research is united by the use of mathematical modelling to tackle the spread of antibacterial resistance (AbR), and now SARS-CoV-2. I am interested in using cutting-edge quantitative methods to explore the many dimensions of AbR from it's basic genetic evolution, to environmental selection to informing the design of interventions for control. I work closely with experimental microbiologists as well as clinicians to get to the fundamentals of the dynamics of AbR. Using this experience of thinking about the sources of AbR, I have worked on trying to understand and quantify the spread of SARS-CoV-2, specifically in hospital settings.  

### (1) Why does prevelance of resistance in infection vary by age? 

This is the focus of my MRC CDA. My three work packages here will involve 

1. *mapping* trends in data from global open access and individual patient UKHSA datasets
2. *modelling* to understand the underlying drivers 
3. *intervention design* using the modelling and understanding to support better empiric therapy design.
 
This project starts in September 2022 so watch this space... I am recruiting a data scientist to work alongside me - advert [here](https://jobs.lshtm.ac.uk/Vacancy.aspx?ref=EPH-IDE-2022-34). Deadline 30th September. 

### (2) Why aren't all bacteria resistant to all antibiotics? Why is diversity maintained? 

Resistance to nearly all antibiotics has been seen in nearly all bacteria and yet totally drug resistant bacteria are rare. Instead, we see highly diverse antibiograms in bacterial samples from patients (in MRSA) and a variety of mutational combinations conveying resistance (in *Mtb*). I want to understand what drives this maintenance of diversity and the rate of gene movement to determine better methods of control and ways to slow resistance emergenece. 

This variation is also often missing from mathematical models that aim to capture the dynamics of AbR spread or interventions for AbR control - I want to understand the importance of this and use these new modelling frameworks to better understand the underlying dynamics and to improve treatment design to prevent AbR emergence. 

My work in this area has mainly focused on *S. aureus* where most resistance genes are moved horizontally between bacteria by bacteriophage. These super cool bacterial viruses not only need to be investigated as a potential future therapy but because they likely drive resistance evolution in many bacteria. To get to the heart of this problem I work with [Jodi Lindsay's lab](https://www.sgul.ac.uk/research-profiles-a-z/jodi-lindsay) to perform microbiology experiments allowing us to get insight into bacteria, phage and antibiotic interactions. 

Much of my research on bacteriophage has been led by my PhD student [Quentin Leclerc](https://scholar.google.com/citations?user=oSDPjWIAAAAJ&hl=en). He has developed a model of phage and bacterial interactions to measure the rate of generalised transduction which allows us to capture the dynamics of both phage and bacteria populations. A key to this was linking phage burst size to bacterial growth and a saturating function for the phage/bacterial interaction. From this we can start to understand at what rate bacterial populations maintain diversity and hence the patterns we seen in the clinic. 

I have also work on resistance diversity in *M. tuberculosis* with a focus on the importance of fitness costs to resistance - how do predictions of resistance burden vary when models include the true variation in fitness between resistant strains? Current research is exploring sub-MIC resistance diversity. 

### *Selected publications*
[Bacterial-phage model](https://journals.asm.org/doi/full/10.1128/msystems.00135-22): In this paper we lay out our experimental work with *S. aureus* exploring the rate of generalised transduction and fit multiple model structures to it to determine the likely underlying dynamics and rates. 

[Variation in fitness in *M.tb*](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4583567/): We showed the importance of variation in fitness to the future levels of MDR-TB. 

[Differences in fitness between MRSA clones](https://www.ncbi.nlm.nih.gov/pubmed/22761331): Using hospital strains of *S. aureus* we explored what may have caused a decline in MRSA incidence at St. George's University NHS Trust and found a fitness differential between the key clonal complexes.

#### Collaborators: [Jodi Lindsay and group](https://www.sgul.ac.uk/research-profiles-a-z/jodi-lindsay), [Louis Grandjean](https://www.researchgate.net/profile/Louis_Grandjean2-UCL), [Mirko Zimic and group](http://www.upch.edu.pe/vrinve/investigacion/lbbm-gbi) 

### (3) Where does transmission and selection of AbR occur? 

A fundamental aspect to AbR control is understanding where the AbR bacteria are selected for and transmitted from. We are interested in reducing the number of infections in humans with AbR bacteria. If most of this resistance is selected by antibiotic use in the community then we should reduce antibiotic use in primary care. If most was initially selected for in pigs, then we need to target antibiotic use and then onward transmission from pork products. These maps of selection and transmission are likely to vary by organism and resistance mechanism, but until they are mapped and more importantly, quantified (which is most important) we will be merely fire-fighting the end problem of AbR. My research here develops mathematical models and frameworks to assess the importance of different environments in different settings (e.g. UK vs. Senegal) and then their contribution to the economic burden. 

In particular, I am PI of the SEFASI consortium which has funding to explore the impact of interventions at the farm level to reduce antibiotic prescribing in England, Senegal and Denmark. 

### *Selected publications*
[Quantifying where AbR comes from](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-018-1121-8): In this work we used modelling to ask whether hospitals or community antibiotic prescribing was really the source of most selection of AbR finding that due to the large volumnes in primary care the community was very much the place to target stewardship interventions. 

[How can you quantify the impact of antibiotic use in food-producing animals on AbR infections in humans?](https://www.mdpi.com/2079-6382/11/1/66): In this work we argue for better data analysis to get to the heart of this important interaction.

#### Collaborators: [Nichola Naylor, UKHSA/LSHTM](https://www.lshtm.ac.uk/aboutus/people/naylor.nichola), [Michel Dione, ILRI](https://www.ilri.org/people/michel-mainack-dione), [Dagim Belay, Uni. of Copenhagen](https://ifro.ku.dk/english/staff/?pure=en/persons/419281), [Javier Guitian](https://www.rvc.ac.uk/about/our-people/javier-guitian). 


### (4) What can we do about AbR? 

I believe mathematical modelling has a key place in informing and guiding interventions for antibiotic reistance and infection control in hospitals. By developing models, fit to hospital or ecological data, new interventions as well as hypotheses about resistance development can be developed. 

I work closely with a number of UK hospitals to align my research questions with clinical need and parametrise them as far as possible with existing clinical data. For example, I have worked on SNP [cut-offs for MRSA isolates](https://www.sciencedirect.com/science/article/pii/S266652472030149X) for genome screening in hospitals and transmission differentials between hospital wards. 

I also use modelling to understand the burden of AbR and its driver, in order to determine where interventions should be targetted.  

More practically, I use modelling to support data analysis to better inform empiric prescribing. I led the team that [won the first Wellcome Data ReUse prize](https://www.lshtm.ac.uk/research/centres/amr/news/84291/wellcome-data-re-use-prize-amr-surveillance) thinking about this problem using the ATLAS dataset from Pfizer. Building on this, I am now working with collaborators in Zambia to understand local data and hence develop empiric prescribing guidelines. 

### *Selected publications*

[How many people are latently infected with MDR-Mtb?](https://www.sciencedirect.com/science/article/pii/S147330991930307X): In this work we combined trend analysis with a cohort model to determine if there was a large burden of latent infection with MDR-resistant *Mtb*. We found that 3 in every 1000 individuals globally was likely infected with MDR-Mtb in 2014. This needs to be targetted to prevent active disease cases from reactivation. 

[Screening for carbapenem resistance](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6094916/). This work explores whether screening for patients carrying carbapenem resistant Enterobacteriaceae should be done using a direct PCR test or a culture and then PCR combination. This was presented at ECCMID 2018.

#### Collaborators: [Alison Holmes](https://www.imperial.ac.uk/people/alison.holmes) and the [HPRU for HCAI and AMR](https://www.imperial.ac.uk/medicine/hpru-amr), [Jon Otter](https://www.imperial.ac.uk/people/j.otter), [Pete Dodd](https://www.sheffield.ac.uk/scharr/people/staff/pete-dodd), [Rein Houben](https://www.lshtm.ac.uk/aboutus/people/houben.rein), [Francesc Coll](https://www.lshtm.ac.uk/aboutus/people/coll.francesc), [Nichola Naylor](https://www.lshtm.ac.uk/aboutus/people/naylor.nichola). 


### COVID-19

The COVID-19 pandemic has fundamentally affected the way we do research, and for many mathematical modellers of infectious disease, the questions we now need to ask. My research on COVID-19 initially focused on praticalities: one was to provide support for UCLH to calculate bed occupancy during the London outbreak in the Spring of 2020. This has led to research into the length of stay of patients with COVID-19. Secondly, we looked into the spread of SARS-CoV-2 - which settings are associated with transmission? 

Since the summer of 2020 I have been working with the nosocomial sub-group of SPI-M led by [Julie Robotham](https://www.imperial.ac.uk/people/j.robotham) to understand the size and contribution of hospital settings to SARS-CoV-2 spread. 

I have also worked to understand how COVID-19 will affect AbR spread with colleague within the [AMR Centre at LSHTM](https://www.lshtm.ac.uk/research/centres/amr). Going forward this is something that needs further work to understand how the data on and transmission of AbR was affected - I think there will be something to learn but it's not clear yet to what extent the data on AbR levels can be trusted. 


### *Selected publications*
[Settings of transmission](https://wellcomeopenresearch.org/articles/5-83/v2): We set up a peer supported database of clusters of SARS-CoV-2 infections linked to transmission in specific settings. 

[Contribution of hospitals to SARS-CoV-2 spread in England in the first half of 2020](https://bmcinfectdis.biomedcentral.com/articles/10.1186/s12879-022-07490-4): We found that approximately a fifth of those with identified COVID-19 in hospitals were likely infected in hospital but that hospitals contritbuted little to the wider epidemic.

[The interaction of COVID-19 and AMR](https://elifesciences.org/articles/64139): We proposed a structured way of considering this interaction with how COVID-19 affects AMR emergenece, transmission and burden. 


#### Collaborators on hospital transmission work: [Seb Funk](https://www.lshtm.ac.uk/aboutus/people/funk.sebastian), [Julie Robotham (UKHSA)](https://www.imperial.ac.uk/people/j.robotham), [Jon Read (Lancaster)](https://www.lancaster.ac.uk/people-profiles/jonathan-read), [Ben Cooper (Oxford)](https://www.ndm.ox.ac.uk/team/ben-cooper)
