# EC2880C Group Project

**Author**: Adam Cheng

**Organization**: National University of Singapore, Singapore

**Email**: adamchengworkstation@gmail.com

## Project Overview
This project aims to analyze the Argentina Financial Crisis (1998-2002).

The variables include:
- `country_name`: Name of the country

- `year`: Calendar year

- `ars_usd`: $E_{ARS/USD}$ or ARS per unit of USD

- `export_growth`: % change in the value of exports from the previous year

## Data Source
The data is sourced from the following:
1. [International Monetary Fund (IMF)](https://data.imf.org/en/datasets/IMF.STA:ER)

2. [World Bank](https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators)

## Directories
- `data`: Contains the original datasets used in the project

    - `arg_ars-usd_imf.csv`: Original dataset retrieved from the International Monetary Fund

    - `arg_export_wb.csv`: Original dataset retrieved from the World Bank

- `syntax`: Contains the syntax files created and used for this project

    - `data_analysis.qmd`: Quarto Markdown file in R code for data analysis

    - `*.html and *.pdf`: Files rendered from the Quarto Markdown files. File format depends on the available output format(s) specified in the YAML of the Quarto Markdown files

- `syntax`-specific files: 
    - `bibliography`: Contains the bibliography files used for citations

        - `*.bib`: BibTeX file containing references for documents

        - `*.csl`: Citation Style Language files used for formatting references


## Software Requirements
- [R](https://www.r-project.org/) version 4.2.2 or higher

- [Quarto](https://quarto.org/) for acceesing `.qmd` files

-  An Intergrated development environment (IDE) or a code editor of your choice ([RStudio](https://posit.co/downloads/), [VSCode](https://code.visualstudio.com/), [PyCharm](https://www.jetbrains.com/pycharm/), etc.) to run R code
    - [RStudio](https://posit.co/downloads/) is recommended as it provides a user-friendly interface for R programming and data analysis

## Running the Code
**To run code for the `*.qmd` files**:

- Install [Quarto](https://quarto.org/docs/get-started/)

- Ensure the appropriate programming language is installed (e.g., R, Python)

- Open the `*.qmd` file in RStudio or any [code editor supported by Quarto](https://quarto.org/docs/get-started/hello/vscode.html)

- Run the code from top to bottom

- **Note**: To generate publication ready documents from the `*.qmd` files...
    - Click on the "Render" button in RStudio or use the command line to render the file

    - The output will be saved in the same directory as the `*.qmd` file unless specified otherwise

## References
International Monetary Fund. (2025). *Exchange Rates (ER)*. \[Annual and National Dataset\]. Retrieved from https://data.imf.org/en/datasets/IMF.STA:ER

The World Bank. (2025). *World Development Indicators*. \[Annual and National Dataset\]. Retrieved from https://datacatalog.worldbank.org/search/dataset/0037712/World-Development-Indicators

