# How to Set Up Jupyter AI Locally?

This guide outlines the steps to set up Jupyter AI locally and run the course notebooks on your machine.

## Installing Jupyter AI

This course uses Jupyter AI v3 beta (3.0.0b7), as Jupyter AI v3 is not yet officially released. To install the beta version, run this command in your terminal:

```bash
pip install "jupyter-ai==3.0.0b7"
```

Once installation is complete, navigate to your working directory and launch JupyterLab by typing:

```bash
jupyter lab
```

You should now see the chat bubble in the left sidebar.

> **Note:** 3.0.0b8 beta version was released after the course was filmed. Feel free to explore the newest version as it has enhanced UI.

## Setting Up the Model Provider in JupyterLab

Before you can start interacting with Jupyter AI, you need to configure the model provider and API key (this step was already set up in this course):

1. Click **Settings** in the top menu bar
2. Select **AI Settings** from the drop-down menu (in the newest version, it is **Jupyternaut Settings**)
3. Under **Chat model**, select your preferred model (this course uses `openai/gpt-5-chat-latest`) and click **Update Chat Model**
4. Under **Secrets and API keys**, enter your API key
