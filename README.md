# TensorFlow 2 Workshop Material

## Installation

The workshop material consists of slides, a hand-out and, most importantly,
Jupyter notebooks. The notebooks depend on several components of TensorFlow and
TensorFlow Extended and installing these dependencies leads straight to
dependency hell. I recommend to 

- clone the repository 

  ```shell
  git clone https://github.com/thomastimmermann/TensorFlow-2-Workshop.git
  ```
  
- change into the cloned repository, set up and activate a virtual environment and install the dependencies using the file `requirements.txt`:

   ```shell
   cd TensorFlow-2-Workshop
   python3 -m venv .venv
   source .venv/bin/activate
   pip install --upgrade pip setuptools
   pip install -r requirements.txt
   ```
   

- or go to the repo website and click https://mybinder.org/v2/gh/thomastimmermann/TensorFlow-2-Workshop/master
