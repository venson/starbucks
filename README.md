# starbucks
[medium link](https://medium.com/@venson.hunt/offer-recommand-for-starbucks-9cacafeaddfa)
# 1. Installation

1. Install Juypterlab first
      + Mac
         - `brew install jupyterlab`
      + Archlinux
        - `sudo pacman -S jupyterlab`
2. install pip for python
      + Archlinux (not recommended to use pip on archlinux)
         - `sudo pacman -S python-pip`(outdated since 2021-01-26)
      + Mac
         - `curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

3. install python module
      
      + Archlinux
         - It is prefered to install systemwide module from arch official repository instead of pip)
         - `sudo pacman -S python-pandas python-matplotlib python-seaborn python-scikit-learn python-scipy`
         - `yay -S python-lightgdm python-hyperopt xgboost-git
      + Mac
         - `pip install pandas matplotlib seaborn sklearn statsmodels scipy lightgdm hyperopt xgboost`

# 2. Start jupyterlab
   run jupyterlab

  `jupyter-lab`

# 3. Project Motivation
  By go through the starbucks data, try to find something usefull:
  
    Let's give the customer the offer that they would like to use.
# 4. File Descriptions
   `Starbucks_Capstone_notebook.ipynb`
   The jupyter-lab file for starbucks capstone
   
   `data/`
   The dictionary of starbucks

   The following files are included in this dictionary:
   
    - portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
    - profile.json - demographic data for each customer
    - transcript.json - records for transactions, offers received, offers viewed, and offers completed


    

