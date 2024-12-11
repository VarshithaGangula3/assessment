# University Analysis Notebook

This repository contains a Jupyter Notebook, `university_analysis.ipynb`, designed to assess Python, SQL, and data analysis skills using a mock university database (`university.db`). The notebook includes a series of prompts and tasks aimed at exploring and analyzing the database to gain insights into university data.

---

## Summary of `university_analysis.ipynb`

The notebook provides:
1. **Database Overview**: A description of the schema and relationships in `university.db`.
2. **SQL Query Prompts**: Exercises to practice retrieving and analyzing data using SQL.
3. **Data Analysis Tasks**: Integration of SQL query results with Python libraries such as Pandas, Matplotlib, and Seaborn for further analysis and visualization.
4. **Custom Explorations**: Opportunities for users to create their own queries and visualizations to answer business-relevant questions.

---

## Getting Started

To use this repository, follow these steps to copy/download the files and set up your environment.

### 1. Copy or Download the Repository
- **Clone the repository**:
   ```bash
   git clone https://github.com/GSU-Analytics/student_success_assessment.git
   cd student_success_assessment
   ```
- **Download key files**:
   - `university_analysis.ipynb`: The notebook containing the tasks.
   - `university.db`: The SQLite database used in the notebook.

---

## Running the Notebook

### A. Running Locally with Pip and `requirements.txt`

1. **Set up the environment**:
   - Install Python (3.10 or later).
   - Navigate to the project directory and install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
2. **Run the notebook**:
   ```bash
   jupyter notebook
   ```
3. Open `university_analysis.ipynb` in your browser.

---

### B. Running Locally with Conda and `environment.yml`

1. **Set up the environment**:
   - Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/).
   - Create and activate the environment:
     ```bash
     conda env create -f environment.yml
     conda activate university_db
     ```
2. **Run the notebook**:
   ```bash
   jupyter notebook
   ```
3. Open `university_analysis.ipynb` in your browser.

---

### C. Recommended Setup: Running Jupyter Notebook in VSCode

1. **Install Visual Studio Code**:
   - Download from [VSCode's official website](https://code.visualstudio.com/).
2. **Install the Python extension**:
   - Install the VSCode Python extension from the Extensions Marketplace.
3. **Run the notebook**:
   - Open `university_analysis.ipynb` in VSCode and run cells interactively.
4. **Helpful Tutorial**:
   - [Watch this YouTube video](https://youtu.be/suAkMeWJ1yE?si=fBhAu-wglPCaUZWX) for a step-by-step guide to running Jupyter Notebooks in VSCode.

---

### D. Running on Google Colab

1. **Upload Files**:
   - Navigate to [Google Colab](https://colab.research.google.com/).
   - Upload `university_analysis.ipynb` to Colab.
   - Upload `university.db` to the same folder as the notebook.
2. **Dependencies**:
   - The dependencies are already installed in Colab. 
   - Install other required packages as needed inside the notebook with the command `!pip install package_name`.

---

### Additional Notes on Package Installation
- Use `pip` for installing packages not already included in the `requirements.txt`.
- Use `conda install` to add new packages to the Conda environment.
- In Colab, use `!pip install` to install packages within the notebook environment.

---

## Submitting Your Notebook

When you’ve completed the notebook, please submit your work using one of the following methods:

1. **Push to GitHub**:
   - Fork this repository and push your completed notebook to your forked repository. Share the link to your forked repository.

2. **Host on Colab**:
   - Share a link to your hosted notebook on Colab.

3. **Submit Link to Notebook**:
   - Submit a link to your notebook to **ikerson@gsu.edu**.

**Important**: Please do not email the notebooks as attachments.

---

## Contact

If you have any questions, problems, or concerns, feel free to reach out to Isaac at **ikerson@gsu.edu**. We want you to succeed and are happy to assist in any way.