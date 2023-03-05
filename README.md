# User-Authentication-in-Flask

## Set up & Installation.

### 1 .Clone/Fork the git repo and create an environment 
                    
**Windows**
          
```bash
git clone https://github.com/Dev-Elie/User-Authentication-in-Flask.git
cd User-Authentication-in-Flask
py -3 -m venv venv

```
          
**macOS/Linux**
          
```bash
git clone https://github.com/Dev-Elie/User-Authentication-in-Flask.git
cd User-Authentication-in-Flask
python3 -m venv venv

```

### 2 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```
or
```source venv/bin/activate```

### 3 .Install the requirements

Applies for windows/macOS/Linux

```
cd main
pip install -r requirements.txt
```
### 4 .Migrate/Create a database

```python manage.py```

### 5. Run the application 

**For linux and macOS**
Make the run file executable by running the code

```chmod 777 run```

Then start the application by executing the run file

```./run```

**On windows**
There are different ways for different operating system but one of this should work
```
set FLASK_APP=routes
flask run

or 

$env:FLASK_APP = "routes"
flask run

or

setx FLASK_APP=routes
flask run

```



