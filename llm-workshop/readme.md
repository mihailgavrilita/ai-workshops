LLM Workshop -- Data Analysis using Large Language Models

### Quickstart

```bash
git clone https://github.com/mihailgavrilita/ai-workshops
cd llm-workshop
pip install -r requirements.txt

curl -fsSL https://ollama.com/install.sh | sh 
ollama pull llama3.2
ollama run llama3.2

jupyter lab
```

And now in a bit more detail :) Before beginning, ensure that you have installed `git`, `python` and `pip`. Running in a virtual environment is recommended. Choose a folder you want to download the project and run:

```bash
git clone https://github.com/mihailgavrilita/ai-workshops
cd llm-workshop
```

Now you can install the dependencies:

```bash
pip install -r requirements.txt
```

After that's done, you should install `ollama`. 
Follow the installation instructions for your OS provided on their website.
Finally, run:

```bash
pip install jupyterlab
jupyter lab
```

You should see the Jupyter Lab interface open in your browser.
