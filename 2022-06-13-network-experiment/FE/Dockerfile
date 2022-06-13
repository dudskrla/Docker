FROM python:3.8.5

WORKDIR /FE

COPY FE/Frontend ./

RUN pip install requests 
RUN pip install streamlit

EXPOSE 8501

ENTRYPOINT ["streamlit", "run", "main.py"]