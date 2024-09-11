# NAICS Persona Generator

This project generates personas, problems, and solutions for all 1,057 NAICS codes using AI, quantum computing, and the Metaverse. It automates the process through Python and optionally integrates OpenAI GPT-4 for more detailed content generation.

## Features
- Generates personas, problems, and solutions for businesses across all NAICS sectors.
- Optionally uses GPT-4 to generate AI-powered solutions.
- Outputs data as a CSV file.

## Getting Started

### Prerequisites
- Python 3.x
- OpenAI API Key (optional for AI integration)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/naics-persona-generator.git
    cd naics-persona-generator
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Place your NAICS dataset in the `data/` directory as `naics_codes_full.csv`.

### Running the Script

To generate personas, problems, and solutions:

```bash
python src/persona_generator.py
