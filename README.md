# Week 1 Python + Git Lab (Template)

Starter template for an in-class onboarding lab: download a public CSV dataset from a URL, print a quick summary, and generate a simple chart.

## Dataset chosen
Pick exactly one dataset URL, then set it in `analyze.py` (CONFIG section).

Chosen Dataset: MPG (Car Fuel Economy)  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/mpg.csv  
Recommended columns: `origin` (category), `mpg` (numeric)

## How to run
```bash
python3 -m venv .venv
source .venv/bin/activate   # Windows: .\.venv\Scripts\Activate.ps1
pip install pandas matplotlib
pip freeze > requirements.txt
python analyze.py
```

## What it does
- Prints dataset summary (rows/cols, columns list, first 5 rows, grouped averages)
- Generates `output/chart.png`

## Example output
`output/sample_chart.png` is included as a visual example. Your script run should generate/overwrite `output/chart.png`.

## Reflection (write 3–5 sentences)
Replace this section with your own reflection:
The hardest part of this project was setting up the files correctly for upload to Git using the terminal. Being relatively new to the Git environment, we were initially unaware that files needed to be explicitly added and committed before they could be uploaded to GitHub. Additionally, steps involving the .gitignore and README.md files were particularly confusing at first because we did not fully understand their purpose in managing which files should be tracked and how a project should be documented. This made the early setup process slower and more challenging than expected. However, working through these steps helped us better understand how a project is properly structured in Git.

Through this project, we learned how Git commits are useful for uploading files to GitHub in an organized and controlled way. We also learned that files must first be staged in the terminal before they can be committed, which was something I was previously unaware of. Additionally, we realized the importance of making small, focused commits rather than committing everything at once. Writing clear and meaningful commit messages helped us better track changes throughout the project. On the whole, this process improved our understanding of version control and reduced confusion when managing files.

## Generative AI Disclosure (if applicable)
- Tool used: None
- What it was used for:
  - To verify steps into committing to adding/committing/pushing to git.
  - To verify concepts and terminologies used in the project.
- What I personally verified/changed:
  - Using the concepts and terminologies, AI helped us in making our reflection more cohesive and correct.
