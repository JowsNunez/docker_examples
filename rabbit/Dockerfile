FROM rabbitmq:3.11


RUN rabbitmq-plugins enable rabbitmq_management
RUN rabbitmq-plugins enable rabbitmq_web_mqtt
RUN rabbitmq-plugins enable rabbitmq_web_stomp

EXPOSE 15672
EXPOSE 5672
EXPOSE 15674
