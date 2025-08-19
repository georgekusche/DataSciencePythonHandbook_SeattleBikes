# DataSciencePythonHandbook_SeattleBikes
Basic linear modeling exercise to predict the amount of bikers on a given day.

Next steps: 

1. Import weather data as well (probably scrape it from somewhere or see if it is readily available somewhere)
2. cross-validation
3. play around with interactions and/or ridge/lasso?
4. stel voor wat jy dink, die leser.


Geen src (reusable code) nie, the eenvoudige projek. Ek word wel beter en slimmer by die dag :) 

## Quick start (om maklik te clone)

If you just want to run the notebooks:

```bash
git clone https://github.com/georgekusche/DataSciencePythonHandbook_SeattleBikes.git
cd DataSciencePythonHandbook_SeattleBikes
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
jupyter lab --no-browser
