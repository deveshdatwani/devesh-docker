FROM ubuntu:20.04

COPY . .  

WORKDIR ./

EXPOSE 6700

RUN apt-get update 

RUN apt-get install -y python3-pip

RUN pip3 install -r requirements.txt

CMD ["python3", "app.py"]
