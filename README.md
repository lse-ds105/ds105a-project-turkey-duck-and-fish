[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WKKzpWVj)

# 📝 DS105A Group Project 📝 

## ✈️ Analysis Topic: Flight Delay Analysis ✈️

### Overview

**The purpose of this repository is to the analyse flight delays: which airports have the most delays, which airlines have the most delays, how much delay occurs, etc. ** We have scraped data from flight APIs and analyzed the data. This README file will provide an overview of what you can find in this repository, how to reproduce our analysis, and the conclusions we have reached.

--- 

### Repository Structure

Here's a quick overview of the important files and directories in this repository:

- **`Code(src)`**: this folder contains the Source code for our project, where you can find:  

File **api request.ipynb**: Collecting raw data from the API, and producing a csv file containing raw data **data.csv**  

*note*: **data.csv** contains 732,880 lines of data. We do not want to push any large files to the Github, so the file is compressed to **data.rar**, which could be found in the **/Data** folder.  

File **Data Filtration.ipynb**: Filtering the raw file **data.csv** to produce the final data (**final_data.csv**) that is ready to be used for analysis.  

File **pplot-jan27.ipynb**: Analyzing **final_data.csv** with **Matplotlib** and **Geopandas** to produce visualization graphs  

- **`Data`**: This folder contains the compressed version of the raw data **data.rar** and other filtered data files (e.g. Delay.csv, Airport_IATA.csv) that are used to produce the final data.  

- **`Final Data`**: This folder contains the **final_data.csv**  

- **`docs`**:

---
### Contribution List

Here is a list demonstrating each member's contribution to the project
- **`Kylin Gao`**: xxx
- **`Chaoyang Feng`**: xxx
- **`Sissi Wang`**: xxx
- **`Anka Uysal`**: xxx