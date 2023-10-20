# simple_flask_webapp
If you want to create a backend for a larg site you can use this structure <br>
<h3>
.
├── app
│   ├── extensions.py
│   ├── __init__.py
│   ├── main
│   │   ├── __init__.py
│   │   └── routes.py
│   ├── models
│   │   ├── post.py
│   │   └── question.py
│   ├── posts
│   │   ├── __init__.py
│   │   └── routes.py
│   ├── questions
│   │   ├── __init__.py
│   │   └── routes.py
│   └── templates
│       ├── base.html
│       ├── index.html
│       ├── posts
│       │   ├── categories.html
│       │   └── index.html
│       └── questions
│           └── index.html
├── config.py
</h3>
<br>
<h2>Using : </h2><br>
<code>
  cd simple_flask_struc <br>
  export FLASK_APP=app <br>
  flask run --host "0.0.0.0:5555" --debug 
</code>
<br>
<h2>Note : </h2> you have to change the 5555 to the port you want your site to run from , then use the <a href='http://0.0.0.0:5555'>http://0.0.0.0:5555</a>
