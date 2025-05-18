
This project sets up the base structure for the Solar Challenge, including Python environment, folders, and CI with GitHub Actions.

Environment Setup (using Conda)

Follow these steps to set up the environment on your local machine:


1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/solar-challenge-week1.git
   cd solar-challenge-week1

2. Create a Conda environment:
    ```bash
    conda create -n solar-env python=3.10
    ```

2. Activate the environment:
    ```bash
    conda activate solar-env
    ```

3. Install project dependencies:
    ```bash
    pip install -r requirements.txt
    ```

Folder Structure

├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
 |------ src/
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
