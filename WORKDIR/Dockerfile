FROM almalinux:9
RUN cd /tmp                       # has NO lasting effect — the cd is gone after this layer
RUN mkdir /app
WORKDIR /app
RUN echo "Present directory :${PWD}"
CMD ["Sleep","100"]