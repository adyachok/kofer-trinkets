FROM tensorflow/tensorflow

RUN mkdir /logs

# Tensorboard
EXPOSE 8080

CMD ["tensorboard", "--logdir", "/logs", "--host", "0.0.0.0", "--port", "8080"]