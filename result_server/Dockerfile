FROM python:alpine
COPY ./Student_files/image_for_result_server /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 80
CMD python ./app.py