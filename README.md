# Agents

# Warning
Open Interpreter cuts code short especially the parenthesis/bracket at the end of code. To avoid this, tell your model to:
# "Add a comment at the end of the code, e.g., # End of code"


Usage:

For python 3.11
```bash
pip install -r requirements.txt
```
---
For python 3.10
```bash
pip install -r 310requirements.txt
```
The file requirements.txt helps a smooth installation of Open Interpreter with Python 3.11 and 3.10 on Ubuntu 2204.

**The key to success is actually pip install setuptools<81**

For pyhton 3.11 pip install setuptools==80 has been tested; 3.10, ==70.

For python 3.12, 3.13 and 3.14 open interpreter installations fail on Ubuntu 2204, I uploaded the logs. 

---
For python 3.12
```bash
pip install -r 312requirements.txt
```
The python 3.12 version has been tested on Ubunbu 2404.
