# Python Installation and Setup

### 1. Install Miniconda (Recommended)
1. Download **Miniconda3**:  
   https://www.anaconda.com/download/success
2. Install Miniconda3 and tick:
   - “Register Miniconda3 as my default Python”
   - “Clear the package cache upon completion”

### 2. Create and Activate a Python Environment
Open a command shell (**Anaconda Prompt** on Windows; **Terminal** on macOS/Linux) and run:

```bash
conda create -n networks_workshop
```

If prompted:
- Press `a` to accept terms
- Press `y` to continue

Activate the environment:

```bash
conda activate networks_workshop
```

Install pip (package installer for python):

```bash
conda install pip
```

### 3. Install Required Python Packages
With the environment active:

```bash
conda activate networks_workshop
pip install numpy pandas matplotlib networkx scikit-learn jupyterlab
```

**Package overview:**
- **NumPy** – Fast math with arrays and matrices  
- **Pandas** – Clean and analyze tabular data  
- **Matplotlib** – Plotting and visualization  
- **NetworkX** – Lets you build and study graphs and networks  
- **scikit-learn** – Train ML models and measure performance with a simple, unified toolkit  
- **JupyterLab** – Interactive workspace for code, notes, and data exploration  

### 4. Install Visual Studio Code (VS Code)
1. Download VS Code: https://code.visualstudio.com/  
2. Open VS Code  
3. Go to the **Extensions** tab  (looks like <img width="34" height="24" alt="image" src="https://github.com/user-attachments/assets/504cce94-4cbc-4bda-a0c7-3bbd52d05bfe" />)

4. Install:
   - **Python** extension  
   - **Jupyter** extension  

### 5. Windows Note: Execution Policy Error
If you get an `Execution_Policies` error:

Open **PowerShell as Administrator** and run:

```powershell
Set-ExecutionPolicy RemoteSigned
```

### 6. Running Jupyter Notebooks

#### Option A (Preferred): VS Code
Open any `.ipynb` file directly in VS Code.

#### Option B: Command Line

```bash
conda activate networks_workshop
jupyter lab
```

This will open JupyterLab in your browser.
