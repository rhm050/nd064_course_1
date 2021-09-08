FROM python:2.7
LABEL maintainer="Md.Rakibul Hasan"

COPY techtrends /app
WORKDIR /app

EXPOSE 3111

RUN pip install -U pip && pip install -r requirements.txt 

CMD ["python", "init_db.py"]
CMD ["python", "app.py"]
