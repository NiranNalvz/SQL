To use sql in mysql using notepad ,installation procedure:


(https://www.python.org/downloads/

mkdir sql_notebook
cd sql_notebook

python -m venv env

env\Scripts\activate

pip install --upgrade pip

pip install notebook

pip install ipython-sql

pip install prettytable==0.7.2

pip install mysql-connector-python

jupyter notebook

%load_ext sql
%sql mysql+mysqlconnector://root:root@localhost/test(://user:password@host/dbname)

%%sql
show databases;)
