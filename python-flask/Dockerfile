FROM python:alpine
WORKDIR /app
COPY . .
RUN pip install --trusted-host files.pythonhosted.org -r requirements.txt
CMD ["flask", "run", "--host=0.0.0.0"]
