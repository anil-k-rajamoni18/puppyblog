## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)


This is Simple Puppy blog website ,developed using Flask ,SqlAlchemy ,Its the CRUD operations 




# Flask

Flask is a lightweight Web Server Gateway Interface WSGI web application framework that was created to make getting started easy and making it easy for new beginners. With the tendency to scale up to complex applications.

Flask has its foundation around Werkzeug and Jinja2 and has become one of the most popular Python web application frameworks.

As a developer in developing a web app in python, you may be using a framework to your advantage. A framework is a code storage that should help developers achieve the required result by making work easier, scalable, efficient and maintainable web applications by providing reusable code or extensions for common operations.

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [flask](https://flask.palletsprojects.com/en/1.1.x/)
* [SqlAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [Bootstrap](https://getbootstrap.com/)


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install flask.

```bash
pip install flask
```

## Usage

```python
Hello World
Great! Now that everything is installed you can create your first Flask App.

Use the line below to import Flask in Python.

from flask import Flask
Create app, that hosts the application

app = Flask(__name__)
Then you need a route that calls a Python function. A route maps what you type in the browser (the url) to a Python function.

@app.route('/')
    def index():
The function should return something to the web browser,

return 'Web App with Python Flask!'
Almost done, the server needs to be started. This starts the web app at port 81.

app.run(host='0.0.0.0', port=81)
Enter the url http://localhost:81/ in your web browser.

Code summary:

from flask import Flask

app = Flask(__name__)

@app.route('/')
def index():
    return 'Web App with Python Flask!'

app.run(host='0.0.0.0', port=81)
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure to update tests as appropriate.



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

ANIL K RAJAMONI anil.k.rajamoni99@gmail.com

Project Link: [https://github.com/anil-k-rajamoni18/puppyblog](https://github.com/anil-k-rajamoni18/puppyblog)

Deployed on Heroku:[https://blogpuppy.herokuapp.com/]



## License
[MIT](https://choosealicense.com/licenses/mit/)



