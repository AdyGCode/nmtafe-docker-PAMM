# Filename: docker/apache/Dockerfile

FROM httpd:2.4.51

# Copy the hello world configuration to the apache configs
COPY helloworld.apache.conf /usr/local/apache2/conf/helloworld.apache.conf

RUN echo "Include /usr/local/apache2/conf/helloworld.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf

