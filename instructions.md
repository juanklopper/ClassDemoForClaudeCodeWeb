
---
applyTo: "notebook"
---

## Notebook Instructions

* Start a notebook with a title markdown cell such as `# Notebook Title`.

* The second markdown cell should be `## Python packages` followed by a code cell that imports all necessary Python packages.

* End this section with a code cell with the Python code `%config InlineBackend.figure_format = 'retina'` to enable high DPI plotting.

* The third markdown cell should be `## Load data` followed by a code cell that loads the data and subsequent code cells that perform any necessary data cleaning and preprocessing.

* The next markdown cell should be `## Analysis` followed by code cells that perform the analysis. Follow the instruction in the prompt to complete the analysis.

## General guidelines for notebook structure and formatting

* Use a clear and descriptive title for the notebook.

* Use markdown section cells to organize the notebook into sections.

* Use code cells for executable code.

* Ensure that the code is well-commented and easy to understand.

* Do not create excessively long code cells.

* Break code cells into shorter, manageable chunks.

* Use text and LaTeX in markdown cells after each code cell execution to explain the results of the code. For instance, if the code cell contained the code `df.Age.mean()` and the result is 42, use a markdown cell to write: The sample mean $\bar{X}=42$ years.

* Use consistent formatting throughout the notebook for a professional appearance.