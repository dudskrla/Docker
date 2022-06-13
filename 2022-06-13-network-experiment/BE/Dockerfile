FROM python:3.8.5

WORKDIR /BE

COPY BE/app ./

EXPOSE 8000

RUN apt-get update && apt-get -y install sudo
RUN pip install -r requirements.txt
RUN sudo apt-get install libgl1-mesa-glx -y


# ENTRYPOINT ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000", "--reload"]
ENTRYPOINT ["python", "run.py"]