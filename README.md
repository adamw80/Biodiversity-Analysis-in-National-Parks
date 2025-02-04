# Biodiversity Analysis in National Parks

## Overview
This project focuses on analyzing biodiversity data from the National Parks Service to understand species distribution and conservation status across various parks. By exploring patterns in species endangerment and their geographical distribution, the project aims to provide insights into conservation needs. Machine learning models are applied to predict species conservation status and distribution based on environmental factors.

## Dataset
The project uses the following datasets:
- **species_info.csv:** Contains information on species taxonomy and conservation status.
  - **category:** Taxonomic category of the species (e.g., Mammal, Bird).
  - **scientific_name:** Scientific name of the species.
  - **common_names:** Common names of the species.
  - **conservation_status:** Current conservation status (e.g., Endangered).

- **observations.csv:** Contains observation counts of species in various national parks.
  - **scientific_name:** Scientific name of the observed species.
  - **park_name:** Name of the national park.
  - **observations:** Number of observations in the past 7 days.

## Key Objectives
1. Analyze species distribution and conservation status.
2. Identify factors contributing to species endangerment.
3. Predict conservation status using machine learning models.
4. Visualize the distribution of species across different parks.

## Project Structure
```
.
├── README.md                 # Documentation file
├── biodiversity.ipynb        # Main analysis and prediction notebook
├── data/                     # Contains input datasets (species_info.csv, observations.csv)
├── results/                  # Outputs such as plots, tables, and model performance
└── models/                   # Any saved models used for prediction
```

## Key Features
- **Exploratory Data Analysis:** Understand species characteristics and conservation trends.
- **Statistical Analysis:** Determine significance between species categories and their conservation status.
- **Machine Learning Models:** Predict conservation status and geographical distribution.
- **Visualization:** Display species distributions and trends across parks.

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/biodiversity-analysis.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and execute the `biodiversity.ipynb` notebook in a Jupyter environment to follow the analysis and predictions.

## Results
- Insights into species endangerment and their conservation status.
- Visualizations of species distribution in national parks.
- Predictive models for conservation status and distribution.

## License
This project is licensed under the MIT License.

## Contact
For questions or feedback, feel free to reach out:
- **Email:** Adam.RivardWalter@gmail.com  
- **GitHub:** [adamw80](https://github.com/adamw80)
