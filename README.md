
EventFlowApi : It is write api . Configured with EventFlow , EventStore and RabbitMq.   

EventFlowApi.Read: It is read api, Configured with Eventflow and Elastic Search. It configured a RabbitMq subscriber at startup.which invoked Domain event subscribers when data is arrived.
and insert the data in ElasticSearch.
 
 


Prerequisites :

1.  download and install Aspnetcore 3.1 framework.
2.  Set following environment variables
   
    ASPNETCORE_ENVIRONMENT, 
    ELASTICSEARCHURL, 
    EVENTSTOREURL,
    RABBITMQCONNECTION
  
    


 

