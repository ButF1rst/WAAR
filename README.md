# Women in Armed Rebellions

## Overview

This repo examines the countries with the highest documented women’s participation in armed rebellions and explores the organizational characteristics of these movements. A logistic regression model is built to analyze the probability of whether women’s participation in rebellion groups exceeds a defined threshold of significance related to rebellion characteristics, organizational dynamics, and socio-political factors.

## File Structure

The repo is structured as:

-   `data/01-raw_data` contains the raw data ('WAAR_data') as obtained from https://www.waarproject.com/dataset.
-   `data/02-analysis_data` contains the cleaned dataset ('Cleaned_data') that was constructed.
-   `data/00-simulation_data` contains the simulation dataset ('SimulationData').
-   `model` contains fitted models using Logistic Regression. 
-   `other` contains relevant literature and details about LLM chat interactions.
-   `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the python scripts used to simulate, download and clean data.


## Statement on LLM usage

ChatGPT was used and all chat history is in other/llm_usage/usage.txt.

