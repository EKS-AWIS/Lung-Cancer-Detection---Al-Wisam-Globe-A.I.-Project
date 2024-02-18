Sure, here's a simple step-by-step guide to install Python on a Windows computer and then use pip to install dependencies from a requirements.txt file:

1.**Download Python Installer**:

- Visit the official Python website at https://www.python.org/.
- Click on the "Downloads" tab and select the latest version of Python for Windows.
- Download the installer executable file (usually with a .exe extension).

2.**Run Python Installer**:

- Once the installer is downloaded, double-click on the executable file to run it.
- Check the box that says "Add Python x.x to PATH" (x.x represents the Python version).
- Click "Install Now" to begin the installation process.

3.**Verify Python Installation**:

- After the installation is complete, open the Command Prompt by searching for "cmd" in the Windows search bar.
- Type `python --version` and press Enter. You should see the installed Python version displayed in the Command Prompt.

4.**Navigate to Your Project Directory**:

- Open File Explorer and navigate to the directory where your Python project is located.
- Alternatively, open the Command Prompt and use the `cd` command to change the directory to your project folder.

5.**Install Dependencies from requirements.txt**:

- Ensure that your project contains a `requirements.txt` file listing all the dependencies required by your Python code.
- In the Command Prompt, navigate to the directory containing your `requirements.txt` file.
- Run the following command to install the dependencies listed in the file:

  ```

  pip install -r requirements.txt

  ```
- Pip will automatically download and install all the required packages listed in the `requirements.txt` file.

6.**Run Your Python Code**:

- Once all the dependencies are installed, you can run your Python code using the Command Prompt.
- Navigate to the directory containing your Python script.
- Run your Python script by typing the following and pressing Enter.
  ```

  python main.py

  ```

## IMPORTANT NOTE

Please ensure that you have downloaded the dataset from [IQ-OTH/NCCD Kaggle](https://www.kaggle.com/datasets/adityamahimkar/iqothnccd-lung-cancer-dataset) and have kept it in the same folder as the code inside a folder named `dataset`


