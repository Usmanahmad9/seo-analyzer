# seo-analyzer
analysis of URL's and seo keywords

# Python SEO Analyzer

This project is a Python-based SEO (Search Engine Optimization) analyzer that performs a comprehensive analysis of web pages and provides both textual and graphical output of the results.

## Features

- Webpage content analysis
- Keyword density calculation
- Meta tag information extraction
- Header tag analysis
- Image and alt text usage analysis
- Internal and external link counting
- Simple SEO score calculation
- Graphical visualization of results

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.6 or later
- pip (Python package installer)

## Installation

1. Clone this repository or download the source code.

2. Navigate to the project directory:

3. Install the required dependencies:
4. in the project directory
   type: pip install -r requirements.txt
5. Run python seo_analyzer.py


6. When prompted, enter the URL of the webpage you want to analyze.

7. The script will process the webpage and display a graphical representation of the SEO analysis results.

## Project Structure

- `seo_analyzer.py`: Main script that orchestrates the SEO analysis process.
- `seo_utils.py`: Utility functions for web scraping and data processing.
- `seo_visualizer.py`: Functions for creating graphical visualizations of the analysis results.

## Visualizations

The program generates a figure with four subplots:

1. Top 10 keywords bar chart
2. Header tag distribution bar chart
3. Links and images analysis bar chart
4. SEO score pie chart

Additional textual information (title, description, word count) is displayed at the bottom of the figure.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, please open an issue in the GitHub repository.
