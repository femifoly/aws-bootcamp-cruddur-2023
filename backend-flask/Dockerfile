FROM python:3.12.0a5-slim

# Inside Container
# Make a new folder inside container
WORKDIR /backend-flask

#Outside container --> Inside container
# this contains the libraries want to install to run the app
COPY requirements.txt requirements.txt

# Inside Container
# Inside the python libraries used for the app
RUN pip3 install -r requirements.txt

# Outside container -> Inside Container
# . mean everything in thhe current directory
# first period . - /backend-flask (outside container)

#second period . - /backend-flask (Inside container)
COPY . .

# Set environment variables (Env Vars)
# Inside container and will remain set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}

# CMD (command)
# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0","--port=4567"]