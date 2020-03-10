FROM tensorflow/tensorflow

RUN mkdir /logs

# Tensorboard
EXPOSE 8080

CMD ["tensorboard", "--logdir", "/logs", "--port", "8080"]