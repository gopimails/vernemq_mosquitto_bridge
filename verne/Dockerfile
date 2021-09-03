FROM vernemq/vernemq
WORKDIR /vernemq
COPY vernemq.conf vernemq.conf

EXPOSE 1884
ENV DOCKER_VERNEMQ_ACCEPT_EULA=yes

CMD ["start_vernemq"]