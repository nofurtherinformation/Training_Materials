# June Training for VoteKit in 2025

More stuff to come soon!


## Running with Docker

Docker is a program to help describe and reproduce environments for running applications and analysis. It helps us start up a Python environment on your computer, without the need to manually install and configure Python and data anaylsis modules.

To get started:

1. Install [Docker](https://www.docker.com/)
2. Open your terminal, and navigate to this repository (eg. `cd /Users/Me/Documents/Github/Training_Materials`)
3. Run `docker compose up`

Your computer will set up the required programs, libraries, and configuration. This may take a few minutes. You should see a message that says something like "Jupyter Server 2.16.0 is running at...", which indicates the set up was successful.

Now, navigate to [http://127.0.0.1:8888](http://127.0.0.1:8888) in your web browser and you can use jupyter.

To shut down Docker, you can use the Docker Desktop application or hit Control+C in your terminal.

## Runnig with Docker and Dev Containers!

Follow the above to start the docker compose environment.

1. Install the dev containers extension with yuor IDE (VS Code, Cursor).
2. Open the command pallete (cmd+shift+p) and look for 'Dev Containers: Attach to Running Container' 
3. Attach to the relevant docker container

You may need to re-install the Python and jupyter extensions in your IDE from within the dev container for property syntax.

Choose the 'venv' python environment for your notebooks. If using cell-based (`# %%`) syntax python files, use the command palette to `Python: Select Interpreter`