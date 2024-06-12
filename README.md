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

1. Run the script `Nucleia_Distance.py`:
    ```bash
    python Nucleia_Distance.py
    ```

2. Follow the instructions to annotate nucleus positions on control and experimental images.

3. View the generated plots and statistical analysis results.

## Contributors

Foysal Ahammad

## License

This project is licensed under the [license name]. See the [LICENSE](./LICENSE) file for details.
