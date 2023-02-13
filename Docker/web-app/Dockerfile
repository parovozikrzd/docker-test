FROM python:3.6

RUN mkdir -p /scripts/webapp1/
WORKDIR /scripts/webapp1/

COPY . /scripts/webapp1/
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8080

CMD ["python","webapp.py"]