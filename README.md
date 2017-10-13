Docker for Flask
==================== 

### Pull
```sh
docker pull lucasko/flask
```

### Run
```sh
docker run --name flask -v $PWD/:/app/ -it -d -p 5000:5000  flask app.py
```

### Brows web application
[http://localhost:5000](http://localhost:5000)
