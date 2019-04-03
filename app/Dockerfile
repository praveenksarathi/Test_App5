#The repository from which Flask is pulled in
FROM tiangolo/uwsgi-nginx-flask:flask

MAINTAINER praveenksarathi

#Moving the base application folder to Flask/app/ folder
COPY . /app

WORKDIR /app

# tell the port number the container should expose
EXPOSE 5000

ENTRYPOINT ["python"]

# Command to run the program
CMD ["app_rest.py","-p 5000"]
