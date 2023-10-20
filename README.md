# simple_flask_webapp
If you want to create a backend for a larg site you can use this structure <br>
<h3>
'''
.
├── app<br>
│   ├── extensions.py<br>
│   ├── __init__.py<br>
│   ├── main<br>
│   │   ├── __init__.py<br>
│   │   └── routes.py<br>
│   ├── models<br>
│   │   ├── post.py<br>
│   │   └── question.py<br>
│   ├── posts<br>
│   │   ├── __init__.py<br>
│   │   └── routes.py<br>
│   ├── questions<br>
│   │   ├── __init__.py<br>
│   │   └── routes.py<br>
│   └── templates<br>
│       ├── base.html<br>
│       ├── index.html<br>
│       ├── posts<br>
│       │   ├── categories.html<br>
│       │   └── index.html<br>
│       └── questions<br>
│           └── index.html<br>
├── config.py<br>
</h3>
'''
<h2>Using : </h2><br>
<code>
  cd simple_flask_struc <br>
  export FLASK_APP=app <br>
  flask run --host "0.0.0.0:5555" --debug 
</code>
<br>
<h2>Note : </h2> you have to change the 5555 to the port you want your site to run from , then use the <a href='http://0.0.0.0:5555'>http://0.0.0.0:5555</a>
