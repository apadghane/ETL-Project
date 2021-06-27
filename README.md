# ETL Assignment
![etl](https://www.astera.com/wp-content/uploads/2019/10/etl.png)<br><br><br>
**Author**: Abhishek Padghane<br><br>
**Task**: In this assigment, Data need to be loaded from source. Transformed in such a fashion that output should be a database supported (sql) file. Transformation that need be done is adding an extra column which will contain date and time.<br><br>
**Tools and Technologies**:
* Python
* Jupyter Notebook
* Pandas
* SqlAlchemy
* Glob
* Dotenv

**Files and Folders**:
* **Analytics:** This folder contains data files<br><br>
* **.envDemo:** Contains credential template for database credentials, insert your db credentials and rename/clone this file as `.env`<br><br>
* **ETL-Assignment-Project.ipynb:** Source code file of this assignment. This notebook file Contains python code of ETL process<br><br>
* **requirements.txt:** Contains third-party libraries/dependencies for this project<br><br>
* **runtime.txt:** Contains version of python used to build this project<br><br>
* **.gitignore:** Contains file and folder name that should not be included in git repository<br><br>
* **README.md:** Project synopsis

**Installation Instructions**:
1. Download [Python](https://www.python.org/downloads/) and install it on your system<br><br>
2. Download [MariaDB](https://mariadb.org/download/) database and install it on your system<br><br>
2. Install virtual environment by `pip install virtualenv`<br><br>
3. Create virtual environment by `python3 -m virtualenv venv` or `python -m virtualenv venv`<br><br>
4. Activate virtualenv by `venv\Scripts\activate` or `source venv/bin/activate` in shell/bash/terminal<br><br>
4. Install requirements by `pip3 install -r requirements.txt` or `pip install -r requirements.txt`<br><br>
5. Insert your db credentials in `.envDemo` file and rename/clone it to `.env`<br><br>
5. To run jupyter notebook type `jupyter notebook` in virtualenv activated shell/bash/terminal

**Screen Shots**:
* Dataset downloaded from kaggle, use this [link](https://i.ibb.co/xD3cwhm/etl1.jpg)
![etl1](https://i.ibb.co/xD3cwhm/etl1.jpg)<br><br>
* Folder and file structure
![etl9](https://i.ibb.co/w4hSF15/etl9.jpg)<br><br>
* Using 4 of the stock data files, renaming them according to problem defination and adding some more files.<br>
![etl2](https://i.ibb.co/YBNhSFq/etl2.jpg)
![etl3](https://i.ibb.co/G0V2pL0/etl3.jpg)
![etl4](https://i.ibb.co/bFKjZhn/etl4.jpg)<br>
* Database creation for storing/loading transfromed data into database<br>
![etl5](https://i.ibb.co/TY5yr5g/etl5.jpg)
![etl6](https://i.ibb.co/JjT7G30/etl6.jpg)
![etl7](https://i.ibb.co/V9Wmk0D/etl7.jpg)<br><br>
* Output of ETL process can be seen from HeidiSql Db ui, transformed data can be seen in tables<br>
![etl10](https://i.ibb.co/jMXQZqV/etl10.jpg)