# Overview

Creating medical chat-bot using Python (*Flask*) and machine learning algorithms for purposes of project for the course of Intelligent Systems at the Faculty of Organization and Informatics, University of Zagreb. 

# Requirements

Python 3.5 or newer.

Dependencies:

- Flask
- PyTorch
- NLTK
- NumPy
- Scikit-learn
- Pandas

# Install requirements

Before running the application you need to install the dependencies. We recommend to use the virtual environment
[virtualenv](https://pypi.org/project/virtualenv/) for this.

Linux:

```
python3 -m venv venv
venv/bin/activate
pip install flask torch nltk numpy sklearn pandas
```
Windows:

```
py -3 -m venv venv
venv\Scripts\activate
pip install flask torch nltk numpy==1.19.3 sklearn pandas
```



In order for _nltk_ tokenization to work, the _'punkt'_ package must be downloaded. To do this, simply enter the Python shell and run the following:

```python
import nltk
nltk.download('punkt')
```

This will install all the required dependencies needed to run the application successfully.

## Run

To run MedicalChatbot, `cd` into MedicalChatbot repo on your computer and run `python -m flask run`. This will run the Flask 
server in development mode on localhost, port 5000.

`* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)`
