# secret_seminar_ml

Clone the git repo and install virtualenv as well as jupyterlab:
  ```
  git clone https://github.com/kimeels/secret_seminar_ml.git

  python3 -m pip install --user virtualenv
  
  pip install jupyterlab
  ```
Change directories into MALT and create a virtual environment:
  ```
  cd secret_seminar_ml

  python3 -m venv ml_tut_venv
  
  ```

Start the virtual env and install the necessary packages using the requirements file:
  ```
  source malt_env/bin/activate

  pip install -r requirements.txt
  
  python -m ipykernel install --user --name=ml_tut_venv
  ```
