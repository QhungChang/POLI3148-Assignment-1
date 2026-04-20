# POLI3148-Assignment-1

# Global Demonstration Events Analysis (2021–2025)

## Overview
This project analyzes global patterns in demonstration events from 2021 to 2025 using data from the Armed Conflict Location & Event Data Project (ACLED). The aim is to understand how protests vary across time, regions, and in terms of their intensity, particularly in relation to fatalities and state intervention.

The analysis explores both global trends and domestic drivers of protest activity.

## Data Sources
The dataset used in this project is derived from ACLED’s aggregated regional data. The data was downloaded in separate regional files, including:

- Africa  
- Asia-Pacific  
- Europe & Central Asia  
- Latin America & the Caribbean  
- Middle East  
- United States & Canada  

These datasets contain weekly aggregated information on events, fatalities, and exposure.

Because ACLED distributes its data in Excel workbook format, all files were converted into CSV format for compatibility with Python and Google Colab. Additionally, due to GitHub’s file size limitations, the Africa and Asia-Pacific datasets were split into smaller files before being uploaded.

All processed datasets were then uploaded to this repository and accessed via raw GitHub links for analysis in Google Colab.

## Methodology
The analysis focuses specifically on demonstration-related events. To ensure consistency, only the following ACLED sub-event types were included:

- Peaceful protest  
- Protest with intervention  
- Excessive force against protesters  
- Violent demonstration  

Other event types (e.g., battles, strategic developments, mob violence) were excluded.

The workflow involved:
1. Merging regional datasets into a single global dataset
2. Cleaning and filtering the data
3. Creating time-based variables (e.g., year, date, monthly grouping)
4. Conducting exploratory and comparative analysis across regions and countries

## Key Analyses

### 1. Temporal Patterns of Demonstrations
A time-series analysis of demonstration events revealed that protest activity often spikes following major international events. For example:
- Increased demonstrations following the Ukraine war (2022)
- A surge in protests after the Gaza conflict (2023)

These patterns suggest that demonstrations can act as a form of global political expression.

At the same time, domestic political factors also drive protest activity. For instance, large-scale demonstrations in the United States (e.g., the “No Kings” protests) contributed to observable spikes at the national level.

### 2. Regional Distribution of Demonstrations
The analysis identified which regions and countries account for the highest number of demonstration events.

Key findings:
- Regions such as Europe, South Asia, and North America record the highest volume of protests
- A small number of countries (e.g., India, United States) account for a large share of global demonstrations

### 3. Types of Demonstrations
The project examines the distribution of different types of demonstrations.

Findings show that:
- Peaceful protests make up the majority of events
- However, a significant proportion involve intervention or escalation, reflecting variation in how protests are managed across contexts

In addition to examining the distribution of demonstration types, this analysis also focuses on the extent to which demonstrations involve intervention. Intervention is defined to include the sub-event types “Protest with intervention,” “Excessive force against protesters,” and “Violent demonstration,” capturing cases where protests are met with state response or escalate beyond peaceful activity.

Using this definition, the analysis compares patterns of intervention across both regions and countries. At the regional level, this allows for an assessment of how frequently demonstrations are met with coercive responses in different parts of the world. At the country level, it highlights specific contexts in which protests are more likely to involve intervention, reflecting differences in political systems, governance, and state–society relations.

### 4. Fatalities in Demonstrations

#### Total Fatalities
- Certain countries (e.g., Bangladesh, Myanmar, Iran) account for a large share of total protest-related deaths
- These are often linked to political crises, conflict, or state repression

#### Fatalities per Event (Intensity)
- A different pattern emerges when examining fatalities per demonstration
- African regions dominate this metric, indicating that protests there are more likely to become deadly when they occur

This distinction highlights the difference between:
- **Scale** (total number of deaths)
- **Intensity** (how dangerous each protest is on average)

## Key Findings
- Demonstrations are influenced by both global geopolitical events and domestic political dynamics  
- Protest activity is unevenly distributed across regions and countries  
- The intensity of protest violence varies significantly, with some regions experiencing fewer but more lethal events  
- Distinguishing between total activity and per-event intensity provides a more nuanced understanding of protest dynamics

## Limitations
- ACLED data relies on media and open-source reporting, which may vary by region  
- Some regions may be underreported due to weaker media coverage   
- The analysis does not control for variables such as population size, regime type, or economic conditions  

---

## Author
Chang Qian Hung 

---

## References
- ACLED Codebook  
- ACLED Time-Period Coverage Documentation  

(See footnotes in the main report for full references.)
