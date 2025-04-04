## How to run these Jupyter Notebooks  
Jupyter notebooks are interactive documents that let you combine code, text, images, and even graphs, all in one place. They're especially useful for beginners because you can run code step by step and see the results immediately, without worrying about complicated setups. Here are three easy ways to get started:

### 1. Running Jupyter notebooks in Visual Studio Code (VS Code)
What you need:  
- Python installed on your computer  
- Visual Studio Code (VS Code), which you can download from [https://code.visualstudio.com](https://code.visualstudio.com)  

Here’s how to set it up:

1. **Open Visual Studio Code**.
2. Look at the left sidebar and click the icon shaped like four small squares—this is the *Extensions* panel.
3. In the search bar, type "*Python*" and click on the one from Microsoft to install it. (This connects VS Code with Python on your computer.)
4. Next, search for "*Jupyter*" and install it as well. (This lets you run interactive notebooks.)
5. Now, create your notebook:
    - Go to *File → New File*, then save your new file with a name ending in `.ipynb`. For example, you could call it `my_notebook.ipynb`. This tells VS Code it’s specifically a notebook file.
6. You can now write code in small blocks called *cells*. To run each cell, click the "play" button (▶).next to it.

You’ll immediately see results below the code.

### 2. Running notebooks locally using Jupyter notebook server
What you need:  
- Python installed on your computer  

Here’s how you set up a local Jupyter notebook:
1. Open your computer’s terminal (on Windows: Command Prompt or PowerShell; on Mac/Linux: Terminal).
2. Install Jupyter with this simple command (it’s safe to copy-paste):

```bash
pip install notebook
```
This tells Python to install Jupyter for you.

3. Once installed, navigate to the folder containing your notebook (or where you want it to be) in the terminal, then type:

```bash
jupyter notebook
```

4. After you press Enter, a browser window will open automatically at `http://localhost:8888`. (This address just means your notebook runs locally, directly on your own computer.)
5. The web page you see is the Jupyter notebook interface. Here, click on an existing `.ipynb` file to open it, or create a new notebook by clicking *New → Python 3*.
6. Write your code in cells. To run a cell, click the "play" button (▶).

### 3. Running notebooks online using Google Colab (easiest method)
What you need:  
- A Google account  
- A web browser with internet access (no other installation)

1. Go to [https://colab.research.google.com](https://colab.research.google.com).
2. To create a notebook from scratch, simply click on *File → New Notebook*.
3. If you already have a notebook file (`.ipynb`), choose *File → Upload notebook* and pick the file from your computer.
4. In Colab, each code cell has a small "play" button (▶). Click it, or press *Shift + Enter* on your keyboard, and your code runs immediately.

Google Colab automatically saves all your work into your Google Drive, so you don't have to worry about losing it.

*A special benefit of Colab*: It gives you free access to powerful hardware (GPUs or TPUs), especially useful for machine learning tasks (but you don’t need to worry about that yet unless you want to explore advanced topics).
