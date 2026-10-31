# walmart-hurricane-project
--------------------------
## How to Access and Run the Project

### 1. Get the Repository

Clone the project repository from GitHub:

```bash
git clone [REPOSITORY_URL]
```

Alternatively, download the repository by selecting **Code → Download ZIP** on GitHub and extracting the files.

### 2. Open the Notebook in Google Colab

1. Go to [Google Colab](https://colab.research.google.com/).
2. Select **File → Open notebook → GitHub**.
3. Paste the GitHub repository URL.
4. Select the project notebook from the `notebooks/` folder.

### 3. Access the Project Data

In the first notebook cell, clone the repository into the Colab environment:

```python
!git clone [REPOSITORY_URL]
```

The repository will be downloaded, including the `data/` directory and all supplied datasets.

### 5. Run the Notebook

1. Confirm that the notebook's file paths point to the cloned repository.
2. Select **Runtime → Run all** to execute the notebook from beginning to end.
3. The notebook will load and clean the datasets, query the SQLite database, retrieve weather data through the Open-Meteo API, and perform the five analyses.

**Requirements:** An internet connection is needed to clone the repository and retrieve weather data. Google Colab is used as the execution environment.
