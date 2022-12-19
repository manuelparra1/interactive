interactive_titanic_df.mov
# Interactive Buttons & Sliders -> Plotting
### Python Virtual Environments
I could only get interactive & dynamic graphs to work in a virtual enviroment with Jupyter Lab. This solves library dependecy issues.  The virtual environments can be easily deleted later.
#### Create a working directory for Jupyter Lab notebook/github repo. 
> Also home for the  Python Virtual Environment.

##### 1. Setup Directory
```bash
cd ~/codeup-data-science/
```
```bash
mkdir interactive-titanic
```
```bash
cd interactive-titanic
```
##### 2. Create Python Virtual Environment
```bash
python3 -m venv ./
```
##### 3. Switch Environments
> The current directory will temporarily be the python library $PATH

```bash
source /bin/activate
```
##### 4. Re-Install libraries and dependencies to virtual environment
> Only a few megabytes. Worth it for the pain-free setup later.

```bash
pip install upgrade pip
```
```bash
pip3 install panel hvplot seaborn scipy matplotlib pydataset sklearn scikit-learn sqlalchemy pymysql jupyterlab
```
##### 5. Run Jupyter Lab
```bash
jupyter lab
```