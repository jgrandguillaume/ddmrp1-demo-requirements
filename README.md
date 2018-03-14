# Use with Python 3

Create a virtual environment

~$ virtualenv ddmrp11

Activate virtual environment

~$ source ddmrp11/bin/activate

*** Anytime you want to go out from virtual environment just type: $ deactivate

Check if we are using virtualenv correctly

~$ which pip

~$ which python

Install the requirements.txt

pip3 install -r https://raw.githubusercontent.com/jgrandguillaume/ddmrp1-demo-requirements/master/requirements.txt --pre
pip3 install bokeh==0.12.7
