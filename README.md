# Child Care Crisis in New York

This repo includes all my data analysis and charts for the story.

📄 **Project page:** [https://hazel-gandhi.github.io/childcare-ny/](https://hazel-gandhi.github.io/childcare-ny/)

---

## 📁 Repo Guide

### `data/`  
A folder with all the CSVs I used to make the charts.

- The first chart showing total number of vouchers was made with data from the [Office of Child and Family Services](https://ocfs.ny.gov/programs/childcare/data/).  
  📄 File: `NYCCAP-Case-Child-Counts-by-District.csv`

- The second chart uses data from the same agency.  
  📄 File: `Child_Care_Regulated_Programs_API_20250310.csv`  
  This contains a list of all child care centers in the state. The data was segregated by county and merged with census data to calculate the density of child care centers per 10,000 children.

### `notebook.pynb`  
Includes some basic charts created in Seaborn, which were then pushed to Illustrator for final design.
