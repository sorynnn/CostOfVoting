# Reanalyzing Voter Turnout: A Difference-in-Differences Approach  

## Overview  
This project reanalyzes the seminal study by **Gerber, Green, and Larimer (2008)**, which investigates why millions of people vote despite the seemingly irrational cost-benefit imbalance of doing so. The study examines the hypothesis that a sense of civic duty, potentially influenced by social pressures, motivates voter turnout.  

Using experimental data from a 2006 Michigan primary election, nearly 350,000 voters were randomly assigned to various treatment groups, each receiving a different form of mailout or none at all. This project applies advanced econometric techniques, including **difference-in-differences (DiD)** analysis on a fixed effects model, to estimate the **average treatment effects** of these interventions on voter turnout.  

## Learning Objectives  
This project allows me to:  
- Practice T-tests and R programming skills.  
- Understand and apply fixed effects models.  
- Perform difference-in-differences analysis to estimate treatment effects.  

## Experimental Design  
The experimental treatments and control conditions are as follows:  

- **Treatment 1 (“Civic Duty”)**: Mailout reminding voters that voting is a civic duty.  
- **Treatment 2 (“Hawthorne”)**: Mailout informing voters that researchers are studying their turnout via public records.  
- **Treatment 3 (“Self”)**: Mailout displaying the record of their household's prior turnout.  
- **Treatment 4 (“Neighbors”)**: Mailout displaying the turnout records of their household and their neighbors.  
- **Control**: No mailout received.  

### Research Question  
Why do large numbers of people vote despite the high costs and low likelihood of influencing election outcomes?  

## Analysis Highlights  
- **Fixed Effects Model**: Captures unobserved individual heterogeneity to control for time-invariant characteristics that may influence voter behavior.  
- **Difference-in-Differences (DiD)**: Evaluates the causal impact of each treatment by comparing changes in voter turnout across groups.  
- **Average Treatment Effects (ATE)**: Quantifies the impact of each intervention on voter turnout, revealing the effectiveness of social pressure and civic duty priming.  

## Results  
The analysis demonstrates:  
1. The **Neighbors** treatment, which uses social pressure by displaying neighbors’ voting records, has the highest average treatment effect on turnout.  
2. The **Civic Duty** and **Self** treatments also significantly increase turnout, though to a lesser extent.  
3. Social pressure emerges as a critical factor in motivating voters, aligning with Gerber, Green, and Larimer’s original findings.  

## Tools and Methods  
- **Programming**: R  
- **Statistical Techniques**: T-tests, difference-in-differences analysis, fixed effects models  
- **Output**: All analyses are presented in a fully reproducible R Markdown file, “knit” into a user-friendly format for easy interpretation.  

## References  
- Gerber, A. S., Green, D. P., & Larimer, C. W. (2008). Social pressure and voter turnout: Evidence from a large-scale field experiment. *American Political Science Review*.  

## How to Run  
1. Clone this repository to your local machine.  
2. Open the `R Markdown` file in RStudio.  
3. Run the analysis and knit the file to view results.  

## License  
This project is open-source under the [MIT License](LICENSE).  
