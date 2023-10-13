# AI & Automation Academy example notebooks

## Quick start

1. Create a new virtual environment and activate it:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a .env file in this directory (notebooks).
4. Add your OpenAI API key. You can find it [here](https://platform.openai.com/account/api-keys) after you log in. Your .env file should look like this (do not wrap the key in quotes):

    ```bash
    [openai]
    OPENAI_API_KEY = sk-**************************
    ```
    
5. Run the Jupyter notebook server:

    ```bash
    jupyter notebook
    ```

6. Open the notebook you want to run and follow the instructions in the notebook.