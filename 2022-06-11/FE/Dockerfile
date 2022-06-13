FROM python:3.8.5

WORKDIR /FE

COPY FE/Frontend ./

RUN pip install requests 
RUN pip install streamlit

EXPOSE 8501

# ENTRYPOINT ["streamlit", "run", "main.py", "--server.port", "8501", "--server.address", "127.0.0.1"]
# CMD streamlit run main.py \
#     --server.address 0.0.0.0 \
#     --server.port 8501 \
#     --server.runOnSave true

CMD ["streamlit", "run", "main.py"]