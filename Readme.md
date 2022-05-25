**Kubernetes MongoDB and MongoExpress Setup**

Define and apply a secret config yaml file with the contents and values below

    apiVersion: v1
    kind: Secret
    metadata:
      name: mongodb-secret
    type: Opaque
    data:
      mongo-root-username: ~
      mongo-root-password: ~
