# Getting-Started-With-RabbitMQ
Here we will download and start RabbitMQ instance from scratch.

1) Because RabbitMQ is built on Erlang, we must first install Erlang. 
           - Go to the Erlang downloads page and get the erlang binary file for Windows.
 
2) Now download RabbitMQ installation from the RabbitMQ downloads page.
3) The RabbitMQ command prompt should have been installed as part of the previous installation.It should be opened.
         To use the command, go to the RabbitMQ Server Location and type it in:
            
        rabbitmq-server start 
       
4) If RabbitMQ already running we get the above message

  
![Screenshot (310)](https://user-images.githubusercontent.com/79251268/136953968-d41f88f6-8e0d-476e-b366-96bce11e662f.png)

 * The reason you are getting the error might be because of any running instance. To know the status use the following command:
 
        rabbitmqctl.bat status 
  
 * If it is up, this could the reason you are getting the error
 * You can use the following command to make the server down:

        rabbitmqctl.bat stop 
       
  ![Screenshot (309)](https://user-images.githubusercontent.com/79251268/136955269-dd0eb590-2da0-4fdc-b8d9-f7497932d398.png)
       
 * Now you can try starting the rabbitmq-server by hitting the following command:
  
       rabbitmq-server start 
       

![Screenshot (311)](https://user-images.githubusercontent.com/79251268/136955707-bee996a1-12de-442c-b92f-debc80d7cfdb.png)

    
