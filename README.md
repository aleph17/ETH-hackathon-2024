# ETH-HACKATHON-2024

Installation instructions. In this example we use python3's venv. Feel free to use conda or any other package manager of your choice.

- Create a virtual environment and load it
```bash
python3 -m venv myenv
source myenv/bin/activate
```
- Install qibo
```bash
pip install qibo
```
- Clone our fork of the CAS repository and install it interactively
```bash
git clone https://github.com/visagim/CAS
cd CAS
pip install -e .
```
- Install jupyter notebook
```bash
pip install notebook
```
