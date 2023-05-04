# webfortune

## Routes

- display the fortune /fortune/
- display the cow saying your message /cowsay/<message>/
- display the cow saying fortune /cowfortune/


## Docker

- build the docker image 
> docker build -t domimel/webfortune
- run docker
> docker run -dp 8009:5000 domimel/webfortune
- URL
> http://10.92.21.106:8009/
- check you container
> docker ps
- kill the docker image
> docker kill

## Local

- create virtual environment 
> python3 -m venv env
- activate environment
> source env/bin/activate
- install requirements 
> pip install -r requirements.txt
- run flask
> flask run --host=0.0.0.0 --port=8009
- URL
> http://10.92.21.106:8009/


