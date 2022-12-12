FROM nginx:1.23.0

# Install openssl
RUN apt-get update -yqq && \
        apt-get install -y openssl

# Copy Config Files
COPY nginx.conf /etc/nginx/
COPY conf.d/ /etc/nginx/conf.d/
COPY sites/ /etc/nginx/sites/