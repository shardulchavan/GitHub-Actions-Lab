FROM python:3.10-slim

WORKDIR /app

COPY ./backend/ . 
RUN pip install -r requirements.txt

# ENV OPENAI_API_KEY=${OPENAI_API_KEY}



EXPOSE 8000

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8001"]