# Roadmap Visualization Project

This project aims to generate a nature-style vertical technical roadmap using Matplotlib. The roadmap serves as a graphical abstract that outlines the problem space, formulation, solution architecture, integration, and deployment strategies for emergency building sweeps.

## Project Structure

```
roadmap-visualization
├── notebooks
│   └── roadmap.ipynb          # Jupyter notebook for generating the roadmap
├── src
│   ├── __init__.py            # Marks the directory as a Python package
│   ├── generate_roadmap.py     # Script to execute the roadmap generation logic
│   ├── viz
│   │   ├── styles.py           # Style configurations for the visualization
│   │   └── elements.py         # Functions for creating visual elements
│   └── utils.py                # Utility functions for various tasks
├── requirements.txt            # Required Python packages
├── environment.yml             # Conda environment specifications
├── .gitignore                  # Files and directories to ignore by Git
├── Makefile                    # Automation commands for project tasks
└── README.md                   # Documentation for the project
```

## Installation

To set up the project, you can create a conda environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
```

Alternatively, you can install the required packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter notebook located in the `notebooks` directory:
   - `notebooks/roadmap.ipynb`
   
2. Run the cells in the notebook to generate and export the roadmap visualization.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.