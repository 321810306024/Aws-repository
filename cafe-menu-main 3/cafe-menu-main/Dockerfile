FROM nginx:1.27-alpine

LABEL org.opencontainers.image.title="Cafe Menu Frontend"
LABEL org.opencontainers.image.description="Frontend-only CI/CD assessment application"

COPY . /usr/share/nginx/html/
COPY default.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
