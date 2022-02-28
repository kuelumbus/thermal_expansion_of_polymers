# Gray and black box model for the thermal expansion of polymers

The Python notebooks in this repo show the modeling of the thermal expansion of polymers using a (tiny) toy data set. The black box (neural network) model is most probably not usable because the data set is too small. 

# Install

[Poetry](https://python-poetry.org/docs/) must be installed. 

```bash
git clone https://github.com/kuelumbus/thermal_expansion_of_polymers
cd thermal_expansion_of_polymers
poetry install
```

Check out the notebooks:

- [dataset.ipynb](thermal_expansion_polymers/dataset.ipynb) for the data set and sources

- [gray_box.ipynb](thermal_expansion_polymers/gray_box.ipynb) for the gray box models (least square)

- [black_box.ipynb](thermal_expansion_polymers/black_box.ipynb) for the black box model (neural network)  
