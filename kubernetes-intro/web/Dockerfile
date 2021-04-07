FROM nginx:latest

COPY app.conf /etc/nginx/conf.d/
COPY /app /app
WORKDIR /app
RUN useradd -r -u 1001 appuser && chown -R appuser /app

COPY app.conf /etc/nginx/conf.d/
EXPOSE 8000
