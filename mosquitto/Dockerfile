FROM eclipse-mosquitto
WORKDIR /mosquitto/config

COPY mosquitto.conf mosquitto.conf
EXPOSE 1883 9000

CMD ["/usr/sbin/mosquitto", "-c", "/mosquitto/config/mosquitto.conf"]