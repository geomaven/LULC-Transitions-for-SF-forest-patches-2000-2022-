# Land Use/Land Cover (LULC) Transition Visualization Script

![image](https://github.com/user-attachments/assets/99331d6f-5263-4ad1-92a7-6704ce7cfacb)

## Description
This Python script generates interactive Sankey diagrams to visualize land use/land cover (LULC) transitions between 2000 and 2022 for different forest patches. The script processes spatial transition data and produces publication-quality vector graphics (SVG format).

## Key Features
- Automated Sankey diagram generation for multiple forest patches
- Custom color scheme matching standard LULC classification
- Google Colab integration for cloud-based execution
- SVG output for high-resolution publications
- Flexible input data handling via Excel files

## Prerequisites
- Python 3.8+
- Google account (for Colab execution)
- Required Python packages:
  - pandas
  - plotly
  - kaleido
  - openpyxl

## Installation
```bash
# Clone repository
git clone https://github.com/yourusername/lulc-transition-visualization.git

# Install requirements (optional for Colab)
pip install -r requirements.txt
