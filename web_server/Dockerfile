FROM python:alpine
COPY ./web_server/image_for_web_server /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./app.py