FROM rabbitmq:3.6.9-management
ADD rabbitmq_delayed_message_exchange-20171215-3.6.x.ez /usr/lib/rabbitmq/lib/rabbitmq_server-3.6.9/plugins
RUN rabbitmq-plugins enable --offline rabbitmq_delayed_message_exchange
