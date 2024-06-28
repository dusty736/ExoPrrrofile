# ExoPrrrofile

# Exoplanet Detection and Analysis Pipeline

This repository contains a pipeline for detecting and analyzing exoplanets using publicly available data from the James Webb Space Telescope (JWST) and other sources. The pipeline includes steps for defining a field of view (FOV), downloading data, identifying exoplanet systems, performing spectroscopy analysis, and creating visual profiles.

## Project Structure

- `data/`: Directory to store downloaded light curves and spectroscopic data.
- `scripts/`: Directory containing Python and R scripts for each step of the pipeline.
- `results/`: Directory to save results, such as detected transits and spectral analysis.
- `README.md`: This file, explaining the project and how to run the pipeline.
- `pipeline.Rmd`: R Markdown file for running the entire pipeline and generating a report.

## Requirements

- Python (with `requests`, `pandas`, `lightkurve`, `matplotlib`, `pandexo` packages)
- R (with `ggplot2`, `rmarkdown`, `reticulate`, `httr`, `jsonlite` packages)

## Setup

1. Clone this repository:
    ```sh
    git clone https://github.com/dusty736/exoplanet-pipeline.git
    cd exoplanet-pipeline
    ```

2. Install the required Python packages:
    ```sh
    pip install requests pandas lightkurve matplotlib pandexo
    ```

3. Install the required R packages:
    ```r
    install.packages(c("ggplot2", "rmarkdown", "reticulate", "httr", "jsonlite"))
    ```

## Running the Pipeline

### 1. Define the Field of View and Download Data

Update the `scripts/download_data.py` script with the coordinates of your FOV.

Run the script to download light curves:
```sh
python scripts/download_data.py
```

## Acknowledgments

## Acknowledgments

I would like to acknowledge the invaluable assistance of OpenAI's ChatGPT, who provided guidance and support in the persona of Ted Lasso, an astronomer at Cambridge University. This unique approach added a touch of inspiration and positivity to the project, making the development process both efficient and enjoyable. The AI helped streamline the process by offering code snippets, technical advice, and motivational support.

