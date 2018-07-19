第一个问题
FLASK_APP = blog2/__init__.py
FLASK_ENV = development
FLASK_DEBUG = 0
In folder C:/practice/blog2
C:\practice\blog2\venv\Scripts\python.exe -m flask run
 * Serving Flask app "blog2/__init__.py"
 * Environment: development
 * Debug mode: off
Usage: python -m flask run [OPTIONS]

Error: While importing "blog2", an ImportError was raised:

Traceback (most recent call last):
  File "C:\practice\blog2\venv\lib\site-packages\flask\cli.py", line 235, in locate_app
    __import__(module_name)
  File "C:\practice\blog2\blog2\__init__.py", line 3, in <module>
    from flask_sqlalchemy import SQLAlchemy
ModuleNotFoundError: No module named 'flask_sqlalchemy'
Process finished with exit code 2
第二个问题
C:\Users\sunlanzi>pip3 install FlaskSQLAlchemy
Collecting FlaskSQLAlchemy
  Using cached https://files.pythonhosted.org/packages/c1/46/35786dd4ce741092917
82b1625c6f860d47397a4a08c0cbd9295f25bbf75/FlaskSQLAlchemy-0.1.1.tar.gz
Installing collected packages: FlaskSQLAlchemy
  Running setup.py install for FlaskSQLAlchemy ... error
    Complete output from command c:\users\sunlanzi\appdata\local\programs\python
\python36\python.exe -u -c "import setuptools, tokenize;__file__='C:\\Users\\sun
lanzi\\AppData\\Local\\Temp\\pip-install-3vgmjh01\\FlaskSQLAlchemy\\setup.py';f=
getattr(tokenize, 'open', open)(__file__);code=f.read().replace('\r\n', '\n');f.
close();exec(compile(code, __file__, 'exec'))" install --record C:\Users\sunlanz
i\AppData\Local\Temp\pip-record-r2pffj8n\install-record.txt --single-version-ext
ernally-managed --compile:
    running install
    Traceback (most recent call last):
      File "<string>", line 1, in <module>
      File "C:\Users\sunlanzi\AppData\Local\Temp\pip-install-3vgmjh01\FlaskSQLAl
chemy\setup.py", line 47, in <module>
        'FlaskSQLAlchemy = flasksqlalchemy.cli:cli',
      File "c:\users\sunlanzi\appdata\local\programs\python\python36\lib\distuti
ls\core.py", line 148, in setup
        dist.run_commands()
      File "c:\users\sunlanzi\appdata\local\programs\python\python36\lib\distuti
ls\dist.py", line 955, in run_commands
        self.run_command(cmd)
      File "c:\users\sunlanzi\appdata\local\programs\python\python36\lib\distuti
ls\dist.py", line 974, in run_command
        cmd_obj.run()
      File "C:\Users\sunlanzi\AppData\Local\Temp\pip-install-3vgmjh01\FlaskSQLAl
chemy\setup.py", line 20, in run
        raise Exception("You probably meant to install and run Flask-SQLAlchemy"
)
    Exception: You probably meant to install and run Flask-SQLAlchemy

    ----------------------------------------
Command "c:\users\sunlanzi\appdata\local\programs\python\python36\python.exe -u
-c "import setuptools, tokenize;__file__='C:\\Users\\sunlanzi\\AppData\\Local\\T
emp\\pip-install-3vgmjh01\\FlaskSQLAlchemy\\setup.py';f=getattr(tokenize, 'open'
, open)(__file__);code=f.read().replace('\r\n', '\n');f.close();exec(compile(cod
e, __file__, 'exec'))" install --record C:\Users\sunlanzi\AppData\Local\Temp\pip
-record-r2pffj8n\install-record.txt --single-version-externally-managed --compil
e" failed with error code 1 in C:\Users\sunlanzi\AppData\Local\Temp\pip-install-
3vgmjh01\FlaskSQLAlchemy\



！！！！！！网站：http://www.cnblogs.com/mysql-dba/p/6070258.html
