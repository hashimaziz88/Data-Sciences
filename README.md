# Exploratory Data Analysis:

Bootcamp Exploratory Data Analysis (648)
For raw project instructions see: http://syllabus.africacode.net/projects/data-science-specific/
bootcamp-exploratory-data-analysis/

## Directory structure

```
├── data
│   └── data.csv
├── notebook
│   └── eda.ipynb
├── README.md
├── requirements.txt
└── .gitignore  
```
---

## Usage

### Cloning the Repository:

The [Project Repository](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python).

To get started go to the Project repository on Github and clone the Git repository to your local machine. This can be done by clicking the code button and copying the URL to clone.

 Open a terminal and run the following command:

```
git clone https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python.git
```

This command clones the Git repository, creating a local copy of the entire project along with its version history.

![Screenshot 2024-03-06 112443](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/2160c43d-d11e-4736-b6f3-2f6b0b5b45cb)

### Requirements for Project to Run:

Ensure that you have Python 3.12.1 installed. You can download it from the official Python website: [Python 3.12.1 Download](https://www.python.org/downloads/release/python-3121/)

Following the hyperlink will take you to the Python download page, scroll to the bottom of the page where the download links are, check which package applies to your machine and download the approprate version of python for your specific machine.

![Screenshot 2024-03-06 144805](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/4637d621-a5aa-4955-9c87-693fd3de569f)


### Creating and Activating virtual environment

Open a terminal or command prompt in the project directory and run the following command to create a virtual environment named venv.
```
python -m venv venv
```
Thereafter activate Virtual environment.
For Windows Machines:
```
.\venv\Scripts\activate
```

For other machines such as mac or Linux:
```
source venv/bin/activate
```

Once activated, your terminal prompt should change, indicating that you are now working within the virtual environment.

### Installing Dependencies:

Use the Python package manager (pip) to install all the required dependencies listed in the "requirements.txt" file. Open a terminal and run the following command:

```
pip install -r requirements.txt
```

This ensures that the project has all the necessary libraries and modules.

### Running the Project Locally:

1. Install Visual Studio Code by downloading it from [here](https://code.visualstudio.com/download).

Follow the Hyperlink which will take you to the Visual Studio code download page. Thereafter choose the appropriate version and package for your machine and download it.

![Screenshot 2024-03-06 115920](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/c005c706-ab5a-4857-a41e-bbed21df49fb)


2. Once installed open VS code.
   
![Screenshot 2024-03-06 113124](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/bcbbb599-d41a-46fe-a09e-622d54a086bc)

3. Install the Jupyter notebook extension in VSCode. You can find it on the Visual Studio Code marketplace [here](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). This can be done in VS code by navigating to the extension tab clicking on it and searching Jupyter and installing the appropraite extension.

![Screenshot 2024-03-06 113236](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/6051c0c6-7cfb-4c66-8d37-ee836e1e7a3a)

![Screenshot 2024-03-06 113308](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/0a2034d6-bc0d-4e9b-ac86-7b41d79a7b6d)

4. Open the project folder in Visual Studio Code by clicking on File in VS code and naviagting to the folder in which the Project is located.
   
![Screenshot 2024-03-06 113641](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/1f85b11b-f678-4919-a51e-05b61cd00fc0)

![Screenshot 2024-03-06 112626](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/89658af9-5cce-4c20-870a-5420c7a80e7a)

5. Launch the Jupyter notebook from the VSCode interface by clicking on the eda.ipynb file in the notebooks folder.

![Screenshot 2024-03-06 133336](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/ab61e9d2-f0e5-4814-9509-1821c31577e0)

6. To select the Jupyter kernel, open your Jupyter notebook in VS Code and click on the kernel selection dropdown at the top right corner. Choose the correct kernel (Python 3.12.1) to run your notebook.

![Screenshot 2024-03-06 113706](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/fc278d61-dc1c-40a5-bbd3-52fe16d06628)

7. After Selection the correct Kernel from the drop down menu the Run All button can be pressed, this runs all code snippets within the Jupyter notebook. Code snippets which need to ouput a resullt, tables or Graphs will then be displayed below its correlating code box.

![Screenshot 2024-03-06 113928](https://github.com/Umuzi-org/Hashim-Muhammad-648-bootcamp-exploratory-data-analysis-python/assets/78796582/29ad943a-d446-4de6-af1e-80af807e43bf)

8. Alternatively, you can explore other ways to run Jupyter Notebook by visiting [Jupyter Installation](https://jupyter.org/install).

### Deactivating the virtual environment.

When you're done working on your project, deactivate the virtual environment by inputting this in the terminal and then pressing Enter.

```
deactivate
```
---
