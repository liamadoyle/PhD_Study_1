# Psychopathy and Exploitation in Economic Games: <br> A Meta-Analysis

A meta-analysis examining the relationship between psychopathy and exploitation in various economic games (e.g., the Prisoner's Dilemma Game, the Dictator Game). In addition, the relationship between psychopathy and success in the Prisoner's Dilemma Game was examined.

## Table of Contents
- [About](#about)
- [Installation](#installation)
- [Folder Navigation](#folder-navigation)

## About
For the first study of my dissertation, I conducted several meta-analyses examining the relationship between psychopathy and exploitative behaviours in economic games. Specifically, this relationship was examined in five major economic games: the Prisoner's Dilemma Game, the Public Goods Game, the Dictator Game, the Ultimatum Game, and the Trust Game. Several conceptual and methodological moderators were examined (e.g., *k*-index of game, incentive structures of the study). Lastly, the relationship between psychopathy and success in economic games was examined. Due to a lack of data in other games, this solely involved examining this relationship within the Prisoner's Dilemma Game.

## Installation

### xlsx

The '.xlsx' files include all identified studies relevant to the research question. All coding for moderators is also available within these .xslx files. The process by which studies were identified can be found in my forthcoming dissertation, which will be accessible online. 

### R Script

Statistical analysis was conducted using version 4.4.1 of *R*. The packages used for analysis are as follows: 

* version 2.0.0 of the *tidyverse* package,
* version 7.0-0 of the *meta* package,
* version 4.6-0 of the *metafor* package,
* version 2.4.5 of the *devtools* package,
* version 0.5.1 of the *esc* package,
* version 0.8.9 of the *effectsize* package,
* version 2.4.6.26 of the *psych* package,
* version 0.1.0 of the *dmetar* package, and
* version 1.4.3 of the *readxl* package.

All analyses were conducted with version 2024.04.2+764 of *RStudio*.

## Folder Navigation

All of the raw data is stored in '.xlsx' in the [Data](./Data) folder.

To examine the analyses conducted in *R*, you can navigate to the [Analysis](./Analysis) folder.

Scripts and Markdown files have been sorted by game in this folder. All script files ('.Rmd') require *R* to be installed. Markdown files ('.html') can be downloaded to view the output of the aforementioned scripts without downloading any additional software. 

### Main Directory

The following table provides direct links to the folders of interest:

| Folder | Description |
|-----------------------------------------|-----------------|
| [Supplements](./Supplements) | Supplementary analyses and plots, designed to provide additional details for those reading my dissertation |
| [Collapsed](./Analysis/Collapsed) | Meta-analytic model examining psychopathy and exploitation across all economic games |
| [Prisoner's Dilemma Game](./Analysis/PDG) | Meta-analytic model examining psychopathy and exploitation/success in the PDG |
| [Public Goods Game](./Analysis/PGG) | Meta-analytic model examining psychopathy and exploitation in the PGG |
| [Dictator Game](./Analysis/DG) | Meta-analytic model examining psychopathy and exploitation in the DG |
| [Ultimatum Game - Proposer](./Analysis/UG_Proposer) | Meta-analytic model examining psychopathy and exploitation in the UG as the Proposer |
| [Ultimatum Game - Responder](./Analysis/UG_Responder) | Meta-analytic model examining psychopathy and exploitation in the UG as the Responder |
| [Trust Game - Trustor](./Analysis/TG_Trustor) | Meta-analytic model examining psychopathy and exploitation in the TG as the Trustor |
| [Trust Game - Trustee](./Analysis/TG_Trustee) | Meta-analytic model examining psychopathy and exploitation in the TG as the Trustee |
| [Data](./Data) | Data for each of the above models to facilitate replication/re-analysis |
