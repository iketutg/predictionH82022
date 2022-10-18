# predictionH82022
Latihan membuat model dan Deploy Apps Prediction menggunakan Data set : 
https://raw.githubusercontent.com/iketutg/my_example_ds/main/data/Placement_Data_Full_Class.csv

- Register Heroku 
- Python 3.10.8 


Install Python Multi Version 

1. Download dan Install pyenv 
2. Install Python sesuai dengan yang tuju :
 pyenv install 3.10.8
python-build: definition not found: 3.10.8

See all available versions with `pyenv install --list'.

If the version you need is missing, try upgrading pyenv:
cd /Users/iketutg/.pyenv/plugins/python-build/../.. && git pull && cd -

3. List Python yang di laptop kita 
pyenv verions 

4. Set python version di laptop
pyenv global 3.10.8

5. untuk mengecek 
pyenv version
atau 
python -V

6. Membuat Environment Python 

python3 -m venv heloflask    

7. Activate 

 - untuk di linux atau mac 
source heloflask/bin/activate   

- windows 
./heloflask/bin/activate.bat 

8. Install library  
pip install -r requirements.txt

9. Runing on local computer 
    export FLASK_APP= app
    export FLASK_ENV=development 
    flask run -p 5003 

10. to deploy Heroku 
    1.  Register 
    2.  Download heroku client 
    3.  Create New App helloh8py2022
    4.  Option for Deploy using Heroku Git
        1.  $ heroku login
        2.  $ cd my-project/
        3.  $ git init
        4.  $ heroku git:remote -a helloh8py2022
        5.  $ git add .
        6.  $ git commit -am "make it better"
        7.  $ git push heroku master
        8.  Wait until Done and tested  https://helloh8py2022.herokuapp.com/
11. Done

