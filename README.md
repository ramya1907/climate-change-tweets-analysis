# Climate Change Stance Analysis Project
This repository serves as a supporting resource for the thesis project titled "Analyzing Climate Change Discourse on Twitter: Stance Classification, Clustering, and Social Network Analysis". The project aims to explore the diverse perspectives and stances present within Twitter discourse regarding climate change, employing advanced data science techniques including natural language processing (NLP), machine learning for stance classification, clustering algorithms for identifying discourse themes, and social network analysis to understand the polarised stances among Twitter users discussing climate change.

## Repository Contents

- `climate_change_stance_analysis.ipynb`: The main Jupyter notebook containing detailed code for data preprocessing, stance classification models, clustering analysis of tweets, and constructing social networks based on stances.

- `frequency_dictionary_en_82_765.txt`: This frequency dictionary is a component of the spell checking and correction process within the preprocessing stage. 

- **Dataset Folder**: Contains three CSV files with public datasets collected from different sources. These datasets are utilized within the Jupyter notebook for analysis.
  - `data_world.csv`: Dataset sourced from DataWorld platform.
  - `kaggle.csv`: Dataset sourced from Kaggle platform.
  - `kaggle_2020.csv`: Dataset sourced from Kaggle platform.

- `combined_data.csv`: This file contains data that has undergone preprocessing and stance classification to streamline subsequent analyses, eliminating the need to repeatedly execute preprocessing and stance classification steps prior to clustering.


## How to Use This Source Code

To utilize this source code effectively, follow these step-by-step instructions after downloading the source code from the repository:

1. **Open Google Colab**: Navigate to [Google Colab](https://colab.research.google.com/) and sign in with your Google account.

2. **Upload the Notebook**: Click on `File` > `Upload notebook`, then select the `climate_change_stance_analysis.ipynb` file you downloaded from this repository.

3. **Prepare the Dataset Folder**:
   - In the Colab environment, use the sidebar to locate the `Files` tab.
   - Open the (`/content`) folder, right-click and choose `New folder`, then name it `Dataset`.
   - Inside the `Dataset` folder, upload the CSV files: `data_world.csv`, `kaggle.csv`, and `kaggle_2020.csv`.

4. **Upload the Frequency Dictionary**:
   - Similarly, in the main content folder (`/content`), upload the `frequency_dictionary_en_82_765.txt` file. Ensure it's not inside the `Dataset` folder but in the same directory level as `Dataset`.

5. **Run the Code**:
   - You can run the entire notebook by clicking on the 'play' button under `Run Analysis`
   - Alternatively, run each cell individually to proceed through the analysis steps at your own pace.

6. **Verify Data Loading**:
   - Within the 'Data Cleaning' section, `head()` statements are included to ensure CSV files are properly read and the DataFrame is correctly populated. Make sure to check the outputs of these cells to verify that the data loading process has been successful.

By following these instructions, you should be able to replicate the analysis presented in the notebook, explore the data, interact with the Network Visualisation, and gain insights into the climate change discourse on Twitter.

## Additional Instructions for Clustering and Network Visualization

If your focus is solely on the clustering and network visualization sections of this analysis, you can bypass the initial preprocessing and stance classification steps by directly utilizing the prepared `combined_data.csv` file.

1. **Upload the Combined Dataset**:
   - In addition to the files mentioned above, upload the `combined_data.csv` file to the main content folder (`/content`) in the Colab environment. 

2. **Run the Imports and Installations cell**

3. **Navigate to the Desired Section**:
   - In the notebook, scroll down to the sections labeled 'Clustering' or 'Network Analysis'.
   - These sections can be run independently if the `combined_data.csv` file is in place. 

3. **Run the Specific Sections**:
   - To execute clustering analysis or network visualization, simply run the cells in the corresponding section of the notebook.