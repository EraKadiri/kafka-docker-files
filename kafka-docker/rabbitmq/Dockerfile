FROM rabbitmq:3.10.2-management

# Install wget
RUN apt-get update && \
    apt-get install -y wget && \
    apt-get clean

# Download the delayed message exchange plugin
RUN wget https://github.com/rabbitmq/rabbitmq-delayed-message-exchange/releases/download/3.10.2/rabbitmq_delayed_message_exchange-3.10.2.ez \
    -O /opt/rabbitmq/plugins/rabbitmq_delayed_message_exchange-3.10.2.ez


RUN rabbitmq-plugins enable rabbitmq_delayed_message_exchange