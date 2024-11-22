
# **Project: Team Research and Development Assignment**

## **Overview**
This repository contains the code and resources for the **Team Research and Development Assignment** as part of the coursework. The project analyses placement status among students based on gender using statistical methods. It aims to draw meaningful conclusions about potential disparities and provide actionable insights.

## What's Inside

- **R_Visualization/**: R scripts used to create different visualizations of the data.

BarPlot: Scripts specifically for generating bar plots.

.gitignore: Lists files that Git should ignore (like temporary files).

- **A-64 Team Research and Development Presentation Slide.pptx**: A PowerPoint presentation of our team research and result.
  
- **Dataset_Placement_Data_Full_Class.csv**: The main dataset containing students placement detail.



## Getting Started

1. Clone the repository to your local machine.


```bash

   git clone https://github.com/smhasan24/Project_Team_Research.git


2. Load the dataset in to your preferred tool (i.e., R):

```{r message=FALSE}
dataset <- read.csv('Path where your CSV file is located on your computer\\File Name.csv')

3.	Look at the visualizations in the R_Visualization folder to get insights on data.
4.	Go through our PowerPoint presentation for project summary (A-64 Team Research and Development Presentation Slide.pptx) .


## **Features**
- Data preprocessing and cleaning scripts.
- Statistical analysis, including Chi-Square tests.
- Visualizations, such as bar charts and chart Table
- Comprehensive R scripts for data exploration and hypothesis testing.
- Git log tracking for project transparency.

## **Research Question**
**"Is there a difference in the proportions of placement status (placed vs. not placed) between male and female students?"**

## **Repository Structure**
```
.
├── data/                # Contains the dataset files
├── scripts/             # R scripts for data analysis
├── visualizations/      # Plots and visual outputs
├── git_log.xlsx         # Git log tracking all commits
├── README.md            # Project documentation
└── results/             # Final results and reports
```

## **Technologies Used**
- **R**: For statistical analysis and data visualization.
- **Git**: For version control and collaboration.
- **GitHub**: For project management and file sharing.

## **Getting Started**
### **Prerequisites**
- R and RStudio installed.
- Required R packages:
  - ggplot2
  - dplyr
  - tidyr

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/smhasan24/Project_Team_Research.git
   cd Project_Team_Research
   ```
2. Open the R script files in RStudio.
3. Run the scripts in the `scripts/` directory to perform data analysis and generate visualizations.

## **Results**
The key findings of the analysis will be included in the `results/` directory. Statistical outputs and visualizations are provided to support conclusions.

# **Project: Team Research and Development Assignment**

## **Visualizations**
The project includes statistical visualizations generated using R. Below is an example of a stacked bar chart with normalized proportions created to visualize the relationship between gender and placement status:

### Stacked Bar Chart
![Stacked Bar Chart](BarPlot/Normalized_Placement_Status_By_Gender.jpg)

> *This chart illustrates the proportion of placed and not placed students by gender.*

### How to View Visualizations
All visualizations are stored in the `visualizations/` directory. Clone the repository and navigate to the folder to view additional plots.



## **Contributing**
Contributions are welcome! If you’d like to improve or expand the project:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push to your branch and create a pull request.

## **Data Privacy**
The dataset used in this project is anonymous and does not contain personally identifiable information (PII). All data used is for educational purposes only. No data is shared with third parties, and the repository is intended to demonstrate statistical analysis methods.

## **License**
This project is for educational purposes and is not distributed under any formal license.

## **Contact**
For questions or feedback, please contact:
- **SM Hasan**: [GitHub Profile](https://github.com/smhasan24)
