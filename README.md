# Film Dataset Analysis Assignment

## Setup Instructions

### Prerequisites
- Python 3.8+
- MySQL Server 8.0+
- Sakila Sample Database

### Installation

1. Create virtual environment:
```bash
python -m venv film-analysis-env
source film-analysis-env/bin/activate  # Mac/Linux
# or
film-analysis-env\Scripts\activate     # Windows
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Configure database connection:
- Open the notebook
- Update DB_CONFIG dictionary with your MySQL credentials:
    - user: Your MySQL username
    - password: Your MySQL password
    - database: 'sakila'

