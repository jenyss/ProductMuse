# ProductMuse
Product Discovery exploration where data from Jira and Miro are processed in a Jupyter Notebook, transformed into DataFrames (using pandas), and analysed by an LLM (OpenAI GPT-4) to identify product opportunities based on a product discovery template.

If you have any questions or would like to collaborate, feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jenya-stoeva-60477249/). You're more than welcome!

![ProductMuse](ProductMuse.png "ProductMuse")

## Intallation

<b>Prerequisites</b>

* Access to <b>JupyterLab, Google Colab<b>, or another interactive computing environment to run this Jupyter Notebook.
* <b>Access to a Large Language Model API<b> for evaluating your product discovery prompts.
* <b>API access to Jira, Miro<b>, or another tool that stores data for product discovery.

### Step 1: Clone the Repository

Clone this repository to your local machine:
```
git clone <REPOSITORY_URL>
cd <PROJECT_FOLDER>
```

### Step 2: Open Jupyter Notebook in JupyterLab

Ensure that ```<PROJECT_FOLDER>``` is accessible in JupyterLab.
 * In JupyterLab, use the "Open from Path" option to load ```ProductMuse_v1.ipynb```.
 * <b>Similarly, load ```oneConnection.env``` and populate the variable keys with appropriate values.</b>

### Step 3: Run the Jupyter Notebook

To execute the notebook, select each cell and press ```Shift + Enter```.
