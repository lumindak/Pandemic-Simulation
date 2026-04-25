
There is no threshold that decides a pandemic level.How ever if an outbreeak grows or dies out can be
decided by R0.

if R0 >1 → the disease spreads

if R0<1 → the disease dies out

R0 is the average number of people that one infected person will pass a disease to in a population where:

1.No one is immune

2. No interventions are in place (no vaccines, masks, distancing, etc.)

This concept is known as the Basic reproduction number.

It depends on:
1.how contagious the disease is
2. how often people interact
3. how long someone is infectious
Once immunity or interventions exist, we use a different number:Rt (effective reproduction number). 

Herd immunity threshold = 1-1/R0
Rt​=R0​×(1−immune fraction) ; if Rt<1 disese dies out.
    immune fraction = (vaccinated + recovered)/total poputation

    Rt<1  ==> immune fraction > 1 - 1/R ( for typical flu R0 is between 1.2-1.5.
  
Ref: ChatGpt

## Environment setup

1. Create a virtual environment in the project root:

```bash
python -m venv .venv
```

2. Activate the virtual environment:

```bash
# Windows (PowerShell)
.venv\Scripts\Activate.ps1

# Windows (cmd)
.venv\Scripts\activate.bat
```

3. Install project dependencies:

```bash
pip install -r requirements.txt
```

## Run the models

This project contains two notebook models:

- `SIRmodel1.ipynb`
- `My_SIRmodel.ipynb`

You can run them using either VS Code or Jupyter.

### Option 1: Run in VS Code

1. Open a notebook file.
2. Select the `.venv` Python kernel (top-right in the notebook editor).
3. Run all cells from top to bottom.

### Option 2: Run in Jupyter from terminal

```bash
jupyter notebook
```

Then open `SIRmodel1.ipynb` or `My_SIRmodel.ipynb` in the browser and run all cells.
