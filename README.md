## Neural Framework

Simple, but yet powerful neural computation framework for fast prototyping.

### Install with pip
```
pip install git+https://github.com/vegardbotnen/neural_framework.git
```

### Upgrade with pip
```
pip install --upgrade git+https://github.com/vegardbotnen/neural_framework.git
```


### How To
```python
from neural_framework.brain import Brain, fully_connected

fc = fully_connected([2,4,4,1])
fc.show()
```