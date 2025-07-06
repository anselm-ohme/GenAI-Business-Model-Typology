Overview
This repository accompanies the research paper:

"Where Do They Fit? Categorizing Entrepreneurial Ventures in the Age of Generative Artificial Intelligence"
Anselm Ohme, ESCP Business School, Berlin

The paper proposes a novel taxonomy to systematically categorize entrepreneurial ventures leveraging Generative AI (GenAI). It addresses the limitations of existing digital venture taxonomies that fail to account for the unique characteristics of GenAI-driven ventures, such as heavy reliance on foundational models, high upfront compute costs, blurred IP boundaries, and probabilistic user experiences.

🔬 About the Paper
The study introduces a two-dimensional taxonomy to classify GenAI ventures using:

General Intelligence: Ranging from low to high, based on standardized model performance metrics (e.g., MMLU-Pro, GPQA Diamond).

Pricing Strategy: From low to high, measured by price per million tokens.

By combining these dimensions, the taxonomy defines four venture types and provides a strategic framework for entrepreneurs, investors, and regulators to understand positioning, capital allocation, and policy implications.

💡 Repository Purpose
This repository will be used to:

Share code implementations of the taxonomy framework.

Provide example analyses and visualization scripts (e.g., venture mapping in the intelligence/pricing matrix).

Release datasets used or referenced in the study (where permissible).

Facilitate future extensions (e.g., adding new dimensions, supporting new model evaluations).

📁 Repository Structure
bash
Kopieren
Bearbeiten
📄 README.md
📂 data/          # Example data files and venture intelligence/price scores
📂 notebooks/     # Jupyter notebooks for taxonomy visualization and analysis
📂 src/           # Core code implementing taxonomy logic and helper functions
📂 figures/       # Visual assets (taxonomy diagrams, example plots)
LICENSE
🚀 Getting Started
Prerequisites
Python 3.9+

Recommended: pip install -r requirements.txt (requirements file to be provided)

Example Usage
python
Kopieren
Bearbeiten
from src.taxonomy import classify_venture

# Example: classify a venture
venture = {
    "intelligence_score": 68,
    "price_per_million_tokens": 0.96
}
quadrant = classify_venture(venture)
print(quadrant)
📊 Data & Figures
The repository includes the example venture data as used in the paper (Table 2), as well as code to reproduce the taxonomy plots (Figures 3 & 4).

🧑‍💻 Author
Anselm Ohme
ESCP Business School, Berlin
aohme@escp.eu

🤝 Contributing
Contributions are welcome! If you'd like to suggest improvements to the taxonomy framework or add analyses, please open an issue or submit a pull request.

📄 License
This repository is distributed under the MIT License.

🔗 Related Links
Full paper PDF (you may link to the PDF or journal page)

Artificial Analysis — source for intelligence scoring

References and further reading listed in the paper

