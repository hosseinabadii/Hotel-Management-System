FROM python:3.11.9-alpine3.20

WORKDIR /usr/backend

COPY requirements.txt ./

RUN pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 8000

CMD [ "fastapi", "run", "server.py" ]
