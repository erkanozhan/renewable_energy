# Türkiye Renewable Energy Data Analysis (1960–2023)

This repository contains the dataset and analysis scripts for the study on the total rate of electrical energy obtained by Turkey from renewable energy sources (excluding hydroelectricity) between 1960 and 2023. The study ([JISTA Research Article](https://dergipark.org.tr/en/pub/jista/issue/90654/1447980))is part of the Master of Science thesis of **Mehmet Berke ÇOLAK**, conducted at **Tekirdağ Namık Kemal University, Institute of Natural and Applied Sciences**, under the guidance of **Erkan ÖZHAN**.

## Dataset Description
The dataset includes the following data:
- **1960–2015:** Sourced from the [World Bank](https://www.worldbank.org/).
- **2015–2019:** Obtained from the [Ministry of Energy of Turkiye](https://www.enerji.gov.tr/).
- **2019–2023:** Acquired from [YTBS-TEIAS](https://ytbs.teias.gov.tr/) ("Yük Tevzi Bilgi Sistemi (YTBS)-Türkiye Elektrik İstatistikleri," 2023).

The dataset is provided in CSV format and includes the following columns:
- `Year`: The year of the data.
- `Electricityproduction`: The total rate of electrical energy obtained from renewable sources (excluding hydroelectricity).

## Repository Structure
/repo
│
├── /data
│ └── turkiye_renewable_energy_1960_2023.csv # Main dataset
│
├── /scripts
│ └── analysis_script.py # Example analysis script
│
├── LICENSE # MIT License
└── README.md # This file


## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/erkanozhan/renewable_energy.git

   cd renewable_energy
   pip install -r requirements.txt


## Acknowledgments
World Bank, Ministry of Energy of Türkiye, and YTBS-TEIAS for providing the dataset.

Tekirdağ Namık Kemal University, Institute of Natural and Applied Sciences for their support.
