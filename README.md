# Retail Sales Analytics

```markdown
## How to run

> Requires Python 3.x (no database needed to verify logic)

```bash
# 1) Get the code
git clone https://github.com/mattwhittemore/retail-sales-analytics-sql-bi.git && cd retail-sales-analytics-sql-bi

# 2) Create & activate a virtual environment
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .\.venv\Scripts\Activate.ps1

# 3) Install & run tests (quick KPI validation)
pip install -r requirements.txt
pytest -q
