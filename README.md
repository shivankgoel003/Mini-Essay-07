# Impact of Data Errors on Statisitcal Analyses


## Overview

This repository contains the R scripts and documentation for a project focused on simulating a dataset with specific errors and subsequently cleaning it. The project demonstrates the impact of instrument and human errors in data collection and processing. It simulates a scenario where data is generated from a Normal distribution but is subject to instrument limitations and human errors during collection and cleaning. This includes overwriting the last 100 observations with the first 100 due to instrument memory limitations and altering negative values and decimal places during the cleaning process.

Note: Language Learning Model ChatGPT was also used while writing this research paper. It was used for the purpose of introduction and data cleaning and simulation. The chat with the AI bot is also attached as a reference under `inputs\llm`


## File Structure

The repo is structured as:

-   `outputs/data` contains the cleaned dataset that was constructed.
-   `outputs/paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the R scripts used to simulate and clean data.
