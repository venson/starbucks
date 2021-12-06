# starbucks
[medium link](https://vensonhunt.medium.com/get-more-profit-with-offers-9b88b9be3b8a)
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
      + Mac
         - `pip install pandas matplotlib seaborn sklearn statsmodels scipy`

# 2. Start jupyterlab
   run jupyterlab

  `jupyter-lab`

# 3. Project Motivation
  By go through the starbucks data, try to find something usefull:
    1. Does offers change customer behavior?
    2. Does the change of customer behavior make more profit?
   And our final goal: 
   Can we find a way to control the cost of offers, or get more profit from offers?
# 4. File Descriptions
   `Starbucks_Capstone_notebook.ipynb`
   The jupyter-lab file for starbucks capstone
   `data/`
   The dictionary of starbucks

   The following files are included in this dictionary:
    - portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
    - profile.json - demographic data for each customer
    - transcript.json - records for transactions, offers received, offers viewed, and offers completed

# 5. Results
   1. With offers, the profit decreased 67931.25 dollars total,2.43 dollars for each order,if the consumers came to starbucks as usual without offers.
But we get 18.89% of the orders with a increase in profit
   2. It possible to find a model to predict the profit difference with orders.
    
# 6. Assumption
   1. The model a consist gross profit margin, which is not very accurate for the profit prediction of each order.
   2. We assume consumers's order follow normal distribution and have consistant pattern, in actual they may come alone or with different numbers of friends, which should make a lot of difference. 
