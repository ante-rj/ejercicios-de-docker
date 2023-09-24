FROM python:latest
ENV prueba=1234
WORKDIR /app
COPY static/  app/static/
COPY templates/ app/templates/
COPY app.py app/
EXPOSE 5050
RUN pip install flask
CMD python3 app/app.py