# openshift-training-assignment

1. ## Things to consider:
    1. Refer the **application.properties** file located at **src/main/resources/**
    2. Wherever **variable substitution** is available kindly provide an **appropriate variable**
    3. You'll need a database container as well, am using MySQL as my database
       1. The **image name** is **mysql**
       2. The **tag** is **8.0.26**
    4. Am using RabbitMQ as a message broker, so you'll have to spin a RabbitMQ container as well
       1. The **image name** is **rabbitmq**
       2. The **tag** is **3.9.2-management**
       3. Expose ports **5672** and **15672**
2. ## Tip
    1. All these 5 containers need to be on the same network
