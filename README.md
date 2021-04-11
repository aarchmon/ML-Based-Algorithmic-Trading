# Machine Learning-Based Algorithmic Trading

![Algorithmic Trading](./Images/algorithmic_trading.jpeg)

---

## Technologies

The entirety of this notebook was generated via _Google Colab_. Therefore, you are not required to import any modules onto your personal machine. Below is a list containing all of the _Python 3.7 +_ modules that are utilized in this notebook.

[pandas](https://pandas.pydata.org/pandas-docs/stable/) - Data analysis module.

[pathlib](https://docs.python.org/3/library/pathlib.html) - Object-oriented filesystem path library.

[tensorflow](https://pypi.org/project/tensorflow/) - High-performance numerical computation library. 

[sklearn](https://sklearn.org/) - Machine learning module.

---

## Installation Guide

With your _Python 3.7+_ environment, run the following commands via CLI:

```
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```

---

## Examples

![SVC](./Images/SVC.png)

![Decision Tree](./Images/Decision_Tree.png)

---

## Conclusion

![Comparison Plot](./Images/Combined.png)

---

## Usage

1. Clone repository onto your personal machine. 

2. Open _Jupyter Lab_ or _Jupyter Notebook_ via _Anaconda Navigator_ and navigate to the directory in which the file `machine_learning_trading_bot.ipynb` is present. _All relevant code for this repository will be executed via Jupyter Notebook and no output will be printed to the command line_. Ensure that all relevant dependencies and _Python_ modules are installed (see __Technologies__ and __Installation Guide__ for more details) before attempting to execute code within _Jupyter Notebook_; otherwise, you will receive multiple interpreter errors! 

3. With the notebook open, start at the very first cell reading "__Credit Risk Classification__" (a cell will be active when a rectangular border is surrounding the area in question). Run each cell in sequential order. _It is vital that all cells are ran in sequential order or your notebook will generate compiler errors_!. 

---

## Contributors

New development created by Aaron C. Montano. **Code from 'Initial commit.' commit originates from UC Berkeley Extension and I do not claim original ownership nor scholarship**.

---

## License

Software tool available for public use. 
