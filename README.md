# uc3m Networks Workshop 2025
*Methods Workshop: Social Sciences PhD Program (2025/2026)* <br>
**Teacher**: [Blas Kolic](https://www.linkedin.com/in/blas-kolic-921359171)

Welcome to the Workshop for Network Theory for the Social Sciences: Concepts, Models, and Applications with Python :)

Networks are all about connections. By focusing on relationships rather than isolated units, we can understand structures and patterns of real-world complex systems. You'll see that more things than you can imagine can be represented as networks, and we'll be able to understand many social, biological, and technological phenomena not only from individual characteristics but also from the web of interactions that link them.

This workshop will introduce participants to the foundational concepts and theories of networks in the social sciences and show how these frameworks help explain individual behaviors and collective outcomes. We will examine how network structures help explain social, political, economic, and cultural dynamics; learn to visualize and analyze networks using Python; and connect empirical patterns to social theory. By the end, participants will also understand the principles behind generative and statistical models of social networks and how to apply them in practice.

## Workshop contents
You can find a detailed syllabus of the course [here](https://docs.google.com/document/d/1tbUFCsfmJMqQ1RelFVrBqFgI3F6eA9p0Fdt3vsGC9LE/edit?usp=sharing). We will have one session per week and, for each session, I'll update this repository with its corresponding material, which will consist of a theoretical part (through slides) and a practical part (through Jupyter notebooks). 
- Python and Jupyter notebook setup instructions below or in the course syllabus.

The material is divided as follows:
1. **Introduction to networks and Python** ([slides](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_1/01_introduction_to_networks_and_python_slides.pdf), [tutorial (viewer)](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_1/01_introduction_to_networks_and_python.html), [session folder](https://download-directory.github.io/?url=https://github.com/blas-ko/uc3m_networks_workshop_2025/tree/main/session_1))
2. **Network models and structural analysis** ([slides](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_2/02_network_models_and_structural_analysis_slides.pdf), [tutorial (viewer)](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_2/02_network_models_and_structural_analysis.html), [session folder](https://download-directory.github.io/?url=https://github.com/blas-ko/uc3m_networks_workshop_2025/tree/main/session_2))
3. **Link prediction and network inference** ([slides](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_3/03_link_prediction_and_network_inference_slides.pdf), [tutorial (viewer)](https://blas-ko.github.io/uc3m_networks_workshop_2025/session_3/03_link_prediction_and_network_inference.html), [session folder](https://download-directory.github.io/?url=https://github.com/blas-ko/uc3m_networks_workshop_2025/tree/main/session_3))
4. **Dynamics on networks**

## Contact
If you have any comments or questions, please write me at:
> blas.kolic@uc3m.es

<br>
<hr>

### Python Installation and Setup

#### 1. Install Miniconda (Recommended)
1. Download **Miniconda3**:  
   https://www.anaconda.com/download/success
2. Install Miniconda3 and tick:
   - “Register Miniconda3 as my default Python”
   - “Clear the package cache upon completion”

#### 2. Create and Activate a Python Environment
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

#### 3. Install Required Python Packages
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

#### 4. Install Visual Studio Code (VS Code)
1. Download VS Code: https://code.visualstudio.com/  
2. Open VS Code  
3. Go to the **Extensions** tab  (looks like <img width="34" height="24" alt="image" src="https://github.com/user-attachments/assets/504cce94-4cbc-4bda-a0c7-3bbd52d05bfe" />)

4. Install:
   - **Python** extension  
   - **Jupyter** extension  

#### 5. Windows Note: Execution Policy Error
If you get an `Execution_Policies` error:

Open **PowerShell as Administrator** and run:

```powershell
Set-ExecutionPolicy RemoteSigned
```

#### 6. Running Jupyter Notebooks

##### Option A (Preferred): VS Code
Open any `.ipynb` file directly in VS Code.

##### Option B: Command Line

```bash
conda activate networks_workshop
jupyter lab
```

This will open JupyterLab in your browser.
