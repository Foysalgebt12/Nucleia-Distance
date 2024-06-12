# Nuclear Distance Analysis

This Python script performs analysis on the distances between nucleus positions in microscopy images for control and experimental groups. It calculates pairwise distances, visualizes the data with histograms, scatter plots, and KDE plots, and conducts statistical tests to compare the groups.

## Features

- Annotation of nucleus positions on microscopy images.
- Calculation of pairwise distances between nucleus positions.
- Visualization of nucleus positions and distances.
- Statistical analysis including ANOVA, Tukey HSD test, effect size calculation, Mann-Whitney U test, and Kruskal-Wallis test.

## Dependencies

- Python 3.x
- OpenCV
- Matplotlib
- NumPy
- Scipy
- Pandas
- Seaborn
- Openpyxl 

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Foysalgebt12/Nucleia-Distance
    ```

2. Install Python and required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

A. Run the script `Nucleia_Distance.py`:
    ```bash
    python Nucleia_Distance.py
    ```




## A.1. Install Manually in Python:

Step 1: Install Python

If you haven't already installed Python on your system, you can download it from the official Python website: [python.org](https://www.python.org/downloads/). Follow the installation instructions for your operating system.

Step 2: Install OpenCV

OpenCV (Open Source Computer Vision Library) is used for image processing. You can install it using pip:

```bash
pip install opencv-python
```

Step 3: Install Matplotlib

Matplotlib is a plotting library for Python. Install it using pip:

```bash
pip install matplotlib
```

Step 4: Install NumPy

NumPy is a fundamental package for scientific computing with Python. Install it using pip:

```bash
pip install numpy
```

Step 5: Install SciPy

SciPy is a library for scientific computing and technical computing. Install it using pip:

```bash
pip install scipy
```

Step 6: Install Pandas

Pandas is a library providing high-performance, easy-to-use data structures and data analysis tools. Install it using pip:

```bash
pip install pandas
```

Step 7: Install Seaborn

Seaborn is a Python visualization library based on Matplotlib. Install it using pip:

```bash
pip install seaborn
```
Step 8: Install Openpyxl

```bash
pip install openpyxl
```

Step 9: Clone the Repository

Clone the GitHub repository containing the code to your local machine:

```bash
git clone https://github.com/Foysalgebt12/Nucleia-Distance.git
```

Step 10: Navigate to the Project Directory

Navigate into the project directory:

```bash
cd Nucleia-Distance
```

Step 11: Run the Python Script

You can now run the Python script using the following command:

```bash
python Nucleia_Distance.py
```


## B. Follow the instructions to annotate nucleus positions on control and experimental images.

To annotate nucleus positions on control and experimental images, follow these instructions:

1. Run the Python Script: Execute the Python script provided in the project directory by running the following command in your terminal or command prompt:

    ```bash
    python Nucleia_Distance.py
    ```

2. Annotate Nucleus Positions on Control Image:
   - Once the script is running, it will display the control image for annotation.
   - Use your mouse to click on each nucleus position in the control image. Each click will mark a nucleus position.
   - After marking all nucleus positions, close the control image window.

3. Annotate Nucleus Positions on Experimental Image:
   - After closing the control image window, the script will display the experimental image for annotation.
   - Repeat the process of clicking on nucleus positions in the experimental image using your mouse.
   - Close the experimental image window after annotating all nucleus positions.

4. Provide Run Number:
   - The script will prompt you to enter a run number. This number will be used to uniquely identify the data saved from this run.

5. Review and Save Annotations:
   - After annotating nucleus positions on both images and providing the run number, the script will save the annotated positions to separate Excel files for the control and experimental groups.
   - Review the confirmation messages to ensure that the positions were saved correctly.

By following these steps, you can effectively annotate nucleus positions on control and experimental images using the provided Python script.

## C. View the generated plots and statistical analysis results.

To view the generated plots and statistical analysis results after annotating nucleus positions on control and experimental images, follow these steps:

1. Run the Python Script: Ensure that you have already executed the Python script as described earlier to annotate nucleus positions.

2. Access the Plots and Results :
   - After annotating nucleus positions and providing the run number, the script generates plots and performs statistical analysis.
   - The generated plots include scatter plots, histograms, KDE plots, and other visualizations depicting the nucleus positions and distances between them.
   - Statistical analysis results, such as p-values from ANOVA, Tukey HSD test, effect size calculations, Mann-Whitney U test, and Kruskal-Wallis test, will also be displayed in the terminal or command prompt.

3. Review Plots :
   - To review the generated plots, look for any open windows displaying the plots. These windows typically appear after the script has completed execution.
   - You may see multiple plots showing nucleus positions, scatter plots of distances, histograms of distances, and KDE plots.

4. Interpret Statistical Analysis:
   - Review the statistical analysis results displayed in the terminal or command prompt.
   - Pay attention to p-values, effect sizes, and any significant findings from the tests conducted.
   - These results provide insights into the differences between the control and experimental groups in terms of nucleus positions and distances.

5. Optional: Save Plots and Results:
   - If you wish to save the plots or statistical analysis results for future reference, you can manually save the plots as image files or copy the results from the terminal or command prompt.

By following these steps, you can effectively view the generated plots and statistical analysis results after annotating nucleus positions using the provided Python script. 

## Contributors
You've installed all the necessary tools and dependencies and can now run the provided code successfully. Let me know if you need further assistance!
Foysal Ahammad
Hamad Bin Khalifa University
Email:foah48505@hbku.edu.qa

## License

## License

This project is licensed under the [license](https://github.com/Foysalgebt12/Nucleia-Distance/blob/main/license). See the [LICENSE](https://github.com/Foysalgebt12/Nucleia-Distance/blob/main/license) file for details.

