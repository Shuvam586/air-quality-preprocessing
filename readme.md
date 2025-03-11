

## **Air Quality Dataset Preprocessing**

This repository contains a cleaned version of an air quality dataset. The goal was to make the dataset more usable for analysis.  

### **Dataset**  
- **Source:** [Air Quality](https://archive.ics.uci.edu/dataset/360/air+quality)  
- **Size:** 9357 instances  

### **Cleaning Steps**  
- Handled missing values   
- Removed duplicates  
- Standardized date/time formats  
- Normalized numerical values


### **Getting Started**  

1. **Clone the Repository**   
   ```sh
   git clone https://github.com/shuvam586/air-quality-preprocessing.git
   ```  

2. **Navigate to the Directory**  
   ```sh
   cd air-quality-preprocessing
   ```  

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```  

4. **Jupyter Notebook**  
   - Execute the cells in [data_cleaning.ipynb](./notebooks/data_cleaning.ipynb)

5. **Clean Dataset**  
   - Processed dataset is exported to [cleaned.csv](./data/cleaned.csv)