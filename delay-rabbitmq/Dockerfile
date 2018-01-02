#Version: 1.0.0
FROM rabbitmq:3-management
COPY rabbitmq_delayed_message_exchange-3.7.0.ez /plugins/rabbitmq_delayed_message_exchange-3.7.0.ez
RUN rabbitmq-plugins enable --offline rabbitmq_delayed_message_exchange