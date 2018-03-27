# jupyter-d3-integration
POC for d3 integration in jupyter notebook to establish two way communication

# pip-based installation
1. Install [python](https://www.python.org/downloads/) if it's not already installed

2. Install virtualenv:

  [sudo] pip install virtualenv

3. Clone this repository:

  git clone https://github.com/sreekanthreddy1991/jupyter-d3-integration
  cd jupyter-d3-integration

4. Create and activate a virtualenv:

  virtualenv ./env

5. Activate the virtualenv:

  source env/bin/activate

(From this point on, any `pip install` commands will put stuff inside `./env`, so if installation gets messed up
somehow, you can just `deactivate; rm -rf env` and start over fresh. Also note that you need to
`source env/bin/activate` every time you open a new terminal for the stuff inside `env` to be used)

6. Install `ipywidgets` and `pandas`:

  pip install ipywidgets
  pip install pandas

7. Run Jupyter notebook, and stuff *should* work:

  jupyter notebook