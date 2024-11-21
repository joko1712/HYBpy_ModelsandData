# HYBpy: Models and Data Repository

This repository contains the files needed to run models for the **HYBpy** tool, a Python-based framework for hybrid modeling of bioprocesses. These files allow you to replicate the results and values presented in my master's thesis: **"HYBpy: A Web-Based Platform for Hybrid Modeling of Bioprocesses"**.

## Purpose

This repository provides:

-   **Model files (.hmod)**: Hybrid models combining mechanistic and machine learning approaches, essential for running simulations and training models in HYBpy.
-   **Data files (.csv)**: Experimental and synthetic datasets used for training and validating models.

## Folder Structure

The repository is organized as follows:

-   **Basic** folder: Contains basic hybrid model and dataset.
-   **Chassagnole** folder: Contains hybrid models and datasets for the **Chassagnole et al., 2001** case study.
-   **ParkAndRamirez** folder: Contains hybrid models and datasets for the **Park and Ramirez’, 1990** case study.
-   **Workshop** folder: Contains hybrid models and datasets used in a recent workshop to display the effectiveness of the tool.

## Website

Visit the official HYBpy website for more information, access to the tool, and additional documentation: [www.hybpy.com](http://www.hybpy.com).

## Using the Files

1. **Download the files**:

    - Clone the repository:
        ```bash
        git clone https://github.com/joko1712/HYBpy_ModelsandData.git
        ```
    - Or download the folders/files directly from the repository.

2. **Load files into HYBpy**:

    - **.hmod files**: These are hybrid model. You can load them into HYBpy to run train the models.
    - **.csv files**: These datasets can be loaded for training and testing models.

3. **Get Started with HYBpy**:
    - Refer to the documentation and tutorials available on the HYBpy website to set up your hybrid models and run trainnings.

## Thesis Reference

If you use these files in your work, please cite my master's thesis:

> Pedreira, J.B., HYBpy: A Web-Based Platform for Hybrid Modeling of Bioprocesses, Master’s Thesis, NOVA University Lisbon, September 2024.

## References

> Chassagnole C, Fell DA, Raïs B, Kudla B, Mazat JP. Control of the threonine-synthesis pathway in Escherichia coli: a theoretical and experimental approach. Biochem J. 2001 Jun 1;356(Pt 2):433-44. doi: 10.1042/0264-6021:3560433. PMID: 11368770; PMCID: PMC1221854.

> Park S, Ramirez WF. Effect of transcription promoters on the optimal production of secreted protein in fed-batch reactors. Biotechnol Prog. 1990 Sep-Oct;6(5):311-8. doi: 10.1021/bp00005a001. PMID: 1366871.
