FROM python:3

WORKDIR /usr/src/app

#Copy the content of the current folder in /usr/src/app
#ignoring the files specified in the .dockerignore file
COPY . .

#Install dependencies (-y to type y as confirmation during installation)
RUN pip3 install -r requirements.txt

#First command to be executed when the container runs
CMD ["python3", "./ascii_art.py"]

#Port to exposed in the container
#EXPOSE 8080